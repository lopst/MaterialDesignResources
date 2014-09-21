Intro
----------------------------------------------------------------------
Material Designにあるルールに則ったAndroid用リソースを定義. 


Typography
----------------------------------------------------------------------
Typographyに関する参考ページ.

 - [Typography | Android Developers](http://developer.android.com/design/style/typography.html)
 - [Typography - Style - Google design guidelines - ](http://www.google.com/design/spec/style/typography.html)

### Implementation

定義リソース

 - Typographic Scale & Basic Styles
 - Basic colors/Color contrast

**/res/values/fonts.xml**
```xml
<dimen name="Material.Text.Display4.Size">112sp</dimen>
<dimen name="Material.Text.Display3.Size">56dp</dimen>
<dimen name="Material.Text.Display2.Size">45sp</dimen>
<dimen name="Material.Text.Display1.Size">34sp</dimen>
<dimen name="Material.Text.Headline.Size">24sp</dimen>
<dimen name="Material.Text.Title.Size">20sp</dimen>
  ...

<!-- Light is Normal -->
<integer name="Material.Text.Style.Light">0</integer>
<!-- Regular is Bold -->
<integer name="Material.Text.Style.Regular">1</integer>
<!-- Medium is Normal -->
<integer name="Material.Text.Style.Medium">0</integer>

<integer name="Material.Text.Display4.Style">@integer/Material.Text.Style.Light</integer>
<integer name="Material.Text.Display3.Style">@integer/Material.Text.Style.Regular</integer>
<integer name="Material.Text.Display2.Style">@integer/Material.Text.Style.Regular</integer>
<integer name="Material.Text.Display1.Style">@integer/Material.Text.Style.Regular</integer>
  ...

<!-- For Light Theme Resource -->
<color name="Material.Text.Color.Primary.Light">#1C1C1C</color>
<color name="Material.Text.Color.Secondary.Light">#727272</color>
<!-- For Dark Theme Resource -->
<color name="Material.Text.Color.Primary.Dark">#E3E3E3</color>
<color name="Material.Text.Color.Secondary.Dark">#323232</color>
```

未定義

 - Roboto typeface
 - Line Height
 - Line breaking rules / Hyphenation
 - Characters per line lengths
 - Tracking and kerning

### Run
![enter image description here](https://lh5.googleusercontent.com/XE5GvmSUqDOo-hMYP5VJDx1NPqeyvVbvOQWaVr-c39c=s600 "materialdesign_typography.png")


------------------------------------------------------------------------------

Copyright
------------------------------------------------------------------------------
> Copyright 2014 yuki312 All Right Reserved.
> 
> Licensed under the Apache License, Version 2.0 (the "License");
> you may not use this file except in compliance with the License.
> You may obtain a copy of the License at
> 
>    http://www.apache.org/licenses/LICENSE-2.0
> 
> Unless required by applicable law or agreed to in writing, software
> distributed under the License is distributed on an "AS IS" BASIS,
> WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
> See the License for the specific language governing permissions and
> limitations under the License.
