# uoCourses

uoCourses is a course recommendation system designed to help University of Ottawa students discover the most relevant courses tailored to their interests, career goals, or academic preferences.

Try it out here! https://uocourses.onrender.com/

# Screenshots
<img width="1896" height="970" alt="image" src="https://github.com/user-attachments/assets/8f37b202-9351-4de1-8cf8-142301d6edfc" />

# ✨ Features
* **Course Search:** Find courses by describing your career goals, academic interests, or specific subjects
(e.g., "I want to improve at data structures," "How do I become a doctor?" or "I want skills to become a CEO").
* **AI-Powered Responses:** Recommendations are presented using Gemini AI.
* **Comprehensive Course Data:** Pulls detailed information on course codes, titles, descriptions, and prerequisites from the uoapi.
* **User-Friendly API:** Simple /chat endpoint to interact with the system.
  
# 🚀 How It Works
1. **Input Query:** Users describe their interests or goals (e.g., "_I want to study robotics_").
2.  **Smart Filtering:** The system uses a score-based algorithm to match courses:
    * Assigns higher scores to subject code matches
    * Prioritizes keywords in course titles over descriptions
    * Considers course level preferences (beginner, advanced, graduate)
3. **AI Enhancement:** Top-ranked courses are sent to Gemini AI for natural language recommendations
4. **Response Validation:** System verifies AI output contains valid course codes and falls back to simple listing if needed

# 🛠️ Technologies Used
* **Backend Framework:** Flask (Python)
* **AI Integration:** Google Gemini 2.0 Flash API
* **Data Source:** uoapi by uScheduleMe https://github.com/uScheduleMe/uoapi
* **Frontend:** React
* **Caching:** Custom LRU cache implementation for optimal performance
* **Cross-Origin Support:** Flask-CORS for seamless frontend integration

# 🏗️ Architecture Highlights
* **Preloaded Course Data:** All course information loaded into memory at startup for zero-latency access
* **Score-Based Ranking:** Sophisticated filtering system that ranks courses by relevance before AI processing
* **Temperature-Optimized AI:** Lower temperature (0.3) for consistent and accurate recommendations
* **Health Monitoring:** /health endpoint for system status checks
  
# License
This project uses uoapi by uScheduleMe, which is licensed under the GNU Lesser General Public License v3.0 (LGPL-3.0). See the COPYING and COPYING.LESSER files for the exact terms of the license.

Made with ❤️ for uOttawa students
