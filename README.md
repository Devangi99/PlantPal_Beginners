# PlantPal_"For Beginners"
A cross-platform mobile application developed as part of a final year research project, aimed at assisting beginners in Sri Lankan floriculture with **cut flower crop selection** and **Philodendron variety identification** using affordable technologies.

## Research Problem

Cut flowers and ornemantal plants are key products in Sri Lanka's floriculture industry, but beginner growers often struggle with:
- Selecting suitable crops based on **weather, resources, and expected yield**
- Identifying different **Philodendron varieties** used in tissue culture and foliage décor

❌ Poor decisions result in time, money, and resource losses  
❌ Lack of expert guidance for new growers  
✅ This app bridges this gap with **accessible technology**

## Overall Architecture
![Architecture](assets/img10.jpg)

### 1️⃣ Cutflower Advisor  
- Machine learning–based model  
- Crop recommendation based on weather (via OpenWeather API)  
- Factors considered: temperature, humidity, infrastructure
![Cutflower advisor](assets/img63.jpg)

### 2️⃣ Philovariety Finder  
- Image classification model to identify Philodendron varieties  
- Built using CNNs and trained on a custom dataset
- Out-of-scope image detection using DL
![Philo finder](assets/img115.jpg)

## Project Snapshots
![screen1](assets/pic1.png)
<br>
![screen2](assets/cut.png)
<br>
![screen3](assets/philo.png)
<br>
![screen4](assets/val.png)


## Tech Stack

- **React Native** – Cross-platform mobile development  
- **Python + Flask** – Backend + model hosting  
- **Python, Scikit-learn, TensorFlow, Keras** – ML & DL components  
- **OpenWeather API** – Weather data integration  


## 🔐 Access Note

Some implementation components (ML models, datasets, and backend logic) remain unpublished and are not included in this repository. For inquiries, please contact:

📧 **[dgamage102@gmail.com]**

