# scrcpy-audio-support
Simple remote your Android device with scrcpy + audio support over vlc (60fps).

Connect on localhost (wifi).
![image](https://user-images.githubusercontent.com/58414694/183927539-2dd38595-0dfb-4672-944c-7ce7ae43aa48.png)

Connect over internet using ngrok.com
![image](https://user-images.githubusercontent.com/58414694/183928638-e43d3628-87a8-4596-85ba-a91dbb234d87.png)

TO-DO:

- [x] Release this.
- [ ] Make GUI.

HOW-TO-USE:

- Download it in releases, then run exe file to install. It will extract all files in current directory and create desktop shortcut. You need to follow these instructions showing on terminal in first time setup, after done you can simply directly connect to your phone over wifi without any confirmation (must the same wifi network, if you want remote over internet, forward port on your router or using ngrok.com run in termux on android).  
- After connected, your phone will mute audio and turn off screen, audio and video only playing from computer. If you disconnect, your device will lock immediately and unmute sound.
