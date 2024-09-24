# 🏥 Healthcare Facility Management System
Overview
The Healthcare Facility Management System is a web-based application designed to streamline patient interactions with a healthcare facility. It offers features like patient registration, secure login, booking appointments with specific doctors, and the ability to reschedule or cancel appointments anytime. This system aims to enhance the patient experience and simplify administrative tasks for healthcare providers.

# ✨ Features
1. 📝 Patient Registration:

- New patients can create an account by providing necessary details like name, age, contact information, and medical history.
Secure storage of patient information using modern encryption techniques.
Patient Login:

2. 🔐 Patients can log in using their email and password.
- Passwords are stored securely using hashing algorithms to ensure privacy.
Book an Appointment:

3. 🩺 Patients can browse a list of available doctors and book appointments.
- Appointments can be scheduled for available dates and times specific to each doctor.
Confirmation is provided upon successful booking.
Reschedule or Cancel Appointments:

4. 🔄 Patients can view their upcoming appointments.
- Appointments can be easily rescheduled or canceled at any time, depending on availability.

# 🛠️ Technologies Used

1. Frontend: NextJS with TailwindCSS
2. Backend: Node.js with Appwrite
3. Deployment: Deployed using Vercel

🚀 Getting Started

# Installation
To run the Healthcare Facility Management System locally, follow these steps:

1. Clone the repository:
  - git clone https://github.com/mairura/healthcare.git
   
3. Navigate to the project directory:
   - cd carepulse

5.  Install dependencies
      - npm install
    
6. Set up environment variables:
  - PROJECT_ID=
  - API_KEY=
  - PATIENT_COLLECTION_ID=
  - DOCTOR_COLLECTION_ID=
  - APPOINTMENT_COLLECTION_ID=
  - NEXT_PUBLIC_BUCKET_ID=
  - NEXT_PUBLIC_ENDPOINT=https://cloud.appwrite.io/v1
  - NEXT_PUBLIC_ADMIN_PASSKEY=
  - TWILIO_RECOVERY_KEY=
  - TWILIO_ACCOUNT_SID=
  - TWILIO_AUTH_TOKEN=
   - SENTRY_AUTH_TOKEN=
    
5. Run the development server:
   npm run dev

6. Open http://localhost:3000 to view the app in your browser.

# 🎯 Future Improvements
1. 📩 Appointment Notifications: Implement email or SMS notifications to remind patients of upcoming appointments.
2. 💳 Payment Integration: Add functionality for patients to make payments for their consultations or treatments online.
3. 📄 Medical Records: Allow patients to upload and view their medical records through the platform.

   
