# AndroidProblemSets

问题描述：

```
com.android.ide.common.process.ProcessException: org.gradle.process.internal.ExecException: Process 'command 'C:\Program Files\Java\jdk1.7.0_51\bin\java.exe'' finished with non-zero exit value 1 
```

解决方案：
```
defaultConfig {

// Enabling multidex support.
multiDexEnabled true
}
```

---
