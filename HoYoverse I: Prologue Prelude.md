Cryptoverse CTF 2023

HoYoverse I: Prologue Prelude
Challenge: You stumble upon a thread that claims to have uncovered the address of HoYoverse's secret headquarters. As you eagerly click on the link, you're greeted with an image of a bustling city street. Find the address of the exact location where this image was taken.

We're given a image: OSINT.png, and straight away notice some useful text on the side of the building to search on: "111" "Tarification" "robert" bour... 

![image](https://github.com/hacklaugh/Cryptoverse-CTF-2023/assets/126184849/f8e38ffb-af7d-441e-8d8b-f66692ba6c02)


A quick Google search on these words found the building on the first Google page:
111 St Duke, Montréal, QC H3C 2M1 - Cité Multimédia

![image](https://github.com/hacklaugh/Cryptoverse-CTF-2023/assets/126184849/01405b1e-267e-411f-b007-4ebc8f5e16c5)


So, go to Google Maps and enter the address, and find the corner where the photo was taken. Unfortunately the flag failed first time for me, I got the address as "802 Rue Ottawa". When this failed, I wandered round a bit more, then looked again and this time got "802 Ottawa St". This English version was correct.
![image](https://github.com/hacklaugh/Cryptoverse-CTF-2023/assets/126184849/9783476f-7054-4803-a847-4681f0f29710)


Flag: cvctf{802 Ottawa St}
