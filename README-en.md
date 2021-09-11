# CircleView
>  Click to see [中文文档](https://github.com/strugglelin/CircleView/blob/master/README.md)
- Author：strugglelin
- Summary


![示意图](https://raw.githubusercontent.com/strugglelin/CircleView/master/image/Introduction-en.png)


**Note：Opinions & Suggestions about this open source project can be put forward in Issue。Welcome Star ！**

## 1. Introduction
a `CircleView`
>Github Address：[CircleView](https://github.com/strugglelin/CircleView)

![示意图](https://raw.githubusercontent.com/strugglelin/CircleView/master/image/circleview.png)


## 2. Application Scenarios
A custom Circle View


## 3. Feature

##### 3.1 Can customize the color of the CircleView


## 4. Usage

##### Step 1：Import Library

*root directory build.Gradle*

```
allprojects {
    repositories {
        google()
        jcenter()
        // jitpack 远程仓库
        maven { url 'https://jitpack.io' }
    }
}
```

*app module build.Gradle*

```
dependencies {
   // implementation 'com.strugglelin.circleview:CircleView:1.0.4'
   implementation 'com.github.strugglelin:CircleView:1.0.4'
}
```

##### Step 2：Set animation properties
- Attributes Description:

```
<attr name="circle_color" format="color"/>
```

- Use examples
Set in the ` XML ` file

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

## 5.Complete Demo
[Github Address：CircleView](https://github.com/strugglelin/CircleView)


## 6.LICENSE

`CircleView` is available under the `MIT` license.

## 7.Contribute
- Before you open an issue or create a pull request, please read [Contributing Guide](https://github.com/strugglelin/CircleView/blob/master/CONTRIBUTING.md) first.
- Note：Opinions & Suggestions about this open source project can be put forward in Issue。Welcome Star ！

## 8.Release
2019-08-01 v1.0.4 ：add Circle View

# About the author
- ID：Strugglelin
- E - mail：[18950261460@163.com](18950261460@163.com)
- Github：[https://github.com/strugglelin](https://github.com/strugglelin)
- CSDN：[https://blog.csdn.net/BlueSky003](https://blog.csdn.net/BlueSky003)