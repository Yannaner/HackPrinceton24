
<div align="center">

# SustainAI: Your Personal Guide to Sustainable Living

[![Last Commit](https://img.shields.io/github/last-commit/Yannaner/HackPrinceton24?label=Last%20Commit)](https://github.com/Yannaner/HackPrinceton24/commits)
[![Languages](https://img.shields.io/github/languages/count/Yannaner/HackPrinceton24?label=Languages)](https://github.com/Yannaner/HackPrinceton24)
[![Stars](https://img.shields.io/github/stars/Yannaner/HackPrinceton24?label=Stars)](https://github.com/Yannaner/HackPrinceton24/stargazers)
[![Forks](https://img.shields.io/github/forks/Yannaner/HackPrinceton24?label=Forks)](https://github.com/Yannaner/HackPrinceton24/network)

</div>

---

## Table of Contents
- [Overview](#overview)
- [Inspiration](#inspiration)
- [What It Does](#what-it-does)
- [How We Built It](#how-we-built-it)
- [Challenges](#challenges)
- [Accomplishments](#accomplishments)
- [What We Learned](#what-we-learned)
- [What's Next](#whats-next)
- [Project Structure](#project-structure)
- [Installation & Usage](#installation--usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [Acknowledgements](#acknowledgements)

---

## Overview

**SustainAI** is an AI-powered web application that serves as your personal sustainability assistant. It offers tailored recommendations, actionable insights, and an engaging chatbot interface—all aimed at helping you reduce your environmental impact.

---

## Inspiration

Climate change and environmental challenges can feel overwhelming. SustainAI was born out of the desire to empower individuals by bridging the gap between sustainability awareness and actionable change. Our goal is to transform everyday decisions into meaningful contributions for a healthier planet.

---

## What It Does

- **Personalized Sustainability Advice**: Offers customized recommendations based on user data.
- **Interactive Chatbot**: Engages users with AI-driven, natural language conversations using the OpenAI GPT-3.5-Turbo API.
- **Data Integration**: Combines information from health apps, purchase histories, and transportation methods.
- **Action Tracking**: Allows users to monitor sustainable actions, build streaks, and track progress.
- **Educational Resources**: Provides a rich library of content on sustainability topics.

---

## How We Built It

- **Frontend**: Developed with **React** and styled with **Tailwind CSS** for a responsive and intuitive interface.
- **Backend**: Powered by **Node.js** with **Express.js**, handling API requests and integrating external services.
- **Database**: Utilizes **MongoDB Atlas** for scalable, secure data storage.
- **AI Integration**: Leverages the **OpenAI GPT-3.5-Turbo API** to deliver natural, engaging conversations.
- **MATLAB Integration**: Converts complex WAD files (Walk Activity Data) into structured formats (CSV/JSON) for enhanced data processing.

---

## Challenges

- **AI Chatbot Integration**: Balancing engaging conversation with actionable sustainability advice.
- **Data Integration**: Managing diverse data sources while ensuring robust privacy and security.
- **WAD File Processing**: Developing MATLAB scripts to accurately convert binary data into usable formats.
- **Time Constraints**: Delivering a fully functional project within a hackathon timeframe.

---

## Accomplishments

- Integrated AI to deliver real-time, personalized sustainability advice.
- Successfully developed MATLAB scripts for reliable WAD file conversion.
- Implemented engaging user features such as streak tracking and action logging.
- Maintained ethical data handling and robust security throughout the project.

---

## What We Learned

- Advanced our skills in AI and natural language processing.
- Gained comprehensive experience in full-stack web development and data integration.
- Learned specialized techniques in MATLAB for processing complex data formats.
- Enhanced our teamwork, project management, and problem-solving abilities.

---

## What's Next

- **Mobile Application Development**: Creating native apps for iOS and Android.
- **Enhanced Personalization**: Utilizing advanced machine learning for even more tailored advice.
- **Community Features**: Introducing challenges, leaderboards, and social sharing.
- **Voice Assistant Integration**: Providing hands-free interaction for improved accessibility.

---

## Project Structure

```
SustainAI/
├── client/                  # Frontend application (React)
├── server/                  # Backend API (Node.js & Express)
├── matlab-env/              # MATLAB scripts for WAD file conversion
├── my-eco-chat/             # Chatbot implementation and AI integration
├── .gitignore
├── package.json
├── README.md                # This file
└── other configuration files
```

---

## Installation & Usage

### Prerequisites
- [Node.js](https://nodejs.org/)
- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas)
- [MATLAB](https://www.mathworks.com/products/matlab.html) (for data conversion scripts)

### Installation
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Yannaner/HackPrinceton24.git
   cd HackPrinceton24
   ```
2. **Install Dependencies**:
   ```bash
   cd client
   npm install
   cd ../server
   npm install
   ```
3. **Configure Environment Variables**:  
   Create a `.env` file in the server directory with the necessary configuration (e.g., MongoDB URI, OpenAI API keys).

### Running the Application
- **Start the Backend**:
  ```bash
  cd server
  npm start
  ```
- **Start the Frontend**:
  ```bash
  cd client
  npm start
  ```
- **Access the Application**:  
  Open your browser and navigate to `http://localhost:3000`

---

## Contributing

Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a feature or bugfix branch.
3. Commit your changes with clear messages.
4. Open a pull request detailing your improvements.

---

## License

This project is licensed under the [MIT License](LICENSE).

---


## Acknowledgements

- [aymane-omari/HackPrinceton](https://github.com/aymane-omari/HackPrinceton) – Inspiration and foundational code.
- The HackPrinceton team and all contributors for their support.
- OpenAI for providing innovative AI technology.
```

