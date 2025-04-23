
<!---
============================================================================
                  CURSOR AI INSTRUCTIONS - DO NOT MODIFY
============================================================================
-->

<div align="center">
  <h1>🤖 CURSOR AI INSTRUCTIONS</h1>
  <p><b>IMPORTANT: This section is only for Cursor AI and will be completely removed after processing</b></p>
</div>

---

## AI Task: Complete README Transformation

Hello Cursor AI! Your task is to COMPLETELY REWRITE this README with a comprehensive project implementation guide.

### Critical Requirements:

1. **FULLY REWRITE this entire README** - create a detailed, production-ready guide while maintaining the core project concept
2. **Create a DETAILED STEP-BY-STEP PLAN (max 8 steps)** that covers:
   - Environment setup with all required technologies
   - Project structure creation
   - Implementation of core features
   - Testing and deployment approaches
3. **Tailor content to the user's profile:**
   - User's Experience Level: `Beginner`
   - User's Available Time: `A Few Hours`
4. **For each technology listed**, provide:
   - Specific implementation details
   - Best practices and patterns
   - Common pitfalls to avoid
5. **Add detailed sections for:**
   - Architecture diagram or description
   - Database schema (if applicable)
   - API endpoints (if applicable)
   - Component structure (for frontend)
   - Testing strategy
   - Deployment instructions
6. **Provide code examples** for critical project parts
7. **REMOVE THESE INSTRUCTIONS COMPLETELY** after your rewrite

Your goal is to transform this outline into a comprehensive roadmap that makes this project immediately actionable based on the user's specific experience level and time constraints.

### ⚠️ CRITICAL FIRST STEP ⚠️

**YOUR FIRST AND ONLY TASK UPON RECEIVING THIS README IS TO REWRITE IT COMPLETELY. DO NOT START IMPLEMENTING THE PROJECT OR WRITING ANY CODE YET.**

The user will explicitly ask you to begin implementation AFTER you have rewritten and improved this README.

<!---
============================================================================
                 END OF CURSOR AI INSTRUCTIONS
============================================================================
-->


# Simple Podcast Recorder

## Project Overview
A basic podcast recording application that allows users to record and save audio files for community podcasting.


> **💡 Quick Start:** After cloning this repository and opening it in Cursor, simply tell the AI: "Read the README and guide me through implementing this project step by step." Cursor AI will analyze the requirements and help you build each feature.


## User Profile
- **Experience Level:** Beginner
- **Available Time to Complete:** A Few Hours

## Technologies
- **React**: Used for building the user interface and providing an interactive experience for users.
- **Web Audio API**: Utilized for accessing the user's microphone and recording audio.
- **JavaScript**: Used as the primary programming language for implementing application logic.
- **HTML**: Used for structuring and organizing the application's user interface.
- **CSS**: Used for styling and layout of the application's user interface.
- **LocalStorage**: Used for storing recorded audio files locally on the user's device.


## Development Steps
### 1. Setting Up the Project
Create a new React project using a tool like create-react-app, and set up the necessary dependencies.

### 2. Implementing Audio Recording
Use the Web Audio API to access the user's microphone and record audio.

### 3. Saving Recordings
Use LocalStorage to save recorded audio files locally on the user's device.

### 4. Creating the User Interface
Use HTML, CSS, and React to create a simple user interface for recording and playing back audio.

### 5. Testing and Debugging
Test the application to ensure it is working as expected, and debug any issues that arise.


## Main Features
Features will be added soon


## Sample Code
```javascript
// Example code snippet
function startRecording() {
  navigator.mediaDevices.getUserMedia({ audio: true })
    .then(stream => {
      // Record audio
    });
}
```


## Getting Started
Instructions will be added soon

## Resources
- [React Documentation](https://reactjs.org/docs/getting-started.html) (documentation)
- [Web Audio API Tutorial](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API) (tutorial)
- [LocalStorage API Documentation](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage) (documentation)
- [HTML and CSS Tutorial](https://www.w3schools.com/html/default.asp) (tutorial)


## AI Coding Prompts

Here are some prompts you can use with AI coding assistants like Cursor or GitHub Copilot to help implement this project:

### Prompt 1
```
Implement the user interface for the Simple Podcast Recorder by creating a React component that includes a start recording button and a list to display recorded audio files. Use HTML to structure the component and CSS to style it.
```

### Prompt 2
```
Use the Web Audio API to record audio from the user's microphone and store it in the browser's local storage. In the startRecording function, set up the media stream and use the recorded audio to create an audio blob. Then, use LocalStorage to store the audio blob with a unique filename.
```

### Prompt 3
```
Add features to the Simple Podcast Recorder by implementing audio playback functionality using the Web Audio API. When a user selects an audio file from the list, use the audio blob to create an audio context and play the audio file. Include controls for pause, play, and volume adjustment.
```


Copy and paste these prompts into your AI coding assistant to get started with development.


---
*Generated by [CodeSpark](https://github.com/YOUR_USERNAME/codespark)*
