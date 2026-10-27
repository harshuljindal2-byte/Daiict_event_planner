# Daiict_event_planner
🎪 DA-IICT Campus Event Planner

A lightweight, modern web application designed for students, event organizers, and the Student Body Government (SBG) at DA-IICT, Gandhinagar. It provides real-time environmental analysis, intelligent scheduling suitability scoring, sunset/twilight calculations, and planning tools to ensure seamless execution of daytime and overnight campus events.

✨ Features

🎯 Event Presets & Categories: Pre-configured presets for iconic campus events like Tarang Garba Night, Overnight Hackathons, Synapse Open Air Concerts, as well as custom events across Cultural, Sports, and Tech domains.

🌤️ Real-Time Weather & Environmental Data: Integration with free weather APIs to monitor rain probability, feel-like temperatures, wind speed, and sunset timings for Gandhinagar (23.1888° N, 72.6285° E).

🌬️ Air Quality Integration (Optional): Supports OpenAQ API key input to fetch live PM2.5 levels for health-conscious sports and outdoor scheduling.

🏛️ Venue-Aware Scoring Algorithm: Smartly adjusts environmental impact weights based on venue selection (e.g., neutralizes rain/wind risks for indoor venues like the Auditorium).

⏳ Live Countdown & Hourly Breakdown: Interactive hour-by-hour status strip indicating optimal time slots during multi-day or overnight event windows.

📋 Automated Logistics Checklist: Dynamically generates actionable checklists (hydration stations, canopy setups, security notifications) based on forecasted risks.

📅 Export & Share Tools: Includes one-click .ics calendar file generation, copy-to-clipboard summaries, and WhatsApp sharing buttons.

🛠️ Tech Stack & API Integrations

Frontend: Pure HTML5, CSS3 (Modern dark theme with glassmorphism), Vanilla JavaScript (ES6+).

Typography: Bricolage Grotesque (Google Fonts).

APIs Used:

Open-Meteo API: Hourly weather forecasting (temperature, humidity, rain probability, wind speed).

Sunrise-Sunset API: Civil twilight and sunset timings in IST.

OpenAQ API v3: Real-time ambient air quality index (PM2.5).

🚀 Getting Started

No complex node setup or build steps required! The entire application runs natively in any modern web browser.

1. Clone the Repository

git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git
cd YOUR_REPOSITORY_NAME


2. Run Locally

Simply double-click index.html or open it using VS Code's Live Server extension.

📖 How to Push to GitHub

If you are pushing this code to GitHub for the first time, execute the following commands in your terminal:

# 1. Initialize git (if not already initialized)
git init

# 2. Stage all files
git add .

# 3. Create initial commit
git commit -m "Initial commit - DA-IICT Event Planner"

# 4. Set local main branch
git branch -M main

# 5. Link your remote GitHub repository
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git

# 6. Push code to GitHub
git push -u origin main


🤝 Contributing

Contributions are welcome! Feel free to open issues or submit pull requests to add new campus venues, improve risk algorithms, or add new presets.

📄 License

Distributed under the MIT License. Developed for the student community at DA-IICT Gandhinagar.
