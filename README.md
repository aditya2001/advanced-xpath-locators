## Advanced Xpath Locators

### 1. Xpath syntax?

```java
Xpath=//tagname[@attribute='value']
```

### Xpath using Following?
Following selects all the nodes that follow current node.

![img.png](img.png)

```java
//tagname[@attribute=’value’]//following::tagname 

https://accounts.lambdatest.com/register?_gl=1*196o109*_gcl_au*NzQ3MjMwODk5LjE3MjYxNTUzMDg.

//div[contains(@class,'login')]//following::input
```

### Xpath using Following-Sibling?

The following-sibling selects all sibling nodes after the current node which are same level as current node.
Hence, the following-sibling will return you to the node at the same level and after the current node.

![img_3.png](img_3.png)

```java
//div[contains(@class,'error__border')]//following-sibling::div
```

### Xpath using Parent?



