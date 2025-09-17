# StudyMate — AI PDF Study Assistant

StudyMate is an **AI-powered PDF learning system** built for students.  
It allows you to upload PDFs, ask questions, and get summaries instantl
##  Features
- Upload any PDF and get **chapter-wise summaries**  
- Ask **natural language questions** about the content  
- Highlight **important keywords** automatically  
- Simple **frontend** + powerful **backend AI** 
##  Project Structure
- `backend/` → Flask backend for PDF processing & AI model  
- `frontend/` → React/HTML frontend for user interaction  
- `sample/` → Example PDFs and screenshots 
##  How to Run (Development)
1. Clone this repo:
   ```bash
   git clone https://github.com/yamini-0605/hgff.git
   cd hgf
   #install dependencies
   pip install -r requirements.txt
   #start backend
   python backend/app.py
   #start frontend
   cd frontend
   npm install
   npm start
open in browser: https://localhost:3000
