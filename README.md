# DE
Contact Tracing - Germany

On April 26 Chancellery Minister Helge Braun and Health Minister Jens Spahn said in a joint statement that German Federal Government would change their programs & adopt a decentralized model for the National contact-tracing app.

Until April 24 Germany was still officially backing Fraunhofer HHI solution, based on centralized PEPP-PT/NTK protocol.

PEPP-PT | https://github.com/ct-report/PEPP-PT
--------|-------------------------------------

\
However, such centralized solution isn't supported by the new "Nofitication Exposures" APIs by Apple+Google for BLE contact-tracing (release to developers expected on April 28). Besides, it was affected by specific issues for BLE background detection on iOS devices.

Therefore, the German Government together with some partners - including SAP and T-Systems - is now working on **CORONA-WARN-APP**, that relies on Apple+Google Exposure Notifications API.

On May 30th : first release of source-code for iOS&Android apps.

**On June 16th the app has been officially published on Google Play Store & Apple App Store.**

Play Store | https://play.google.com/store/apps/details?id=de.rki.coronawarnapp
----------------|----
Sources | https://github.com/corona-warn-app/
References | https://www.coronawarn.app/en/

- APKLAB Analysis

Build | Link
------|-----
1.0.0 #27 Play Store | https://apklab.io/apk.html?hash=a2c7979dd32f05cc1bd93d992a382f9b60c8556641e34458588bfbee65d927b2
0.5.4 #4 Release | https://apklab.io/apk.html?hash=cd9edc4c3a6bb2a5c5106f65551ea504dd2e62760e280b5e9175a1aca65790aa
0.5.4 #4 Debug | https://apklab.io/apk.html?hash=388e273f18804459bcc275bd2259c4333aa61a60039159a51f50f701cdec4e6e

- JoeSandbox Report

Build | Link
------|-----
1.0.0 #27 Play Store | https://www.joesandbox.com/analysis/238833/0/html
0.5.4 #4 Release | https://www.joesandbox.com/analysis/234408/0/html
0.5.4 #4 Debug | https://www.joesandbox.com/analysis/234409/0/html


\
It's a decentralized solution with architecture based on DP^3T + TCN - used by former proposal **Ito** .

DP^3T | https://github.com/ct-report/DP-3T
------|-----------------------------------

TCN / Ito | https://github.com/ct-report/TCN 
----------|---------------------------------
