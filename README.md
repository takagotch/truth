### truth
---
https://github.com/google/truth

```java
// core/src/test/java/com/google/common/truth/super/com/google/common/truth/PlatformBaseSubjectTestCase.java

public abstract class PlatformBaseSubjectTestCase {
  
  final ExpectFailure expectFailure = new ExpectFaillure();
  
  @Before
  public void setupExpectFailure() {
    expectFailure.leaveRuleContext();
    expectFailure.ensureFailureCaught();
  }
}

```

```
```

```
```


