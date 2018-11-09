FilletImageView
===============

Expand on [circleImageview](https://github.com/hdodenhof/CircleImageView), a fillet imageview

![CircleImageView](https://github.com/xiaoXiangGuo/FilletImageView/blob/master/screenshot.png)

Gradle
------
```javascript
allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}

dependencies {
    ...
    implementation 'com.github.xiaoXiangGuo:FilletImageView:1.0.0'
}
```

Usage
-----
```xml
<com.zcx.filletimageview.FilletImageView
                android:layout_width="160dp"
                android:layout_height="160dp"
                android:layout_gravity="center"
                android:scaleType="centerCrop"
                android:src="@drawable/hugh"
                app:fiv_border_color="@color/dark"
                app:fiv_border_width="2dp"
                app:fiv_radius="10dp" />
```
