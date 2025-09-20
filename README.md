# Research_Paper_Finder
A web-based application that helps users search for academic research papers with a focus on contributions from Sri Krishna Arts and Science College (SKASC). The system uses Gemini AI, Exa API, Arxiv, and Wikipedia to intelligently filter and display relevant results.

# Features

✅ AI-Powered Query Optimization using Google Gemini ,Multi-source search (Exa → Arxiv → Wikipedia fallback) ,Affiliation Filtering – highlights papers from SKASC ,Interactive UI with animated cards and loaders,Detailed results including title, authors, excerpts, and links.

# 🏗️ System Architecture

User enters query in the frontend (HTML/CSS/JS)
Flask backend optimizes query using Gemini
Searches run in order:
Exa API (primary source)
Arxiv (fallback)
Wikipedia + Gemini summarization (final fallback)
Results are filtered for SKASC affiliation
Frontend displays results as animated cards

# 📂 Project Structure
Research-Paper-Finder/
│── app.py              # Flask backend  
│── index.html          # Frontend (templates)  
│── Style.css           # Custom styles  
│── requirements.txt    # Dependencies  
│── .env                # API keys (keep private, don’t upload)  
│── static/             # CSS/JS/Images  
│── templates/          # HTML files  


# 🖥️ Usage

Enter a research query in the search bar.The system optimizes the query and fetches results.Results are displayed as cards with title, authors, excerpts, and links.If SKASC papers are found → they are marked with high confidence.If none are found → fallback results from Arxiv/Wikipedia are shown.

# 📦 Dependencies

Flask , python-dotenv ,langchain, langchain-community ,langchain-google-genai ,langchain-exa ,exa-py,google-generativeai ,requests, tqdm

# 🤝 Team Members

Monisha Ravichandran (23BCT135)– Project Lead & System Architect ;
Harini M (23BCT117) – Frontend Developer ; 
Varadalakshmi S (23BCT161) – Backend API Integration ; 
Darshana J (23BCT107) – Gemini AI Specialist ; 
Kowsalya V (23BCT128) – Affiliation Filtering Module ; 
Sanjay K (23BCT150)– Tester & Deployment Engineer 
