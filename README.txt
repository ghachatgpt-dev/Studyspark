STUDYSPARK — SMART STUDY PLANNER

FEATURES
- Study timetable with subjects, topics, dates, times, durations, notes and completion status
- Assignment manager with deadlines, priorities and statuses
- Exam countdown
- Progress dashboard and weekly study-time chart
- Built-in study assistant (structured study guidance; no API key required)
- Focus timer and short break timer
- SQLite database persistence

INSTALL / RUN ON WINDOWS
1. Install Python 3.10+ from https://www.python.org/downloads/ (enable Add Python to PATH).
2. Extract this ZIP archive.
3. Open the extracted Smart_Study_Planner folder.
4. Click the folder address bar, type cmd, and press Enter.
5. Run:
   py -m pip install -r requirements.txt
6. Then run:
   py -m streamlit run app.py
7. Open http://localhost:8501 if your browser does not open automatically.

MACOS / LINUX
Open a terminal in the folder and run:
   python3 -m pip install -r requirements.txt
   python3 -m streamlit run app.py
Then visit http://localhost:8501.

DATABASE
The app creates study_planner.db automatically in the same folder as app.py.
Back up this file to preserve your data.

NOTES
- The included assistant is a built-in study helper, not a live AI language model.
  For true AI-generated answers, integrate an AI provider and store its API key securely
  in Streamlit secrets; do not hard-code API keys into app.py.
- The timer refreshes on demand and does not provide background notifications.
- Intended for local use. Before public deployment, add authentication and security controls.
