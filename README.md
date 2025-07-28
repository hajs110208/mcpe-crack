# English | [한국어](README_KO.md)

# mcpe-crack
Google Play License Check Bypasser for Minecraft for Android

# Before doing this
This repository is for people who bought the game legally. Please consider buying Minecraft instead of cracking.

# How to?
Grab some tools. MT Manager and Apktool M are used in the guide.

1. Open MT Manager and click the apk and click "VIEW".

2. Click on any dex file and click "Dex Editor plus".

3. Go to com/mojang/minecraftpe/store/googleplay and tap GooglePlayStore.

4. Search for string that includes "hasverifiedlicense".

5. replace the line which starts with sget-boolean into const/4 v0, 0x1.

6. Save the file and update the file with "AUTO SIGN" Checked.

7. If the apk reports malicious app during installing, you will have to use Apktool M to create your own key and sign it.

8. Open Apktool M and go to Settings > Sign > Create a Key File. Once you're done, go back to the main screen, tap on the apk, click Sign. Be sure to select your custom signature!

9. Once done, install the apk.

# Congrats!
Now you successfully cracked the game.
If that is way too complicated, just replace the smali file. You can find it in the repository.

