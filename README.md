




<h1 align="center">
  <br>
  <a href="https://play.google.com/store/apps/details?id=com.banglalink.toffee"><img src="https://raw.githubusercontent.com/BINOD-XD/Toffee-Auto-Update-Playlist/refs/heads/main/toffee_logo.jpeg" alt="🔥 Toffee 🔥" width="200"></a>
  <br>
  🔥 Toffee 🔥
  <br>
</h1>

<h2 align="center">A Script to trigger the GitHub Actions every day to update the Toffee App Channels Link and Cookie </h2>

<p align="center">
  <a href="https://www.python.org/">
    <img src="https://img.shields.io/badge/Made_With-Python_3.12%2B-blue"
         alt="Gitter">
  
  <a href="https://saythanks.io/to/riyadhossainshanto27@gmail.com">
      <img src="https://img.shields.io/badge/Team_RXS-%E2%98%BC-green.svg">
  </a>
  <a href="https://play.google.com/store/apps/details?id=com.banglalink.toffee">
    <img src="https://img.shields.io/badge/App-Toffe_Live-purple">
  </a>
  </a>
  <a href="https://gitter.im/amitmerchant1990/electron-markdownify"><img src="https://img.shields.io/badge/Made%20in-Bangladesh_🇧🇩-green?colorA=%23ff0000&colorB=%23017e40&style=flat-square"></a>
</p>

<h1 align="center">
 <a href="https://play.google.com/store/apps/details?id=com.banglalink.toffee"><img src="https://github.com/Jeshan-akand/Toffee-Channels-Link-Headers/blob/main/images/banner.jpeg"></a>
</h1>

