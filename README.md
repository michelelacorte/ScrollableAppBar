#ScrollableAppBar

##COMING SOON!

![alt tag](http://i.giphy.com/3oEdv7ptcnY9VKatMY.gif)


This is a Scrollable App Bar for Android, this is a library to make your App Bar extendable and retractable easier!!

##USAGE
ScrollableAppBar is pushed to JCenter, so you just need to add the following dependency to your `build.gradle`.

```
Coming Soon!
```

In alternative you can use AAR repository with:

```
Coming Soon!
```

And add this dependecies

```
Coming Soon!
```
In your layout.xml replace your old AppBarLayout with:

```
<it.michelelacorte.scrollableappbar.ScrollableAppBar
    android:id="@+id/appbar"
    android:layout_width="match_parent"
    android:layout_height="380dp"
    android:theme="@style/ThemeOverlay.AppCompat.Dark.ActionBar"
    android:fitsSystemWindows="true">
</it.michelelacorte.scrollableappbar.ScrollableAppBar>
```

Then in your `MainActivity.java`

```
ScrollableAppBar appBarLayout = (ScrollableAppBar) findViewById(R.id.appbar);

//To give the effect "in the middle" of the image (like gif)
appBarLayout.collapseToolbar();
```

See app example for more help!!

##SYSTEM REQUIREMENT

Android API 21+

##CHANGELOG

**v1.0.0**
- Support API 21+
- Constructor method `ScrollableAppBar(Context context)` and `ScrollableAppBar(Context context, AttributeSet attrs)`
- Added method `expandToolbar()` default false
- Added method `collapseToolbar()` default false
- Added method `expandToolbar(boolean withAnimation)`
- Added method `collapseToolbar(boolean withAnimation)`

##CREDITS

Author: Michele Lacorte (micky1995g@gmail.com)

##LICENSE

```
Copyright 2015 Michele Lacorte

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
