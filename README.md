<div align="center">
<img width="1200" height="475" alt="GHBanner" src="https://ai.google.dev/static/site-assets/images/share-ais-513315318.png" />
</div>

# Run and deploy your AI Studio app

This contains everything you need to run your app locally.

View your app in AI Studio: https://ai.studio/apps/d36d0de1-2d53-4e55-9fcd-5f97c356e6c1

## Run Locally

**Prerequisites:**  Node.js


1. Install dependencies:
   `npm install`
2. Set the `GEMINI_API_KEY` in [.env.local](.env.local) to your Gemini API key
3. Run the app:
   `npm run dev`

## Voice Assistant

The AI Health Assistant now supports browser-based voice interaction in supported browsers:

- Click the microphone button and speak a health/wellness question.
- The recognized speech is sent directly to the existing Gemini AI Assistant.
- AI responses are automatically read aloud using browser speech synthesis.
- Use the speaker button to replay the latest AI response or stop speech.
- Voice recognition uses the browser Web Speech API; Chrome/Edge are recommended.
- The voice feature does not require a separate speech API key.

Voice input/output remains subject to the same educational and medical-safety guidance as the text AI Assistant.


## Competition-ready upgrades

The current build includes the original AI HealthMate modules plus a judge-facing **AI Wellness Command Center**:
- Rule-based wellness risk monitor using recent entered vitals and lifestyle adherence.
- Vital trend analytics for heart rate and blood pressure.
- Personalized next-action cards for hydration, sleep, and vital tracking.
- One-click export of an educational wellness summary.
- Voice-enabled AI assistant using browser speech recognition and speech synthesis.
- Multimodal report analysis with image/text upload.
- Symptom, vitals, diet, sleep, hydration, history, and AI chat workflows.
- Safety-first language: the app is educational and does not diagnose or prescribe treatment.

### Recommended live demonstration order
1. Open Dashboard and show the wellness score.
2. Open Report Analysis and upload a sample report image.
3. Ask the AI Assistant a question using the microphone and demonstrate spoken output.
4. Open AI Command Center to show risk signals, trend analytics, and next actions.
5. Export the wellness summary to demonstrate practical output.

No new npm dependency is required for the competition upgrade.
