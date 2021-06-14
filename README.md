# TimePicker
![Build Status](https://ci.vnapps.com/buildStatus/icon?job=dialtimerpicker&subject=Release&status=1.1.${buildNumber}(${startTime}))
![Build Status](https://ci-backup.vnapps.com/buildStatus/icon?job=dialTimePicker&subject=Backup&status=${duration}(${startTime}))
```gradle
// Using Git: git submodule add https://github.com/nghuyy/dialtimerpicker.git

dependencies { 
        implementation 'androidx.cardview:cardview:1.0.0'
		implementation fileTree(include: [ '*.aar'], dir: '../dialtimerpicker/dist')        
		...

```



<H2>Images</H2>
<img width="270px" height="480" src="/images/3.png" />
<img width="270px" height="480" src="/images/2.png" />
<br>

<H2>Usage</H2>

```xml
<picker.ugurtekbas.com.Picker.Picker
        android:id="@+id/picker"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        />

<!-- or with some attributes in xml -->        
<picker.ugurtekbas.com.Picker.Picker
        xmlns:app="http://schemas.android.com/apk/res-auto"
        android:id="@+id/amPicker"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:layout_centerInParent="true"
        app:hourFormat="false"
        app:canvasColor="#ffffff"
        app:textColor="#000000"
        app:trackSize="20dp"
        app:dialRadius="60dp"
        app:trackIconBitmap="@drawable/ic_baseline_nights"
        app:trackIconSize="48"
                                     
        />

```

```
<H2>License</H2>
    Copyright 2021 Huy Nguyen @vnapps.com

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

     http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
