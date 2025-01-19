# Emotional-Support-And-Wellness-App
Because it matters !

# Emotional-Support-And-Wellness-App

**Because it matters!**

## Overview
The Emotional-Support-And-Wellness-App is a cutting-edge platform designed to provide emotional support and wellness insights to users. This app combines the power of **React/Next.js**, **Machine Learning (ML)**, and **OpenAI's GPT API** to offer human-like conversations that prioritize mental health and self-care.

### Key Features:
- **Interactive Chat Interface**: Built with React/Next.js for a modern and engaging user experience.
- **Sentiment Analysis**: Understands user emotions through ML sentiment analysis and adapts responses accordingly.
- **Human-like Conversations**: Leverages advanced ML models and GPT API integration to simulate empathetic, human-like dialogue.
- **Default Settings for Emotional Understanding**: Provides prompts such as "Is there anything bothering you more?" to ensure deeper engagement.
- **Mood Tracking**: Tracks emotional patterns over time, empowering users with actionable insights for better mental wellness.
- **Voice Recorder Integration**: Allows users to express feelings verbally, making the app more engaging and inclusive.

---

## Tech Stack
- **Frontend**: React/Next.js
- **Backend**: Node.js or FastAPI
- **ML Models**:
  - Sentiment Analysis: Pre-trained models from TensorFlow Hub or Hugging Face.
  - Mood Tracking: Data visualization using Chart.js or Recharts.
- **API Integration**: OpenAI GPT API
- **Styling**: Tailwind CSS
- **Deployment**: Vercel (Frontend), Heroku/Render (Backend)
- **Voice Recorder**: Browser-based MediaRecorder API

---

## Installation
Follow these steps to set up the project locally:

### Prerequisites:
1. Node.js 14+
2. OpenAI API key
3. Libraries: `axios`, `tailwindcss`, `openai`, `next`

### Steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Emotional-Support-And-Wellness-App.git
   cd Emotional-Support-And-Wellness-App
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Add your OpenAI API key:
   - Create a `.env.local` file in the project root.
   - Add your key:
     ```env
     NEXT_PUBLIC_OPENAI_API_KEY=your_api_key_here
     ```
4. Run the application:
   ```bash
   npm run dev
   ```

---

## Features in Detail

### 1. **Interactive Chat Interface**
   - Built with **React/Next.js**, the chat interface provides a modern and intuitive user experience.
   - Users can type messages and receive real-time, context-aware responses.

### 2. **Sentiment Analysis**
   - Uses an ML model to classify the user's emotions (e.g., happy, sad, anxious).
   - Responses are tailored based on the detected sentiment.

### 3. **Human-like Conversations**
   - Integrates OpenAI's GPT API for sophisticated natural language understanding and generation.
   - Incorporates pre-defined rules and responses to maintain a supportive tone.

### 4. **Default Emotional Prompts**
   - Includes built-in prompts such as:
     - "What’s been the highlight of your day?"
     - "Is there anything bothering you more?"
     - "Would you like to talk about it?"
   - Ensures users feel heard and understood.

### 5. **Mood Tracking**
   - Tracks users' emotional patterns over time using visual representations like graphs and charts.
   - Helps users identify triggers, trends, and areas for improvement in their mental wellness journey.
   - Empowers users with actionable insights for better emotional health.

### 6. **Voice Recorder Integration**
   - Adds an engaging voice recording feature, allowing users to express their feelings verbally.
   - Provides an alternative way to communicate, making the app more inclusive and user-friendly.
   - Analyzes voice input for sentiment detection and adapts responses accordingly.

---

## File Structure
```
Emotional-Support-And-Wellness-App/
|-- components/              # Reusable React components
|-- pages/                   # Next.js pages
|-- public/                  # Static assets
|-- styles/                  # Styling files (Tailwind CSS)
|-- utils/                   # Utility functions (e.g., API calls, data processing)
|-- .env.local               # Environment variables (OpenAI API key)
|-- package.json             # Node.js dependencies
|-- README.md                # Project documentation
```

---

## Future Enhancements
- **Customizable Responses**: Allowing users to adjust the tone and style of responses.
- **Mobile App Integration**: Expanding the platform to mobile devices.
- **Enhanced Voice Features**: Adding voice-to-text transcription and personalized voice tones.

---

## Contributing
We welcome contributions! To contribute:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature-name"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

---

## License
This project is licensed under the [MIT License](LICENSE).

---

## Contact
For any inquiries or feedback, please reach out to us at:

- **Email**: anushkachaudhary19128@gmail.comcom

---

**Let’s create a world where mental wellness is a priority!**
