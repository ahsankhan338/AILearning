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
   cd AILearning
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
├──lib/
|  ├── main.dart               # Entry point
|  ├── screens/
│      ├── logo_screen.dart    # Splash screen
│      ├── onboarding_screen.dart  # Start and second pages
│      ├── login_screen.dart   # Login screen
│      ├── register_screen.dart # Registration screen
│      ├── interests_screen.dart # Interests selection screen
│      ├── home_screen.dart    # Home page with bottom navigation
│      ├── learn_screen.dart   # Learning options
│      ├── ai_screen.dart      # AI-driven learning path
│      ├── map_screen.dart     # Map view for institutes
│      ├── courses_screen.dart # Courses listing
│      ├── notifications_screen.dart # Notifications
│      ├── settings_screen.dart # Settings
│      ├── account_screen.dart  # User account
│      ├── ebook_screen.dart   # Ebook listings
│      ├── certificate_screen.dart # Certificates
└── README.md
```

---

## Contributing
- **Ahmed Ibrahim Zeb**: Ibrahimzeb65@gmail.com
- **Ahsan Khan**: Ahsan.khaan338@gmail.com
