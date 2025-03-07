# AI Mock Interview Platform

## Overview
Interview AI Platform is designed to enhance interview preparation by providing a seamless and interactive experience. The platform allows users to create custom mock interviews tailored to specific job roles, answer questions in real-time, and receive AI-driven feedback. Using speech-to-text conversion, responses are transcribed and analyzed against expected answers by Google Gemini AI. Users receive insightful feedback, helping them refine their responses. The system ensures a fair evaluation process by allowing multiple practice attempts but restricting final submission to one per question. With secure authentication and cloud storage, users can track their progress and access feedback anytime through their personalized dashboard.

## Features
- **Custom Mock Interview Setup:** Users can create personalized mock interviews by specifying:
  - **Job Role / Position**
  - **Job Description**
  - **Years of Experience**
  - **Tech Stacks**
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

## Usage
1. **Create a Mock Interview**: Start by entering job details such as role, description, experience, and tech stacks.
2. **Start Interview**: Proceed to the interview questions.
3. **Enable Webcam (Optional)**: Use video for a more interactive experience.
4. **Record Answer**: Speak your answer, which is converted to text.
5. **AI Validation**: Google Gemini AI evaluates the response and provides feedback.
6. **Submit Once**: After finalizing the answer, submit (only once per question).
7. **View Feedback**: Access detailed performance analytics on the homepage.

