# ColorfulStatusBar
Android app状态栏变色。

适用于版本大于等于19以上。

## 用法

Activiy onCreate中添加：

```java
StatusBarCompat.compat(this);
```

如果需要制定状态栏颜色,使用此方法：

```java
StatusBarCompat.compat(this, 0xFFFF0000);
```