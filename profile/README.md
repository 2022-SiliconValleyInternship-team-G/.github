# CarryCARI
![Cover (6)](https://user-images.githubusercontent.com/70802352/187036154-00cead3a-48fa-4f29-ba7a-0ccbb672829f.png)

## Index
- [CarryCARI](#CarryCARI)
  - [1. Architecture](#1-Architecture)
  - [2. Site URL](#2-Site-URL)
  - [3. Getting Started](#3-getting-started)
  - [4. File Structure](#4-File-Structure)
  - [5. Contact Information](#5-Contact-Information)

## 1. Architecture
![image](https://user-images.githubusercontent.com/67141385/181452159-55f30063-524a-43a8-b9e0-55f556147040.png)

## 2. Site URL
- FLAGLY : http://www.learnflagly.com/course/courses/351/
- Webservice URL(Frontend) : https://carrycari.netlify.app
- Webservice URL(Backend) : http://147.47.125.118:6006

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

- On the results page, you can check the caricatures of 8 styles with the photos of the before image you submitted earlier.

![Result Page](https://user-images.githubusercontent.com/70802352/181600528-ae3826c7-9be6-49aa-9d28-8225e57deb8e.png)



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

| Name    | 김소민                                     | 김유진                                        | 임연우                                         | 이주현                                  | 이진경                                    |
| ------- | ------------------------------------------ | ------------------------------------------ | ------------------------------------------ | ------------------------------------------ | ------------------------------------------ |
| role    | Backend Developer                          | Backend Developer                            | AI, Backend Developer                                 | AI | Team Leader, Frontend Developer
| Github  | [@thals1214](https://github.com/thals1214) | [@Yujin-nKim](https://github.com/Yujin-nKim) | [@Lim-YeonWoo](https://github.com/Lim-YeonWoo) | [@JulieOnIsland](https://github.com/JulieOnIsland) | [@dooli1971039](https://github.com/dooli1971039) | 
