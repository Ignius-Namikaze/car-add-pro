# 🚗 Ultimate Ad Generator Pro

This is a single-file web application designed to instantly generate catchy automotive taglines and full marketing copy using a mix of deterministic logic and advanced AI (Gemini). It features real-time data persistence via Google Firestore, allowing users to customize the generator's vocabulary and save their favorite outputs.

# ✨ Key Features

- Dynamic Tagline Generation: Instantly creates two-line, punchy taglines based on user selections (Car Type, Style Focus, and Target Audience).

- Persistent Custom Vocabulary: Users can add and delete their own custom verbs, features, adjectives, and slogans, which are integrated into the generation logic.

- AI-Powered Copywriting: Utilizes the Gemini API (specifically gemini-2.5-flash-preview-09-2025) to take a generated tagline and expand it into a full, two-paragraph, professional ad script.

- Saved Ads Collection: Favorite taglines and their generated full ad copies can be saved to a personal, real-time collection.

- Modern & Minimalist Design: Built with native HTML/JavaScript and styled using Tailwind CSS for a professional, fully responsive user experience.

# ⚙️ Architecture & Technologies

This is a single-page application (index.html) using a modern client-side stack:

**Component:** Frontend, Data Persistence, Core AI, API Handling

**Technology:** HTML5, JavaScript, Tailwind CSS, Google Firestore, Gemini API, fetchWithBackoff

**Role:** Structure, logic, and professional styling/responsiveness, Stores user data (Custom Words and Saved Ads), Provides the intelligence for the "Full Ad Copy" generation feature, Ensures reliable asynchronous communication with the Gemini API.
