
# Drug trafficking detection
A multi-platform drug abuse detection system using social media scraping and machine learning comparison.

## 📖 Table of Contents

- [About The Project](#about-the-project)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the App](#running-the-app)
- [Usage Workflow](#usage-workflow)
- [Project Structure](#project-structure)
- [License](#license)
- [Contact](#contact)

---

## 🧠 About The Project

**Trace Guard** is an AI-powered social media analysis system designed to identify potential drug-related behavior across **Instagram, Twitter, and Telegram**. Users access a central Flask-based web interface to choose the platform, input relevant account information, and generate a detailed PDF report containing a suspicious score and keywords. Users can also report suspicious accounts directly to authorities.

---

## ✨ Features

- 🧠 NLP-based content comparison with a custom dataset
- 📦 Scraping support for Instagram, Twitter, and Telegram
- 📊 Suspicious activity scoring
- 📝 Automated PDF report generation
- 🌐 Flask-based user interface
- 🛡️ Option to report suspicious accounts to police

---

## ⚙️ Tech Stack

**Languages & Frameworks:**  
- Python  
- Flask  

**Libraries:**  
- `tweepy` – Twitter API scraping  
- `instaloader` – Instagram scraping  
- `telethon` – Telegram scraping  
- `transformers`, `scikit-learn` – ML/NLP model integration  
- `pandas`, `wordcloud`, `fpdf2` – Data analysis & visualization  
- `dotenv`, `nest-asyncio` – Environment & async handling  

---

## 🚀 Getting Started

### ✅ Prerequisites

Make sure you have Python 3.7 or higher installed.

### 📦 Installation

1. **Clone the repository**  
   ```bash
   git clone https://github.com/Purni-r/trace-guard.git
   cd trace-guard
   ```

2. **Create and activate a virtual environment**  
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows use: venv\Scripts\activate
   ```

3. **Install dependencies**  
   ```bash
   pip install -r requirements.txt
   ```

---

### ▶️ Running the App

```bash
python app.py
```

Then open your browser and visit: [http://localhost:5000](http://localhost:5000)

---

## 🧪 Usage Workflow

1. User visits the website and selects a platform: **Instagram**, **Twitter**, or **Telegram**.  
2. Depending on the platform:
   - **Instagram:** User enters the Instagram username.  
   - **Twitter:** User enters the Twitter username.  
   - **Telegram:** User logs in with phone number and OTP.  
3. The system scrapes posts or messages using the respective APIs.  
4. Content is compared with a custom drug-related dataset using NLP models.  
5. A suspicious activity score is calculated.  
6. A detailed PDF report is generated including:
   - Account summary  
   - Suspicious keywords  
   - Activity stats  
   - Suspicious score  
7. Users can download the PDF report or report the suspicious account to police via an embedded button.

---

## 📂 Project Structure
Trace-Guard
| File / Folder               | Description                                     |
| --------------------------- | ----------------------------------------------- |
| `app.py`                    | Main Flask server                               |
| `scraper.py`                | Platform-specific scraping and keyword matching |
| `report.py`                 | PDF report generation                           |
| `requirements.txt`          | Python dependencies                             |
| `.env`                      | API keys and environment variables              |
| `templates/index.html`      | Frontend HTML                                   |
| `static/styles.css`         | Stylesheet                                      |
| `dataset/drug_keywords.csv` | Reference drug-related keywords dataset         |


---

## 🪪 License

Distributed under the MIT License. See [LICENSE](LICENSE) for details.

---

## 📬 Contact

**Purnima R**  
📧 purnimaramesh03@gmail.com  
📱 +91-9844530826  

**Alok G Bongale**  
📧 rr6786411@gmail.com  
📱 +91-8971019213 

