# ThreeDLayout
A 3D Layout,When you use it warp other view,it can became a 3D view

# preview

![image](https://github.com/githubwing/ThreeDLayout/raw/master/img/1.gif）


![image](https://github.com/githubwing/ThreeDLayout/raw/master/img/2.gif)

# How to Use

1.Put ThreDLayout as your parent view

```
 <com.wingsofts.threedlayout.ThreeDLayout
      android:background="@color/colorPrimary"
      android:id="@+id/td_header"
      android:layout_width="match_parent"
      android:layout_height="wrap_content"
      >

   <TextView
       android:id="@+id/textView"
      android:text="30℃"
      android:textColor="#fff"
      android:gravity="center"
      android:textSize="80sp"
      android:layout_width="match_parent"
      android:layout_height="wrap_content"
      />
  </com.wingsofts.threedlayout.ThreeDLayout>

```

then,you can call method 

```
//set touch mode enable
layout.setTouchable(true);

//set touch mode
layout.setTouchMode(ThreeDLayout.MODE_BOTH_X_Y);

//start turn Animate
startVerticalAnimate(long duration);
startVerticalAnimateDelayed(final long delayed, final long duration)

startHorizontalAnimate(long duration)
startHorizontalAnimateDelayed(final long delayed, final long duration)

```

# License

    Copyright 2016 androidwing1992

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at
    
        http://www.apache.org/licenses/LICENSE-2.0
    
    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
