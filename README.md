# CircleView
>  Click to see [English Document](https://github.com/strugglelin/CircleView/blob/master/README-en.md)
- 作者：strugglelin
- 概述


![示意图](https://raw.githubusercontent.com/strugglelin/CircleView/master/image/Introduction.png)


**注：关于该开源项目的意见 & 建议可在Issue上提出。欢迎 Star ！**

## 1. 简介
一款 基础的 `Android`自定义`View`控件
>Github地址：[CircleView](https://github.com/strugglelin/CircleView)

![示意图](https://raw.githubusercontent.com/strugglelin/CircleView/master/image/circleview.png)


## 2. 应用场景
一个自定义圆形的View


## 3. 特点

##### 3.1 可以自定义颜色的圆形View


## 4. 具体使用

##### 步骤1：导入控件库

*build.Gradle*

```
dependencies {
   implementation 'com.strugglelin.circleview:CircleView:1.0.4'
}
```

##### 步骤2：设置动画属性
- 属性说明

```
<attr name="circle_color" format="color"/>
```

- 使用示例
在`XML`文件中进行设置

```
    <com.strugglelin.circleview.CircleView
        android:layout_width="80dp"
        android:layout_height="80dp"
        android:padding="10dp"
        android:layout_margin="10dp"
        android:background="#f00"
        app:circle_color="#ff0"
        app:layout_constraintLeft_toLeftOf="parent"
        app:layout_constraintTop_toTopOf="parent"/>
```

## 5.完整Demo地址
[Github地址：CircleView](https://github.com/strugglelin/CircleView)


## 6.开源协议

`DIY_View` 遵循 `MIT` 开源协议

## 7. 贡献代码
- 具体请看：[贡献代码说明](https://github.com/strugglelin/CircleView/blob/master/CONTRIBUTING.md)
- 关于该开源项目的意见 & 建议可在`Issue`上提出。欢迎 Star ！

## 8. 版本说明
2019-08-01 v1.0.4 ：新增 自定义 圆形控件

# 关于作者
- ID：Strugglelin
- E - mail：[18950261460@163.com](18950261460@163.com)
- Github：[https://github.com/strugglelin](https://github.com/strugglelin)
- CSDN：[https://blog.csdn.net/BlueSky003](https://blog.csdn.net/BlueSky003)