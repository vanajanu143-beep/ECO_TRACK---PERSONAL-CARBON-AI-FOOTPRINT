***DUE TO REUSABILITY & UNSUPPORTED THE SYSTEM CONDITIONS AND TECH STACK UNAVALABILITY IN THE DEPLOYEMENT AND ETC SOME ..... REASONS I REUSED THIS REPOSITORY ***

EcoTrack is a web-based personal carbon footprint tracking application designed to help users log daily habits, calculate carbon emissions, visualise their environmental impact, and receive AI-powered eco-friendly suggestions. The application was developed as a practical college project with a focus on usability, responsiveness, and meaningful sustainability insights. It provides a single dashboard where users can record travel, food, and energy activities, view their footprint history, track progress against a personal carbon budget, and earn achievement badges for consistent eco-friendly behaviour.

The system is built using React.js for the frontend, Flask (Python) as the backend service, and Firebase Firestore as the cloud database. The application integrates external services for specific tasks: Groq API (llama-3.3-70b-versatile) for AI-generated eco suggestions, Carbon Interface API for real-world emission factor data, and Chart.js for footprint trend visualisations. The final implementation includes Firebase Authentication, a multi-step habit logger, an animated carbon gauge, a 30-day heatmap calendar, streak tracking, and a badge achievement system.
 

*Frontend:** React.js, Vite, Chart.js
- **Backend:** Flask (Python)
- **Database:** Firebase Firestore
- **Authentication:** Firebase Authentication
- **APIs:** Groq API

  
EcoTrack is a web-based personal carbon footprint tracking application developed using React.js, Flask, and Firebase Firestore. It allows users to log daily travel, food, and energy activities, calculate carbon emissions, visualize trends through charts, track sustainability progress, and receive AI-powered eco-friendly recommendations for reducing environmental impact.

EcoTrack/
│
├── backend/
│   ├── app.py
│   ├── routes/
│   ├── requirements.txt
│   └── .env
│
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── vite.config.js
│
├── README.md
└── .gitignore


EcoTrack is a web-based personal carbon footprint tracking application developed using React.js, Flask, and Firebase Firestore. It enables users to log daily activities, calculate carbon emissions, visualize environmental impact through interactive charts, and receive AI-powered sustainability recommendations. The system promotes eco-friendly habits with progress tracking, achievement badges, and personalized insights. 🌱
