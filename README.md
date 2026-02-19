# AirHub – Travel Stay Booking Platform 

AirHub is a full-stack travel stay booking platform designed to provide a seamless hotel search and reservation experience. It features robust user authentication, dynamic filtering, and an integrated real-time chatbot to assist users in finding their perfect stay.

##  Features
* **User Authentication:** Secure sign-up, log-in, and session management.
* **Smart Search & Filtering:** Find hotels based on location and filter by price ranges.
* **Real-Time Chatbot:** Integrated Socket.IO for a live assistant that provides dynamic hotel recommendations on the fly.
* **Responsive UI:** Clean, intuitive interface ensuring a great user experience across devices.

##  Tech Stack
* **Frontend:** HTML, CSS, JavaScript, Bootstrap
* **Backend:** Node.js, Express.js
* **Database:** MongoDB
* **Real-Time Communication:** Socket.IO / WebSockets

##  What I Learned
Building this project provided hands-on experience with:
* Designing and consuming **RESTful APIs**.
* Structuring and querying NoSQL databases using **MongoDB**.
* Implementing **WebSocket-based communication** for real-time, bidirectional data flow.
* Full-stack application deployment and environment variable management.

##  Run Locally
1. Clone the repository: `git clone https://github.com/adityakuranjekar/AirHub.git`
2. Install dependencies: `npm install`
3. Create a `.env` file in the root directory and add your MongoDB URI: `MONGO_URL=your_connection_string`
4. Start the server: `node app.js` (or `npm start`)
