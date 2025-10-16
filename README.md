# SC-Orion-AI-Assistant
My Star Citizen Pilot AI Assistant
Orion AI Pilot Assistant: Command Console

Orion AI is a specialized, single-file web application designed to act as an in-universe command assistant for the Star Citizen universe. It leverages the power of the Gemini API and Google Search Grounding to provide real-time, context-aware responses to complex, natural language pilot commands.

Key Features

1. Context-Aware Command Execution

Submit complex commands like, "Find the nearest quantum fuel station near Area18 that is safe to land at," and Orion uses live web data (via Google Search) to provide a concise, grounded, and actionable response.

2. Voice Command Integration

Use the 🎙️ Voice Command feature to speak your instructions directly to the application, streamlining operations during active flight.

3. Secure, Persistent Storage (Firebase)

Your Gemini API key is securely saved to a private area in a Firebase Firestore database (using the Canvas environment's provided setup) and is automatically loaded when you access the app again.




**All you need is a free Gemini API Key and you are good to go.**

How to Get Your Gemini API Key
1. Go to Google AI Studio
Open your web browser and navigate to the official developer site: https://aistudio.google.com/ .

2. Make sure you are logged into your Google account.

3. Create the API Key
On the left-hand navigation menu, look for "API key" (it might be under a section called "Get API Key" or similar).

4. Click the "+ Create API key" button.

The site will instantly generate a long, unique string of characters.

5. Copy and Secure Your Key
CRITICAL STEP: This key is your personal credential for accessing Google's AI models. Copy the entire key immediately.


6. Paste the copied key into the designated "Enter Your Gemini API Key" field.

7. Click "Save Key".

Once saved, the app will securely store it using Firebase and you'll be ready to start sending commands to your AI assistant!
