# fb-ssl-bypass

***This is for Facebook APK version 270.1.0.66.127(x86)***

Install the apk and run it at least once otherwise you will not be able to see the  packages.

Copy libcoldstart.so into directory as given below<br/>
`$ adb push libcoldstart.so /data/data/com.facebook.katana/lib-xzs/`

Then make sure you run command as root on mobile device<br/>
`$ adb shell`<br/>
`$ su`<br/>
`$ chmod 777 libcoldstart.so`<br/>

Now you will be able to intercept the requests.

___________________________________________________________________________
*Note : use java-open-jdk-11 and a burpsuite compatible with TLSv1.3. Burpsuite v1.7.36 is highly recommended!*
