# News Summarization and Text-to-Speech Application

## 📌 Project Overview
This project extracts key details from news articles related to a given company, performs sentiment analysis on the articles, and converts the summarized content into Hindi speech using a Text-to-Speech (TTS) model. The application is built with **BeautifulSoup, Pandas, TensorFlow (for sentiment analysis), and Streamlit/Gradio (for the UI)**. It is deployed on **Hugging Face Spaces**.

## 🚀 Features
- **Scrapes news articles** using BeautifulSoup from Google News.
- **Summarizes news content** for quick insights.
- **Performs sentiment analysis** (positive, negative, neutral) using a trained model.
- **Converts text to speech (TTS)** in Hindi.
- **Provides an interactive UI** using Streamlit or Gradio.
- **Deploys easily on Hugging Face Spaces.**

## 📂 Project Structure
```
📦 News-Summarization-and-Text-to-Speech-Application
├── --src
│   ├── scraper.py  # Scrapes news from Google News
│   ├── sentiment.py  # Performs sentiment analysis
│   ├── tts.py  # Converts text to Hindi speech
│   ├── app.py  # Streamlit/Gradio UI
├── requirements.txt  # Dependencies
├── README.md  # Project documentation
├── news_data.csv  # Scraped news data (after running scraper)
```

## 🛠 Installation & Setup
### 1️⃣ Clone the Repository
```bash
git clone https://huggingface.co/spaces/your-username/news-summarization
cd news-summarization
```

### 2️⃣ Create a Virtual Environment (Optional but Recommended)
```bash
python -m venv venv
source venv/bin/activate  # For Mac/Linux
venv\Scripts\activate  # For Windows
```

### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 4️⃣ Run the Application Locally
For **Streamlit** UI:
```bash
streamlit run app.py
```
For **Gradio** UI:
```bash
python app.py
```

### 5️⃣ Running Individual Components (Optional)
- **Scraper:**
  ```bash
  python scraper.py
  ```
- **Sentiment Analysis:**
  ```bash
  python sentiment.py
  ```
- **Text-to-Speech:**
  ```bash
  python tts.py
  ```

## 🚀 Deployment on Hugging Face Spaces
1. Push the project to **Hugging Face Spaces**
   ```bash
   git add .
   git commit -m "Deploying on Hugging Face"
   git push origin main
   ```
2. Open Hugging Face and **launch the app**.

## 📝 Example Usage
1. Run the app.
2. Enter a **company name** (e.g., "Tesla").
3. The app will **scrape** news articles, **analyze sentiment**, and **generate Hindi speech**.
4. Listen to the audio summary directly in the app.

## 🏆 Future Improvements
- Improve news summarization using **LLMs**.
- Add multi-language support for **TTS**.
- Deploy on **AWS/GCP for scalability**.

## 🤝 Contributing
Feel free to fork the repo and submit PRs for improvements!

## 📜 License
This project is licensed under the **MIT License**.

---

### 🌟 If you find this project useful, don't forget to ⭐ the repo!