# 📒Introdicton 
* [Toffee](https://play.google.com/store/apps/details?id=com.banglalink.toffee) Live is the number 1 entertainment app in Bangladesh, boasting over 10 million downloads on the Google Play Store.


# 💥Key Features

* All The Channel Links and Cookies Are Updated Every 30 Minutes
* Premium Channels Are Also Working
* Contains Link With Headers (Host, Cookie)
* In JSON Format
* You Can Easily Use This on a Website or in an App for Restreaming TV Channels 

## 🕹️How To Use
**For Developers**
* 👉 **[Auto Updated Channels Json File](https://raw.githubusercontent.com/BINOD-XD/Toffee-Auto-Update-Playlist/main/toffee_channel_data.json)**
* Use Get Request




```python
import requests
#Get updated the Link and Headers 
link="https://raw.githubusercontent.com/BINOD-XD/Toffee-Auto-Update-Playlist/main/toffee_channel_data.json"
request=requests.get(link).json()

name=request["name"]
owner=request["owner"]
channels_amount=request["channels_amount"]
channels_data=request["channels"]
for channel in channels_data:
    link=channel["link"]
    headers=channel["headers"]
    


print("✓ channel link :"+link)
print("✓ channel Headers :",headers)
#Request Toffee Main Api With Headers
request_server=requests.get(link,headers=headers)
#Get the Live m3u3 Link
print("✓ Response From Toffee Server : "+request_server.text)


```

> **Note**
> I'm using Python 3.You can use other Languages.

# 🖥️Optput
> ✓ channel link :https://bldcmprod-cdn.toffeelive.com/cdn/live/comedy_central_hd/playlist.m3u8
✓ channel Headers : {'Host': 'bldcmprod-cdn.toffeelive.com', 'cookie': 'Edge-Cache-Cookie=URLPrefix=aHR0cHM6Ly9ibGRjbXByb2QtY2RuLnRvZmZlZWxpdmUuY29tLw:Expires=1698080619:KeyName=prod_linear:Signature=RY1grOoqltoX1yPO4WMzHCQk2xIp1zGvi03K2bdefb-_QErIqzbuBwytBNV5HiSHSsDslAS2gJsuRFT_MnNJCQ'}

> ✓ Response From Toffee Server :
#EXTM3U
#EXT-X-VERSION:3
#EXT-X-STREAM-INF:PROGRAM-ID=1,BANDWIDTH=1024000,RESOLUTION=1280x720
../slang/comedy_central_hd_576/comedy_central_hd_576.m3u8?bitrate=1000000&channel=comedy_central_hd_576&gp_id=
#EXT-X-STREAM-INF:PROGRAM-ID=1,BANDWIDTH=768000,RESOLUTION=854x480
../slang/comedy_central_hd_320/comedy_central_hd_320.m3u8?bitrate=768000&channel=comedy_central_hd_320&gp_id=
#EXT-X-STREAM-INF:PROGRAM-ID=1,BANDWIDTH=512000,RESOLUTION=640x360
../slang/comedy_central_hd_160/comedy_central_hd_160.m3u8?bitrate=512000&channel=comedy_central_hd_160&gp_id=


> [Program finished]
<h1 align="center">
 <a href="https://raw.githubusercontent.com/BINOD-XD/Toffee-Auto-Update-Playlist/main/toffee_channel_data.json"><img src="https://i.postimg.cc/YCBvB7vC/IMG-20251223-092632.jpg"></a>
</h1>

# 🎬How To Play
**📱Android**
* Use Network Stream Player [Download](https://play.google.com/store/apps/details?id=com.genuine.leone)
* Add This PlayList [Playlist Link](https://raw.githubusercontent.com/BINOD-XD/Toffee-Auto-Update-Playlist/refs/heads/main/toffee_NS_Player.m3u)
* 👆 Short Link :
  ```
  https://shorturl.at/heUyP
  ```
*  Enjoy 😊

**🖥️ Android TV**
* Use OTT Navigator [Download](https://apkpure.com/ott-navigator-iptv/studio.scillarium.ottnavigator/amp)
* Add This PlayList [Playlist Link](https://raw.githubusercontent.com/BINOD-XD/Toffee-Auto-Update-Playlist/refs/heads/main/toffee_OTT_Navigator.m3u)
*  👆 Short Link :
   ```
   https://shorturl.at/czHW8
   ```
*  Enjoy 🫡

<h1 align="center">
 <a href="#"><img src="https://raw.githubusercontent.com/BINOD-XD/Toffee-Auto-Update-Playlist/refs/heads/main/ns_player.jpg"></a>
</h1>
<h1 align="center">
 <a href="#"><img src="https://raw.githubusercontent.com/BINOD-XD/Toffee-Auto-Update-Playlist/refs/heads/main/ott_view.jpg"></a>
</h1>

# 🚬Credits
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=100&color=FF2C10&background=31FF9400&width=400&lines=Made+By+Team+RXS)](https://git.io/typing-svg)



# 📝Note
* The following code is for educational purposes only. It demonstrates how to authenticate and stream IPTV. Do not use it for any illegal or harmful activities. If the code affects the revenue of the IPTV owners, please let me  and I will delete it.
* Please give me proper credit if you share this content. Otherwise, I will take it down.
* The codes of the repo are encrypted to ensure security. Please refrain from trying to run or deploy them 
* Due to geo-restriction, the IPTV content is only available in Bangladesh.




## CONNECT WITH US :

[![Messenger](https://img.shields.io/badge/Messenger-Chat-blue?style=for-the-badge&logo=messenger)](https://m.me/j/AbZltMIVrGlcZi6j/)
<a href="https://github.com/BINOD-XD"><img title="Github" src="https://img.shields.io/badge/BINOD-XD-brightgreen?style=for-the-badge&logo=github"></a>
[![Instagram](https://img.shields.io/badge/FACEBOOK-FOLLOW-red?style=for-the-badge&logo=facebook)](https://facebook.com/reyadbross)
[![Instagram](https://img.shields.io/badge/FACEBOOK-FOLLOW-red?style=for-the-badge&logo=facebook)](https://facebook.com/tahosin.broos)
[![Instagram](https://img.shields.io/badge/WHATSAPP-CHAT-red?style=for-the-badge&logo=whatsapp)](https://wa.me/+8801989861704)
[![Instagram](https://img.shields.io/badge/INSTAGRAM-FOLLOW-red?style=for-the-badge&logo=instagram)](https://www.instagram.com/reyadbros)
[![Instagram](https://img.shields.io/badge/WEBSITE-VISIT-yellow?style=for-the-badge&logo=blogger)](https://BINOD-XD.github.io)
[![Instagram](https://img.shields.io/badge/TELEGRAM-CHANNEL-red?style=for-the-badge&logo=telegram)](https://t.me/shanto27)

#### 💰YOU CAN HELP ME BY DONATING
<p align="center">

  [![BuyMeACoffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-ffdd00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/binodxd) [![PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://paypal.me/binodxd) [![Patreon](https://img.shields.io/badge/Patreon-F96854?style=for-the-badge&logo=patreon&logoColor=white)](https://patreon.com/binodxd) [![Ko-Fi](https://img.shields.io/badge/Ko--fi-F16061?style=for-the-badge&logo=ko-fi&logoColor=white)](https://ko-fi.com/binodxd)</a>
</p>

# Acknowledgements
## Special Thanks <span style='font-size:45px;'>&#128071;</span>
<a href="#"><img title="Reyad X Shipu" src="https://img.shields.io/badge/Reyad X Shipu-black?style=for-the-badge&logo=Reyad X Shipu"></a>
## Thanks For Using This Tool <span style='font-size:45px;'>&#128536;</span> <span style='font-size:45px;'>&#128525;</span>
