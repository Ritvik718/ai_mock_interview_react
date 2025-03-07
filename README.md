# Interview AI Platform

## Overview
Interview AI Platform is designed to enhance interview preparation by providing a seamless and interactive experience. The platform allows users to answer mock interview questions while leveraging AI-driven validation and feedback. Using speech-to-text conversion, responses are transcribed and analyzed against expected answers by Google Gemini AI. Users receive insightful feedback, helping them refine their responses. The system ensures a fair evaluation process by allowing multiple practice attempts but restricting final submission to one per question. With secure authentication and cloud storage, users can track their progress and access feedback anytime through their personalized dashboard.

## Features
- **Webcam Support:** Users can enable their webcam for a more interactive interview experience.
- **Speech-to-Text Conversion:** The website listens to the user's response and converts it into text using the `react-hook-speech-to-text` NPM package.
- **AI-Powered Validation:** Google Gemini AI evaluates the spoken response against a pre-generated expected answer.
- **Feedback & Rating System:** Users receive detailed feedback and a rating based on their response quality.
- **Data Storage in Firebase:** All interview responses are securely stored in Firebase.
- **Submission Restrictions:** Each answer can only be submitted once, but users can record multiple attempts before submitting.
- **User Authentication:** Clerk ensures secure user authentication and access control.
- **Dashboard & Feedback History:** Users can view their feedback for individual questions and overall interview performance on their homepage.

## Tech Stack
- **Frontend:** React with TypeScript
- **UI Library:** ShadCN UI
- **Authentication:** Clerk
- **AI Integration:** Google Gemini AI
- **Data Storage:** Firebase
- **Speech-to-Text API:** `react-hook-speech-to-text` NPM package

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/interview-ai-platform.git
   cd interview-ai-platform
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up environment variables in a `.env` file:
   ```env
   REACT_APP_FIREBASE_API_KEY=your_firebase_api_key
   REACT_APP_FIREBASE_AUTH_DOMAIN=your_firebase_auth_domain
   REACT_APP_FIREBASE_PROJECT_ID=your_firebase_project_id
   REACT_APP_GEMINI_API_KEY=your_gemini_api_key
   REACT_APP_CLERK_API_KEY=your_clerk_api_key
   ```
4. Start the development server:
   ```bash
   npm run dev
   ```

## Usage
1. Log in using Clerk authentication.
2. Start a mock interview with a set of predefined questions.
3. Enable the webcam and start recording your answer.
4. The application will convert your speech to text using `react-hook-speech-to-text` and validate it against an expected answer using Google Gemini AI.
5. Receive feedback and a rating based on your response.
6. Submit the best response (only once per question).
7. Access detailed feedback and performance analytics on the homepage.

## Future Enhancements
- Support for different interview types and question sets.
- AI-powered answer improvement suggestions.
- Video recording and playback for self-evaluation.
- Gamification elements such as badges and leaderboards.

## Contributing
1. Fork the repository.
2. Create a new branch (`feature/your-feature-name`).
3. Commit your changes.
4. Push to the branch and create a Pull Request.

## License
This project is licensed under the MIT License.

## Contact
For any issues or feature requests, please open an issue on GitHub or contact the project maintainers.

