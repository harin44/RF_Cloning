# RF_Cloning
[Cloning my key and opening my garage gate with my 10 USD DIY CC1101 tool and Universal Radio Hacker](https://www.youtube.com/watch?v=mdkEK_wmWJA&t=229s)

Devices Used for this Signal indetification and Decoding

- [Digital RTL2832U & R828D SDR USB2.0 TV Stick Tuner 25 MHz To 1760 MHz](https://www.aliexpress.com/item/1005005278623123.html?spm=a2g0o.detail.pcDetailTopMoreOtherSeller.2.7d4fatHAatHAX2&gps-id=pcDetailTopMoreOtherSeller&scm=1007.40196.404796.0&scm_id=1007.40196.404796.0&scm-url=1007.40196.404796.0&pvid=1451f6c4-3f74-4f14-9901-895b3c8d1c36&_t=gps-id:pcDetailTopMoreOtherSeller,scm-url:1007.40196.404796.0,pvid:1451f6c4-3f74-4f14-9901-895b3c8d1c36,tpp_buckets:668%232846%238113%231998&pdp_npi=4%40dis%21LKR%215482.87%213641.70%21%21%2118.88%2112.54%21%402101584917334743887061635e1f88%2112000032464132174%21rec%21LK%21%21ABX&utparam-url=scene%3ApcDetailTopMoreOtherSeller%7Cquery_from%3A)
- [Raspberry Pi 3 Model B+ Board 3B Plus BCM2837B0 64-bit 1.4GHz with 1GB LPDDR2 SDARM Support WiFi and Bluetooth](https://www.aliexpress.com/item/1005005675808386.html?spm=a2g0o.productlist.main.3.5c1e3594NbxGDo&algo_pvid=686f52cd-6b83-45e8-8c97-7e2ddd0583d8&algo_exp_id=686f52cd-6b83-45e8-8c97-7e2ddd0583d8-1&pdp_npi=4%40dis%21LKR%2117205.71%2113526.45%21%21%2159.25%2146.58%21%40214100f417337247909022293e68e1%2112000033978452034%21sea%21LK%210%21ABX&curPageLogUid=y9QLp0ndn3kg&utparam-url=scene%3Asearch%7Cquery_from%3A)

Essential Softwares
-  [Universal Radio Hacker](https://github.com/jopohl/urh)
  ->  Universal Radio Hacker (URH) is a tool for analyzing unknown wireless protocols.
-  [spektrum](https://github.com/pavels/spektrum)
    -> Spektrum Programmer allows you to configure settings, load model presets, and update the software on your receiver or transmitter.

Identify the range of the RF signal 

-  turn on  spektrum, from this s/w we can identify the frequency range in which the rf wave is in
-  to get the wave frequency connect the  RTL2832U USB SDR Dongle, and select the  device
-  normally the rf remotes that we use mainly comes in the range of 300 - 400MHz therefore we can select a range of  300-400MHz to  idetify  the frequecy of the remote while operating it.
-  identify the spike and  decrease the range for more  easier identification.

Decoding the RF Signal

- [URH user Guide](https://www.oldergeeks.com/downloads/files/userguide.pdf)

Working with rolling codes
-  [Controlling roller shutters using a remote with rolling codes](https://community.home-assistant.io/t/controlling-roller-shutters-using-a-remote-with-rolling-codes/453336)
-  [ESPSomfy-RTS](https://github.com/rstrouse/ESPSomfy-RTS)

 



