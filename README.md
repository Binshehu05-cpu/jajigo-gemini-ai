# JajiGo Gemini AI - Render deployment

1. Create a new GitHub repository.
2. Upload every file in this folder to the repository root.
3. Create a Gemini API key in Google AI Studio.
4. On Render: New -> Web Service -> connect the repository.
5. Build command: npm install
6. Start command: npm start
7. Add environment variable GEMINI_API_KEY with your real key.
8. Deploy and copy the service URL, for example https://your-service.onrender.com
9. Put that URL into the JajiGo HTML configuration as JAJIGO_GEMINI_CONFIG.baseUrl.
10. Test: https://your-service.onrender.com/api/ai/health

Do not upload .env with a real API key to GitHub.
