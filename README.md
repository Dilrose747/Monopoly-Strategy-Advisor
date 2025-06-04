🧠 Monopoly Strategic Advisor
A lightweight, browser-based tool to help players make smarter Monopoly investment decisions based on ROI and game state.

🎯 Overview
The Monopoly Strategic Advisor is a web application that provides real-time property investment recommendations in the Monopoly board game. Given a player’s current cash, position on the board, and property ownerships, it suggests whether to buy a property based on its cost, rent potential, and Return on Investment (ROI) at various development levels.

Whether you’re a casual player or a game theory enthusiast, this tool brings strategic depth and data-driven gameplay to the classic board game.

🚀 Features
✅ Input current cash, board position, and owned/opponent properties

🔢 Calculates and displays ROI at different development levels (Base to Hotel)

🧠 Provides suggestions to buy or skip based on affordability and strategic value

🎨 Covers all properties, including:

Streets (e.g., Boardwalk, Baltic Avenue)

Railroads (e.g., Reading Railroad)

Utilities (e.g., Water Works, Electric Company)

📊 Dynamically rendered tables showing Rent and ROI

💡 Intuitive UI with instant results – no refresh required

🛠️ Technologies Used
Tool	Purpose
HTML5	Structuring the application and inputs
CSS3	Styling for clean, modern, and responsive layout
Vanilla JavaScript (ES6+)	Core logic: parsing input, handling board position, computing ROI, dynamic UI rendering
Data Modeling (JS Objects)	Simulates Monopoly board properties including cost, color group, rent levels, and ROI values

📸 Demo
🖼️ Visit the app: Try the live demo


A simple UI for a powerful board game strategy engine.

🧮 Example Use
Input your current cash (e.g., $600).

Enter your current position on the board (0–39).

Provide a comma-separated list of your owned properties.

Enter properties owned by opponents.

Click "Get Recommendation" – see if the landed property is worth buying!

🗺️ Property Reference
Supports all key Monopoly properties with board-accurate positions.

ROI is pre-calculated for:

Base (undeveloped)

1–4 Houses

Hotel

Includes special properties like:

🔌 Utilities (position 12 & 28)

🚂 Railroads (positions 5, 15, 25, 35)

💡 Future Enhancements
🧠 AI-driven decision engine based on opponent holdings

🎲 Dice-roll simulations for landing probabilities

📈 Monte Carlo simulations for long-term ROI

🌐 Multiplayer board tracker with cloud sync
