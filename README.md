Wikelo Cloud Sync v1.0
Wikelo Cloud Sync is a real-time, shared-authority logistics and inventory management tool. It is designed to coordinate squad members by turning a standard Google Sheet into a live, collaborative database for tracking materials, locations, and contract completions.

🚀 Key Features
Shared Pool Authority: No single owner. Every squad member can add, move, or delete items from the manifest. Changes sync globally across all active sessions.

Wikelo Hub Dispatch: Dedicated WKL button to rapidly "teleport" items to primary logistics hubs: DASI, SELO, or KINGA.

Material Consumption Engine: The "Initialize Hand-In" system automatically calculates and subtracts required materials from specific hub inventories.

Live Transaction Logging: A persistent history of completed contracts, showing who performed the hand-in, the reward earned, and the source location used.

Visual Sync Confirmation: A real-time "Sync Lamp" pulses to confirm successful data transmission with the Google Apps Script API.

Customizable Workspace: Resizable sidebar panes allow users to balance the material input area and the shared manifest based on their screen size.

🛠️ Installation & Setup
1. Google Sheets Backend
Create a new Google Sheet.

Go to Extensions > Apps Script.

Paste the provided Code.gs into the editor.

Click Deploy > New Deployment.

Type: Web App

Execute as: Me

Who has access: Anyone

Copy the Web App URL (it must end in /exec).

2. Frontend Configuration
Open index.html.

Find the const SCRIPT_URL variable at the beginning of the <script> block.

Replace the placeholder with your Web App URL.

Ensure wikelo-data.json and locations.json are in the same folder as index.html.

🎮 How to Play
Join the Squad: Enter a SQUAD_CODE (must be identical for all teammates) and your HANDLE.

Log Materials: Add items via the sidebar. Use MOV to update a custom location or WKL to send them to a primary hub.

Monitor Contracts: The main grid displays recipes. When a contract turns Green, it is "READY" for hand-in.

Complete Mission: Click INITIALIZE_HAND_IN, select the source hub, and the tool will consume the materials and log the victory in the Recent Transactions feed.

Legal Disclaimer
Wikelo Cloud Sync is an unofficial fan-made tool. It is not endorsed by or affiliated with the Cloud Imperium group of companies.

All game content and materials, including Star Citizen, Squadron 42, and all related logos, characters, ships, and locations are trademarks or registered trademarks of Cloud Imperium Rights LLC and Cloud Imperium Rights Ltd. All rights reserved.

The use of any in-game terminology, ship names, or locations within this tool is intended solely for identification and gameplay coordination purposes among the fan community and does not imply ownership of said intellectual property.
