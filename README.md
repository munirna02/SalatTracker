Salat Tracker: 
a Progressive Web App that provides Muslim prayer time based on city you provide. The app uses a combination of Flask (python) backend, aladhan api for prayer times, and PWA manifest and service work to ensure offline support and mobile friendly eature.

Features:
  1. Fetch Selat time for any city based on user's input.
  2. provid prayer time for Fajr, Duhr, Asr, Maghrib, and Isha.
  3. Allow installation on mobile devices for easy access.

Technology used
  1. Backend: Flask (python)
  2. API: Aladhan API for selat time
  3. Frontend: HTML, CSS, JS
  4. PWA Features: Service Workrs, Web App Manifest
  5. Geolocation: OpenCage API(get city coordinates)

Instruction:
  1. set up environment variable. .env file in the root of the project and OPENCAGE_API_KEY=your-opencage-api-key
  2. python app.py
  3. Service Worker: Caches necessary files for offline use.
  4. Manifest File: Allows the app to be installed on mobile devices with a custom icon, name, and theme color.



