# AI Learning Mobile Application

## Project Overview
The **AI Learning** mobile application leverages Artificial Intelligence (AI) to provide personalized and adaptive learning experiences. This platform dynamically generates weekly learning roadmaps, aggregates relevant online courses, and evaluates user progress through AI-generated quizzes. Additionally, it integrates location-based recommendations for nearby educational institutions, bridging the gap between online and offline learning.

---

## Features
- **Personalized Learning Paths**: AI-generated weekly roadmaps tailored to user preferences and progress.
- **Adaptive Assessments**: Dynamic quizzes with real-time feedback and performance-based adjustments.
- **Content Aggregation**: Curated online courses through web scraping and AI-based recommendations.
- **Summarization**: Automatic summarization of lengthy course materials.
- **Location-Based Services**: Recommendations for nearby educational institutions using Google Maps API.

---

## Technologies Used
- **Frontend**: Flutter
- **Backend**: Flask/Django
- **AI Model**: TinyLlama (Hugging Face Transformers)
- **Database**: PostgreSQL
- **Web Scraping**: Scrapy and BeautifulSoup
- **Location Services**: Google Maps API

---

## Installation and Setup

### Prerequisites
- **Python 3.8+**
- **Node.js**
- **Flutter SDK**
- **PostgreSQL**
- GPU-enabled hardware (for AI model hosting and fine-tuning).

### Steps
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/ahsankhan338/AILearning.git
   cd ai-learning
   ```

2. **Set Up Frontend**:
   - Navigate to the `frontend` directory.
   - Install Flutter dependencies:
     ```bash
     flutter pub get
     ```
   - Run the Flutter app:
     ```bash
     flutter run
     ```
---

## Project Structure
```
├── backend
│   ├── manage.py          # Backend entry point
│   ├── requirements.txt   # Python dependencies
│   ├── app
│   │   ├── models.py      # Database models
│   │   ├── views.py       # API endpoints
│   │   └── utils.py       # Helper functions
├── frontend
│   ├── pubspec.yaml       # Flutter dependencies
│   ├── lib
│   │   ├── main.dart      # Flutter app entry point
│   │   ├── screens        # UI screens
│   │   └── widgets        # Reusable widgets
├── docs
│   └── model_integration.md  # Model integration guide
└── README.md
```

---

## Contributing
- **Ahmed Ibrahim Zeb**: Ibrahimzeb65@gmail.com
- **Ahsan Khan**: Ahsan.khaan338@gmail.com
