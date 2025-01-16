# uoCourses

uoCourses is a course recommendation system designed to help University of Ottawa students find the most relevant courses tailored to their interests, career goals, or academic preferences. By leveraging the uoapi from uScheduleMe and advanced AI capabilities, uoCourses delivers personalized recommendations in a friendly, conversational format.

# Screenshots
![image](https://github.com/user-attachments/assets/4d54831f-ae92-4189-856b-9ade7a99bfaa)

# Features
* **Course Search:** Search for courses by inputting career goals, academic interests, or specific subjects (e.g., "i wanna get better at data structures," "how do i become a doctor," or "i want the skills to become a ceo").
* **AI-Powered Responses:** The app uses Google Generative AI to present recommendations in a conversational and friendly tone.
* **Comprehensive Course Data:** Pulls from the uoapi to access detailed information on course codes, titles, descriptions, and prerequisites. https://github.com/uScheduleMe/uoapi
* **User-Friendly API:** Simple /chat endpoint to interact with the system.
  
# How It Works
* **Input Query:** Users describe their interests or goals (e.g., "I want to study robotics").
* **Course Matching:** The app searches its database for relevant courses using keyword matching.
* **AI Recommendations:** The matched courses are formatted and presented via AI-generated, conversational responses.

# Technologies Used
* **Backend Framework:** Flask (Python)
* **AI Integration:** Google Generative AI
* **Data Source:** uoapi by uScheduleMe https://github.com/uScheduleMe/uoapi
* **Frontend:** React

# Future Steps
* Introduce filtering and sorting options for search results
* Improve the recommendation system for better results
  
