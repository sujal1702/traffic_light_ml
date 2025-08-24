🚦 Traffic Light Color Detection (Django + ML)

This project is a Traffic Light Color Detection System built using Django, OpenCV, and Scikit-learn.
It classifies an uploaded traffic signal image as Red, Yellow, or Green, and blocks irrelevant images (like humans, cars, etc.).

✨ Features

🖼 Upload traffic signal image via web app.

🎨 Detects Red, Yellow, or Green.

🚫 Ignores irrelevant images.

⚡ Machine Learning model trained using image dataset.

🎯 Clean UI with Bootstrap templates.

🗂 Project Structure
traffic_light_ml/
│── dataset/                # Training images (Red/Yellow/Green)
│── ml_model/               # Saved model + label encoder
│   ├── traffic_model.pkl
│   ├── label_encoder.pkl
│── traffic_project/        # Django project folder
│   ├── traffic_app/        # Django app
│   │   ├── templates/
│   │   │   └── home.html
│   │   ├── views.py
│   │   ├── models.py
│   │   ├── urls.py
│   └── settings.py
│── manage.py
│── README.md
