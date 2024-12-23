Gemini Chatbot
Gemini Chatbot is an interactive web application that simulates a chatbot experience. It dynamically generates responses to user inputs using an API integration, features theme switching, and allows users to save chats locally for future reference.

Features
Dynamic Chat Responses: Fetches responses from the Gemini API based on user queries.
Interactive Suggestions: Predefined suggestions to help users get started.
Theme Switching: Toggle between light and dark modes with persistent settings.
LocalStorage Support: Saves chat history and theme preferences for future sessions.
Error Handling: Displays user-friendly error messages for API failures.
Responsive Design: Fully responsive and optimized for various devices.
Technologies Used
Frontend: HTML, CSS, Tailwind CSS, JavaScript
API: Google Gemini API
LocalStorage: For saving chat history and theme preferences
Screenshots
(Include screenshots of the chatbot interface showing the UI in action.)

Installation and Usage
Clone the Repository:

bash
Copy code
git clone https://github.com/Vishalkondi/Gemini-Chatbot.git
cd Gemini-Chatbot
Set Up API Key:

Replace PASTE-YOUR-API-KEY in script.js with your actual API key.
Run the Application:

Open index.html in a browser to use the chatbot.
Project Structure
bash
Copy code
Gemini-Chatbot/
├── index.html       # Main HTML file
├── style.css        # Styling for the chatbot
├── script.js        # JavaScript logic for chatbot interactions
├── images/          # Assets (Gemini avatar, user avatar, etc.)
└── README.md        # Project documentation
LocalStorage Details
Saved Chats: Stored under the key saved-chats in the browser's localStorage.
Theme Preferences: Stored under the key themeColor.
Backend Security (Optional)
To prevent exposing your API key, implement a backend proxy. A sample backend using Node.js is provided in the Backend Example section below.

Future Improvements
Authentication: Add user authentication for personalized chatbot experiences.
Advanced Error Handling: Handle specific error codes from the API.
Backend Proxy: Secure the API key by routing requests through a backend server.
Multilingual Support: Allow users to interact in different languages.
Contributing
Contributions are welcome! Feel free to fork the repository and submit a pull request.

License
This project is licensed under the MIT License.

Acknowledgments
Design inspiration: Coding Nepal
Avatar images: Gemini logo and user icon
API powered by Google Gemini API
