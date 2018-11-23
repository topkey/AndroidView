android提供了一个计时器组件——Chronometer，继承自TextView。显示的是某个时间点开始以及之后的时间增加。
在XML中配置：

```
 \<Chronometer android:layout\_width="wrap\_content" android:layout\_height="wrap\_content"/\>
```

Chronometer的几个主要的方法：

```c
//开始
mChronometer.start();
//停止
mChronometer.stop();
//设置初始值（重置）
mChronometer.setBase(longbase);
//事件监听器，时间发生变化时可进行操作
mChronometer.setOnChronometerTickListener();
//设置格式(默认"MM:SS"格式)
mChronometer.setFormate("%s");
```