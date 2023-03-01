# hse_hw2_chip
[Colab](https://colab.research.google.com/drive/1zJRPWhZv4qmHV8LuMa1raS6g6rvHT97M?usp=sharing)

Для исследования была выбрана клеточная линия DND-41 и гистоновая метка H3K4me3.

## Анализ FastQC

HTML-выдача FastQC находится в папке data

1-ая ChipSeq реплика | 2-ая ChipSeq реплика | Контроль
--- | --- | ---
[ENCFF000APS](https://github.com/Vladm0z/hse_hw2_chip/blob/main/data/ENCFF052DPD_fastqc.html) | [ENCFF000APT](https://github.com/Vladm0z/hse_hw2_chip/blob/main/data/ENCFF612KDN_fastqc.html) | [ENCFF000AOG](https://github.com/Vladm0z/hse_hw2_chip/blob/main/data/ENCFF726ZWD_fastqc.html)

### FastQC

ENCFF000APS

<img width="460" alt="Снимок экрана 2023-03-01 в 16 24 16" src="https://user-images.githubusercontent.com/114533402/222176878-ea2f3a6e-9985-40d4-a4ae-ff3fe888a168.png">
<img width="850" alt="Снимок экрана 2023-03-01 в 16 24 33" src="https://user-images.githubusercontent.com/114533402/222176882-740b20eb-6cbb-4928-9076-6c21437cd72e.png">
<img width="850" alt="Снимок экрана 2023-03-01 в 16 25 01" src="https://user-images.githubusercontent.com/114533402/222176890-474613a8-fe76-4b56-82a7-c6e98bf5bd43.png">
<img width="850" alt="Снимок экрана 2023-03-01 в 16 25 17" src="https://user-images.githubusercontent.com/114533402/222176895-7101d253-9aac-4027-9a6e-f9ea4415e68f.png">
<img width="850" alt="Снимок экрана 2023-03-01 в 16 25 29" src="https://user-images.githubusercontent.com/114533402/222176902-4d56af12-96f0-44d5-bae8-7762c70f78d9.png">
<img width="850" alt="Снимок экрана 2023-03-01 в 16 25 35" src="https://user-images.githubusercontent.com/114533402/222176908-69a6f4d1-ddac-411e-8527-40b810adfba5.png">

ENCFF000APT

<img width="464" alt="Снимок экрана 2023-03-01 в 16 26 33" src="https://user-images.githubusercontent.com/114533402/222177113-525a3615-f95a-41f2-8fd8-292a5c17f43e.png">
<img width="850" alt="Снимок экрана 2023-03-01 в 16 26 11" src="https://user-images.githubusercontent.com/114533402/222177103-36c10daf-4125-414a-8729-576478bbf219.png">
<img width="848" alt="Снимок экрана 2023-03-01 в 16 26 46" src="https://user-images.githubusercontent.com/114533402/222177117-f0ee70ff-1ca8-4b6b-8a13-3623498fec0b.png">
<img width="848" alt="Снимок экрана 2023-03-01 в 16 26 54" src="https://user-images.githubusercontent.com/114533402/222177125-d31297c9-d171-4a1b-8ecf-74e3f60618f6.png">
<img width="848" alt="Снимок экрана 2023-03-01 в 16 27 02" src="https://user-images.githubusercontent.com/114533402/222177127-8933eae1-3d42-4059-a407-17fd791225cc.png">
<img width="848" alt="Снимок экрана 2023-03-01 в 16 27 08" src="https://user-images.githubusercontent.com/114533402/222177132-3ecb8677-73e1-40ed-9c5a-d339d1eb49dd.png">

ENCFF000AOG

<img width="460" alt="Снимок экрана 2023-03-01 в 16 28 18" src="https://user-images.githubusercontent.com/114533402/222177806-467db0fd-e60e-4c4d-8194-d783e486cdaa.png">

<img width="848" alt="Снимок экрана 2023-03-01 в 16 27 34" src="https://user-images.githubusercontent.com/114533402/222177891-6578c3eb-74f8-4732-a72c-116eea7d965d.png">
<img width="848" alt="Снимок экрана 2023-03-01 в 16 27 42" src="https://user-images.githubusercontent.com/114533402/222177904-b1abe032-02e0-4d6a-95db-61aad39c1ccf.png">
<img width="848" alt="Снимок экрана 2023-03-01 в 16 27 48" src="https://user-images.githubusercontent.com/114533402/222177910-64159540-1e2a-47a3-9f42-25eec2a6d152.png">
<img width="848" alt="Снимок экрана 2023-03-01 в 16 27 55" src="https://user-images.githubusercontent.com/114533402/222177915-b63712c0-f8f0-4d07-854a-38ea8bb0073c.png">
<img width="848" alt="Снимок экрана 2023-03-01 в 16 28 03" src="https://user-images.githubusercontent.com/114533402/222177921-ac25a183-7a2c-44c5-9d61-6a46922fa54b.png">

Видно, что качество ридов достаточно хорошее и в подрезании нет необходимости 

## Таблица со статистикой по выравниванию на 19 хромосому
<img width="1052" alt="Снимок экрана 2023-03-01 в 16 38 10" src="https://user-images.githubusercontent.com/114533402/222179626-865cc9ad-ecda-4514-8e60-2ac3fdff05f9.png">

## Диаграммы Эйлера-Венна
### Пересечение пиков 1 реплики и пиков ENCODE
<img width="1211" alt="Снимок экрана 2023-03-01 в 18 09 04" src="https://user-images.githubusercontent.com/114533402/222179983-a0424d1c-8155-4e5e-bd85-d30c7015c839.png">
<img width="1211" alt="Снимок экрана 2023-03-01 в 18 09 31" src="https://user-images.githubusercontent.com/114533402/222180105-cc4f577a-0989-4423-82e9-8dd5f303beea.png">

### Пересечение пиков 2 реплики и пиков ENCODE
<img width="1211" alt="Снимок экрана 2023-03-01 в 18 09 52" src="https://user-images.githubusercontent.com/114533402/222180196-e20bdf31-3bf0-4a39-9f0a-93e1dab02246.png">
<img width="1211" alt="Снимок экрана 2023-03-01 в 18 10 06" src="https://user-images.githubusercontent.com/114533402/222180248-79b34209-56bc-4702-aea9-0d8aebb78f9d.png">

Пересечений довольно мало, это связано с тем, что выравнивание производилось лишь на одну хромосому, а в базе данных ENCODE пики составлены для всех хромосом. Этим же можно объяснить различные значения при пересечении наших пиков с пиками ENCODE и наоборот. 
