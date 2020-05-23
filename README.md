# DE
Contact Tracing - Germany

On April 26 Chancellery Minister Helge Braun and Health Minister Jens Spahn said in a joint statement that German Federal Government would change their programs & adopt a decentralized model for the National contact-tracing app.

Until April 24 Germany was still officially backing Fraunhofer HHI solution, based on centralized PEPP-PT/NTK protocol.

PEPP-PT | https://github.com/ct-report/PEPP-PT
--------|-------------------------------------

\
However, such centralized solution isn't supported by the new "Nofitication Exposures" APIs by Apple+Google for BLE contact-tracing (release to developers expected on April 28). Besides, it was affected by specific issues for BLE background detection on iOS devices.

Therefore, the German Government is now working on **CORONA-WARN-APP**, that relies on Apple+Google Exposure Notifications API. 

CORONA-WARN-APP | n/a
----------------|----
Docs & Sources | https://github.com/corona-warn-app/
References | https://www.coronawarn.app/en/

\
It's a decentralized solution based on DP^3T + TCN - used by former proposal **Ito** .

DP^3T | https://github.com/ct-report/DP-3T
------|-----------------------------------

TCN / Ito | https://github.com/ct-report/TCN 
----------|---------------------------------
