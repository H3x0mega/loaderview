# LoaderView
The LoaderView shows an indeterminate ```ProgressBar``` while you load content on the background. This view lets you handle the failure and success scenarios of the loading process by showing a friendly error message (with a 'Try Again' button), or by removing the view completely.

### Features
- A retry action callback
- A queue for the fade transition animations, in order to avoid them overlapping
- Customizable messages, colors and drawables that can be set programmatically or in your XML layout

### Usage
Just add
```
compile 'com.h3x0mega.androidbits:loader-view:0.1'
```
to your ```build.gradle``` file

### Sample

To know how to use the LoaderView, check the [sample app](https://github.com/H3x0mega/android-bits) at the android-bits repository!

<p align="center"><img src="http://zippy.gfycat.com/ClearcutEminentAustraliancurlew.gif" width="300" height="442"/></p>


License
-------

    Copyright 2015 Francois Jeanneret

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
