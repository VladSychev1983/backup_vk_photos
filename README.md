#  Программа для резервного копирования фото  с профиля VK в Яндекс Диск.
## Итоговая работа по модулю Netology Python OOP.

#### Алгоритм работы:

1. Подключаемся по API к профили VK , получаем список фотографий профиля аватарки.
2. Создаем директорию для фотографий на локальном диске vk_images
3. Выбираем максимальный размер и загружаем фотографии на локальный диск.
4. Пишем лог загрузки в файл download_vk.json
5. Читаем загруженные файлы в директории
6. Подключаемся в API Yandex disk и загружаем фотографии.
7. Пишем лог загруженных фото в файл upload_yandex.json

Usage: 
python backup_vk.photos.py

PS C:\py\requests> python.exe .\backup_vk_photos.py
Downloading 2_1358161707.jpg Ok!
Downloading 1_1358317602.jpg Ok!
Downloading 4_1358230837.jpg Ok!
Downloading 3_1363595352.jpg Ok!
Downloading 3_1384151834.jpg Ok!
Downloading 2_1421315809.jpg Ok!
Downloading 3_1421316005.jpg Ok!
Downloading 10_1544876969.jpg Ok!
Downloading 4_1552751320.jpg Ok!

Uploading 10_1544876969.jpg Ok!
Uploading 1_1358317602.jpg Ok!
Uploading 2_1358161707.jpg Ok!
Uploading 2_1421315809.jpg Ok!
Uploading 3_1363595352.jpg Ok!
Uploading 3_1384151834.jpg Ok!
Uploading 3_1421316005.jpg Ok!
Uploading 4_1358230837.jpg Ok!
Uploading 4_1552751320.jpg Ok!

