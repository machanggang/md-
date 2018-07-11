1. NullPointerException
    需要使用对象的地方使用了null，会抛出该异常。如：
      * 调用null对象的实例方法（非static方法）
      * 访问或修改null对象的非静态字段字段
      * 将null作为一个数组，访问其长度
      * 将null作为一个数组，访问或修改其某个下标值（部分jdk中文版API上翻译为“时间片”，实际源码上注释为"slots"）
      * 抛异常时抛出了null （throw null;）

2. ClassCastException


3. IOException
