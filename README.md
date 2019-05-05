
![all](result/all.png)     

![checkboxpreference](result/che
<EditTextPreference
            android:key="EditTextPreference"
            android:title="Edit Text Preference"
            android:summary="An example that uses a edit text dialog"
            android:dialogTitle="Enter your favorite animal"/>
```
![EditTextPreference](result/EditTextPreference.png)  
ListPreference：
```
<ListPreference
            android:key="ListPreference"
            android:title="List Preference"
            android:summary="An Example that uses a list dialog"
            android:entries="@array/lists"
            android:entryValues="@array/lists"/>
```
![ListPreference](result/ListPreference.png)  
Screen preference：
```
 <PreferenceScreen
            android:key="Screen preference"
            android:title="Screen preference"
            android:summary="Shows another screen of preferences">
            <CheckBoxPreference
                android:key="Toggle preference"
                android:title="Toggle preference"
                android:summary="Preference that is on the next screen but same hierarchy" />
        </PreferenceScreen>
```
![Screen preference](result/Screen preference.png)  

Intent preference：
```
<PreferenceScreen
            android:title="Intent preference"
            android:summary="Launches an Activity from an intent" >
            <intent
                android:action="android.intent.action.VIEW"
                android:data="http://www.baidu.com/"/>
        </PreferenceScreen>
![Intent preference](result/Intent preference.png)  
Preference attrib
