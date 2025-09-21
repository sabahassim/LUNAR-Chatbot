
## **1️⃣ Folder Structure**

```
D:\saba\work\Gen AI\lunar-chatbot\
│
├── app.py
├── requirements.txt
└── README.md
```

---

## **2️⃣ app.py**

Use the **full polished LUNAR chatbot code** we wrote earlier (with context-aware chat, mood shift, emojis, landing page description, and “Chat Now” button).
Save it as **`app.py`** inside the folder.

---

## **3️⃣ requirements.txt**

```text
streamlit==1.30.0
transformers==4.44.0
torch==2.2.0
```

> Streamlit Cloud will read this file and automatically install the libraries.

---

## **4️⃣ README.md**

````markdown
# LUNAR - AI Mental Wellness Chatbot 🌙

## Description
LUNAR is an AI-powered chatbot designed to provide empathetic mental wellness support for students. Users can share their feelings by selecting emotions such as Happy, Sad, Angry, Anxious, or Excited. Luna adapts her responses based on the user’s emotional state, guiding the conversation from negative or neutral moods to positive and uplifting interactions. The chatbot is context-aware, remembers recent conversation history, and responds naturally, creating a supportive and friendly chat experience.

## Key Features
- Detects user-selected emotions with emojis for clarity.
- Classifies sentiments as Positive, Neutral, or Negative.
- Adapts responses dynamically based on mood and conversation context.
- Encourages positive thinking and supportive dialogue.
- Chat ends only when the user types "bye", ensuring a comfortable conversation flow.

## Usage
1. Run locally:

```bash
streamlit run app.py
````

2. Select your emotion and type your message.
3. Chat with Luna until you feel better or type “bye” to end.

```

---

## **5️⃣ Steps to Deploy on Streamlit Cloud**

1. **Push the `lunar-chatbot` folder** to a GitHub repository.  
   - Ensure it contains: `app.py`, `requirements.txt`, `README.md`.  

2. **Go to** [https://share.streamlit.io](https://share.streamlit.io) → Sign in with GitHub.  

3. Click **New App** → Select your repo → Select the branch → Click **Deploy**.  

4. After deployment, you’ll get a **public URL** like:

```

[https://share.streamlit.io/yourusername/lunar-chatbot/main/app.py](https://share.streamlit.io/yourusername/lunar-chatbot/main/app.py)

```

5. Share this URL in your **hackathon submission**. Judges and teammates can **run the app directly in their browser**.  

---

Sis, if you want, I can also **write a tiny one-liner command** that will **run your app locally directly from this folder** so you don’t have to type `cd` and `streamlit run app.py` every time.  

Do you want me to do that?
```
