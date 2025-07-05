Day Planner
Welcome to Day Planner, a interactive web-based planner that helps you organize your day with a magical twist! This project features a responsive interface, a fairy helper powered by AI, and real-time weather integration to provide tailored advice based on your schedule and local conditions.
Overview

Purpose: Manage your daily tasks with a visually appealing design and get personalized suggestions from a fairy helper.
Features:
Add and track tasks with timestamps.
Save data locally using localStorage.
Interactive fairy chatbox with AI-driven responses.
Real-time temperature integration for weather-aware advice.
Typing indicator for a smoother user experience.
Responsive design for desktop and mobile devices.



Prerequisites

A modern web browser (e.g., Chrome, Firefox, Safari).
Internet connection for API calls (OpenWeatherMap and Gemini API).
Optional: Git for cloning the repository.

Setup

Clone the Repository:
git clone https://github.com/your-username/day-planner.git
cd day-planner


API Keys:

OpenWeatherMap API Key: Sign up at OpenWeatherMap to get a free API key. Replace 'YOUR_OPENWEATHERMAP_API_KEY' in the code with your key.
Gemini API Key: Provided in the code (AIzaSyAkUSNfKk836gf35tYump4dUxVGI_KHTxk). Ensure it remains secure and regenerate if exposed.
Update the city variable in the getTemperature function to your location (e.g., 'Mumbai').


Run the Project:

Open index.html in a web browser. No server is required as it runs client-side.



Usage

Add Tasks:

Enter tasks in the schedule inputs (e.g., "Breakfast" at 8:00).
Tasks are saved locally and marked as completed when edited.


Interact with the Fairy Helper:

Click the fairy button (bottom right) to open the chatbox.
Type a message (e.g., "What should I do next?") and click "Send".
The fairy will analyze your schedule and weather, providing tailored advice.


Manage Additional Details:

Use the side panel to add dates, reminders, goals, priorities, and notes.



APIs Used

OpenWeatherMap API: Fetches current temperature for weather-based suggestions.
Endpoint: https://api.openweathermap.org/data/2.5/weather
Key: Stored in getTemperature function.


Gemini API: Powers the fairy helper with AI responses.
Endpoint: https://generativelanguage.googleapis.com/v1beta/models/gemini-2.0-flash:generateContent
Key: Embedded in the sendMessage function.



Contributing
Feel free to fork this repository and submit pull requests. Suggestions for new features (e.g., notifications, task prioritization) are welcome!
License
This project is licensed under the MIT License. See the LICENSE file for details (create a LICENSE file with MIT terms if desired).
Acknowledgments

Icons from Icons8.
Weather data from OpenWeatherMap.
AI capabilities from Google Gemini API.
