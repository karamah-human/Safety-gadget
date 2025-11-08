Overview
This safety gadget consists of a mobile app, backend API, and cloud database. this gadget is connected through satellite communication.
Tech Stack
| Layer | Technology | Description |
| Frontend | React Native | User interface for triggering and managing alerts |
| Backend | Node.js + Express | API that processes alerts and communicates with database |
| Database | MongoDB Atlas | Stores user profiles, contact info, and alert history |
| Device | Bluetooth-enabled wearable | Detects SOS button press and sends signa
Communication flow
-'Users presses on the SOS button'=the gadget alerts the phone through blutooth of satellite communication
-'the app captures this alert' = sends it to the backend API
-'Backend processes request' =it stores this data and also sends out SMS/messages to emergancy services
Security
- JWT authentication for user accounts  
- Encrypted communication (HTTPS, SSL)  
- Role-based data access  
 Technical Feasibility
- React Native ensures cross-platform support (Android + iOS)
- Node.js backend can scale easily for multiple users
- MongoDB supports flexible, location-based data storage
- APIs integrate smoothly with SMS and location service
