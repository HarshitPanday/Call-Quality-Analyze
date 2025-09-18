# Call-Quality-Analyze
Sales Call Quality Analyzer Project


# Call Quality Analyzer 

## Project Overview
**Call Quality Analyzer** ek Python-based Voice AI project hai jo **sales call recordings** ka automated analysis karta hai.  
Ye tool sales teams ko call performance measure karne, customer engagement samajhne, aur actionable insights provide karne me help karta hai.

**Key Goals for Interview Demonstration:**
- Measure **talk-time ratio** (Sales Rep vs Customer)  
- Count **number of questions asked**  
- Detect **longest monologue**  
- Analyze **call sentiment** (positive/negative/neutral)  
- Provide **actionable insights**  
- Bonus: Identify **Sales Rep vs Customer**

---

##  Features

| Feature | Why it Matters |
|---------|----------------|
| Talk-time Ratio | Shows balance of conversation; identifies dominant speaker |
| Question Detection | Measures engagement and inquiry level |
| Longest Monologue | Helps identify areas where speaker dominates or customer is disengaged |
| Sentiment Analysis | Measures positivity/negativity of the call |
| Actionable Insight | Provides recommendations to improve future calls |
| Speaker Identification | Distinguishes Sales Rep from Customer for better analysis |

---

## 🛠 How It Works

1. **Audio Download & Preprocessing**
   - Audio is downloaded from YouTube  
   - Converted to `.wav` format and noise reduced  

2. **Speaker Diarization**
   - Identifies who spoke when using `pyannote.audio`  
   - Helps calculate talk-time and monologues  

3. **Speech-to-Text Transcription**
   - Converts audio to text using OpenAI `Whisper`  

4. **Analysis**
   - **Talk-time Ratio**: % of call duration per speaker  
   - **Question Detection**: Counts questions asked  
   - **Longest Monologue**: Finds longest uninterrupted speech  
   - **Sentiment Analysis**: Determines overall mood using `TextBlob`  
   - **Actionable Insight**: Generates practical suggestions  


