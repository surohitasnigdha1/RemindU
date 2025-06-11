RemindU is a study reminder web application that helps students and learners stay on track with their study schedules. The application sends timely reminders via SMS using the Twilio API, ensuring users never miss an important study session.
Built with:

Frontend: React.js

Backend: Node.js with Express

SMS Service: Twilio API

Features
📅 Schedule study reminders with custom messages

📱 Receive SMS notifications at scheduled times

🔔 Multiple reminder options (one-time, daily, weekly) and reminders would be sent 15 minutes prior to the session.

👤 User-friendly interface with responsive design


Setup Instructions
Clone the repository

bash
git clone https://github.com/surohitasnigdha1/RemindU.git
cd RemindU
Install dependencies

bash
# Install server dependencies
cd server
npm install

# Install client dependencies
cd ../client
npm install
Environment Variables Setup

Create a .env file in the server directory with the following variables:

text
TWILIO_ACCOUNT_SID=your_twilio_account_sid
TWILIO_AUTH_TOKEN=your_twilio_auth_token
TWILIO_PHONE_NUMBER=your_twilio_phone_number
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
Run the application

bash
# From the project root directory

# Start the server (from server directory)
cd server
npm start

# Start the client (from client directory in a new terminal)
cd ../client
npm start
The application should now be running on http://localhost:3000 with the server on http://localhost:5000.

Usage
Register for an account or log in if you already have one

Navigate to the "Create Reminder" page

Fill in the reminder details:

Study topic

Reminder message

Date and time

Frequency (one-time, daily, weekly)

Your phone number (for SMS notifications)

Save the reminder

You'll receive SMS notifications at the scheduled times
