#ScrollableAppBar

<span class="badge-paypal"><a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&amp;hosted_button_id=LY7EX8WMWPWV6" title="Donate to this project using Paypal"><img src="https://img.shields.io/badge/paypal-donate-yellow.svg" alt="PayPal donate button" /></a></span>
[![Twitter](https://img.shields.io/badge/Twitter-@LacorteMichele-blue.svg?style=flat)](https://twitter.com/LacorteMichele)

[![API](https://img.shields.io/badge/API-21%2B-blue.svg?style=flat)](https://android-arsenal.com/api?level=21)

[![License](https://img.shields.io/badge/license-Apache%202-4EB1BA.svg)](https://www.apache.org/licenses/LICENSE-2.0.html)

[![Android Arsenal](https://img.shields.io/badge/Android%20Arsenal-ScrollableAppBar-brightgreen.svg?style=flat)](https://android-arsenal.com/details/1/2816)

[![alt tag](http://www.android-gems.com/badge/michelelacorte/ScrollableAppBar.svg)](http://www.android-gems.com/lib/michelelacorte/ScrollableAppBar?lib_id=718)

This is a Scrollable App Bar for Android, this is a library to make your App Bar extendable and retractable easier!!

![alt tag](https://github.com/michelelacorte/ScrollableAppBar/blob/master/ScrollableAppBarExample.gif)

##DONATIONS

This project needs you! If you would like to support this project's further development, the creator of this project or the continuous maintenance of this project, feel free to donate. Your donation is highly appreciated (and I love food, coffee and beer). Thank you!

**PayPal**

* **[Donate $5]**: Thank's for creating this project, here's a coffee (or some beer) for you!

* **[Donate $10]**: Wow, I am stunned. Let me take you to the movies!ù

* **[Donate $15]**: I really appreciate your work, let's grab some lunch!

* **[Donate $25]**: That's some awesome stuff you did right there, dinner is on me!

* **[Donate $50]**: I really really want to support this project, great job!

* **[Donate $100]**: You are the man! This project saved me hours (if not days) of struggle and hard work, simply awesome!

* **[Donate $2799]**: Go buddy, buy Macbook Pro for yourself!

Of course, you can also choose what you want to donate, all donations are awesome, or just choose import here <span class="badge-paypal"><a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&amp;hosted_button_id=LY7EX8WMWPWV6" title="Donate to this project using Paypal"><img src="https://img.shields.io/badge/paypal-donate-yellow.svg" alt="PayPal donate button" /></a></span>

##USAGE
ScrollableAppBar is pushed to JCenter, so you just need to add the following dependency to your `build.gradle`.

```
compile 'it.michelelacorte.scrollableappbar:library:1.0.0'
```

In alternative you can use AAR repository with:

```
allprojects {
    repositories {
        maven { url "https://dl.bintray.com/michelelacorte/maven/" }
        jcenter()
        mavenCentral()

    }
}
```

And add this dependecies

```
compile 'it.michelelacorte.scrollableappbar:library:1.0.0@aar'
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

[Donate $5]: 		https://www.paypal.me/MicheleLacorte/5
[Donate $10]:  		https://www.paypal.me/MicheleLacorte/10
[Donate $15]:  		https://www.paypal.me/MicheleLacorte/15
[Donate $25]:  		https://www.paypal.me/MicheleLacorte/25
[Donate $50]: 		https://www.paypal.me/MicheleLacorte/50
[Donate $100]: 		https://www.paypal.me/MicheleLacorte/100
[Donate $2799]: 	https://www.paypal.me/MicheleLacorte/2799
