# MuleSoft Platform APIs

Every time you login into the MuleSoft Anypoint Platform, you are implicitly calling a set of APIs that are invoked by the UI, the PlatformAPI! and you can make all these UI actions through HTTP requests directly as well, this is specially useful When automating your SDLC as you may need something more customizable than Anypoint CLI or the Mule Maven Plugin.

These assets act as base to start working upon with good practices (Postman concatenation of requests, testing scripts, etc.) 

If you are new to Platform APIs please go through this [post!](https://blogs.mulesoft.com/dev/howto/get-started-with-platform-apis-and-postman-automation/)

## Prerequisites
Before we start working with platform APIs, you need these three pieces of data: a session token, the organization id and the environment id; as shown in the below image.
![Image of Process](https://raw.githubusercontent.com/angelalberici/mulesoft-platform-apis/master/img/PlatfromAPIBasics.png)

<p>Make sure you have <a href="https://www.postman.com/)" target="_blank" rel="noreferrer noopener" aria-label=" (opens in a new tab)">Postman</a> installed, that you do know how to <a href="https://learning.postman.com/docs/postman/collection-runs/working-with-data-files/#importing-sample-collection-files" target="_blank" rel="noreferrer noopener" aria-label=" (opens in a new tab)">import the Postman Collection and the Environment</a> and then you can finally download the postman assets from this repository. Import both files and make sure to add both anypoint-username and anypoint-password to your Postman Environment, the fields highlighted below.</p>

![Image of Postman Environment](https://lh3.googleusercontent.com/poaVvuZP-1GCEsjRsnf3tBJ99wIStmKEKzoXcVHDmUAxX3OtmgdKXIXYUm2NllTNjwat1Mwsk4UY7Tqovk8MisFTUKyuzQhlVKAUvn8aR4_Sjt3Qk2nC7dvpabw50kxfvOC6rlnX)

## Start using

That's about it. Download import into your Postman, add your credentials to the Environment. Ideas? Comments around the Anypoint Platform APIs documentation? Please leave them in the [post!](https://blogs.mulesoft.com/dev/howto/get-started-with-platform-apis-and-postman-automation/)

## Next steps 
-  Put what you learn into practice with [Learn How to use MuleSoft Platform APIs to manage API Specifications](https://developer.mulesoft.com/tutorials-and-howtos/quick-start/how-to-use-mulesoft-platform-apis-to-manage-api-specifications)
-  For more requests, make sure you check out: [MuleSoft Catalyst](https://catalyst.mulesoft.com/display/OBD/Postman+Collection+for+Anypoint+API+Endpoints)
-  Or to visit the [Platform API Portal](https://anypoint.mulesoft.com/exchange/portals/anypoint-platform/) 


