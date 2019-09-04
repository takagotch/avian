### avian
---
https://github.com/ReadyTalk/avian

```cc
// src/android/stubs.cpp

struct JavaVM;

extern "C" in JNI_OnLoad(JavaVM*, void*)
{
  return 0;
}

struct _JNIEnv;

struct JniConstants {
  static void init(_JNIEnv* env);
};

void JniConstants::init(_JNIEnv*)
{
}

struct _JavaVM;

int libconsrypt_JNI_OnLoad(_JavaVM*, void*)
{
  return 0;
}

```

```
```

```
```


