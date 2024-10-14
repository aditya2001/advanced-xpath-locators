## Advanced Xpath Locators

### 1. Xpath syntax?

```java
Xpath=//tagname[@attribute='value']
```

### Xpath using Following?

```java
//tagname[@attribute=’value’]//following::tagname 

https://accounts.lambdatest.com/register?_gl=1*196o109*_gcl_au*NzQ3MjMwODk5LjE3MjYxNTUzMDg.

//div[contains(@class,'login')]//following::input
```
Following selects all the elements that follow current node.

### XPath using Following-Sibling?


