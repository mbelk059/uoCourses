# uoCourses

uoCourses is a course recommendation system designed to help University of Ottawa students discover the most relevant courses tailored to their interests, career goals, or academic preferences. By leveraging the uoapi from uScheduleMe and AI capabilities via Groq, uoCourses delivers personalized recommendations.

Try it out here! https://uocourses.onrender.com/

# Screenshots
<img width="1267" height="778" alt="image" src="https://github.com/user-attachments/assets/b4b42c2b-51c0-4a05-8fe9-628c8ce5923d" />
<img width="813" height="726" alt="image" src="https://github.com/user-attachments/assets/b2485b1e-56d7-4853-942b-371069288578" />

# Features
* **Course Search:** Find courses by describing your career goals, academic interests, or specific subjects
(e.g., "I want to improve at data structures," "How do I become a doctor?" or "I want skills to become a CEO").
* **AI-Powered Responses:** Recommendations are presented using Groq AI.
* **Comprehensive Course Data:** Pulls detailed information on course codes, titles, descriptions, and prerequisites from the uoapi.
* **User-Friendly API:** Simple /chat endpoint to interact with the system.
  
# How It Works
* **Input Query:** Users describe their interests or goals (e.g., "I want to study robotics").
* **Course Matching:** The app searches the json file for relevant courses using keyword matching.
* **AI Recommendations:** The matched courses are formatted and returned as Groq AI-generated responses.

# Technologies Used
* **Backend Framework:** Flask (Python)
* **AI Integration:** Groq
* **Data Source:** uoapi by uScheduleMe https://github.com/uScheduleMe/uoapi
* **Frontend:** React

# Future Steps
* Introduce filtering and sorting options for search results
* Improve the recommendation system for better results
  
# License
This project uses uoapi by uScheduleMe, which is licensed under the GNU Lesser General Public License v3.0 (LGPL-3.0). See the COPYING and COPYING.LESSER files for the exact terms of the license.
