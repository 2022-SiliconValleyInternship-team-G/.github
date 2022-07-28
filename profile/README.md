# CarryCARI
![Main Page (1)](https://user-images.githubusercontent.com/90602936/181512006-5c9a6387-fba1-4401-b3a2-8389c36b6e77.png)

## Index
- [Lego2me](#lego2me)
  - [1. Prerequisites](#1-prerequisites)
  - [2. Installation Process](#2-installation-process)
  - [3. Getting Started](#3-getting-started)
  - [4. File Manifest](#4-file-manifest)
  - [5. Copyrights / End User Licesnse](#5-copyrights--end-user-licesnse)
  - [6. Contact Information](#6-contact-information)

## 1. Architecture
![image](https://user-images.githubusercontent.com/67141385/181452159-55f30063-524a-43a8-b9e0-55f556147040.png)

## 2. Site URL
- FLAGLY : http://www.learnflagly.com/course/courses/351/
- Webservice URL : 

## 3. Getting Started
- Our website is designed to be responsive, so that even if the size is reduced, the size of the web page is resized to fit the device even if it enters the site from a different size device, so it can be user-friendly.
- If you press the create button above on our site, you will be taken to the page where you can upload your photos.
![KakaoTalk_20220728_211800953](https://user-images.githubusercontent.com/67141385/181505051-59cb696e-9eb0-42b7-8143-a53e6c3a10ed.gif)

- On the page where users upload pictures, you can upload them by drag and drop, or you can select the pictures on your device.
![KakaoTalk_20220728_211801783](https://user-images.githubusercontent.com/67141385/181505095-e98a2cb5-ed18-4b02-a417-a8ce7d764f1d.gif)

- If you click the second "Create" button above on the intro page, you can select the emotion that will be expressed as a caricature after going through the page where you uploaded your picture. After selecting one of the four emotions: smile, cry, surprise, and angry, press the "next" button to go to the waiting page waiting for the result.
![KakaoTalk_20220728_211803888](https://user-images.githubusercontent.com/67141385/181505112-9cbbbe8d-23e6-4744-900f-5648a2de7d12.gif)

- The waiting page is that the user waits while the entered picture is being drawn as a caricature. Cute dinosaur games were added to avoid users' boredom, and if you submit an e-mail by putting a window to register an e-mail, you can also receive the results by e-mail.
![KakaoTalk_20220728_211805665](https://user-images.githubusercontent.com/67141385/181505127-c19f3c82-0d86-46eb-92ba-11f7a4052cdd.gif)


## 4. File Structure
```
📦CarryCARI
 ┣ 📂_media
 ┃ ┣ 📂result_images
 ┃ ┗ 📂user_images
 ┣ 📂assets
 ┃ ┣ 📂user_image_latent
 ┃ ┗ 📂result_image_clip
 ┣ 📂cari
 ┃ ┣ 📂migration
 ┃ ┣ 📜admin.py
 ┃ ┣ 📜apps.py
 ┃ ┣ 📜models.py
 ┃ ┣ 📜serializers.py
 ┃ ┣ 📜tests.py
 ┃ ┣ 📜urls.py
 ┃ ┣ 📜views.py
 ┃ ┗ 📜__init__.py
 ┣ 📂CarryCARI_prj
 ┃ ┣ 📜asgi.py
 ┃ ┣ 📜settings.py
 ┃ ┣ 📜urls.py
 ┃ ┣ 📜wsgi.py
 ┃ ┗ 📜__init__.py
 ┣ 📂ml
 ┃ ┣ 📂StyleCLIP-pytorch
 ┃ ┣ 📂StyleCariGAN
 ┃ ┗ 📜ai.py
 ┣ 📂venv
 ┣ 📜db.sqlite3
 ┣ 📜manage.py
 ┗ 📜README.md
```

## 5. Contact Information

| Name    | 김소민                                     | 김유진                                        | 이진경                                         | 이주현                                  | 임연우                                    |
| ------- | ------------------------------------------ | ------------------------------------------ | ------------------------------------------ | ------------------------------------------ | ------------------------------------------ |
| role    | Backend Developer                          | Backend Developer                            | AI, Backend Developer                                 | Frontend Developer | AI
| Github  | [@thals1214](https://github.com/thals1214) | [@Yujin-nKim](https://github.com/Yujin-nKim) | [@dooli1971039](https://github.com/dooli1971039) | [@JulieOnIsland](https://github.com/JulieOnIsland) |[@Lim-YeonWoo](https://github.com/Lim-YeonWoo) |
