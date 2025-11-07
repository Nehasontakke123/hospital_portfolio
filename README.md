# Tekisky Hospital — Doctor & Patient Management System

Tekisky Hospital is a full-stack OPD (outpatient) management system built with React.js, Node.js, Express, and MongoDB. It digitizes prescriptions, manages patient records, and streamlines clinic workflows with role-based dashboards, PDF prescription generation, and WhatsApp notifications.

## Live demo
- Frontend: https://your-project-link.vercel.app  (replace with your live URL)
- Backend / API docs: https://your-api-docs-link  (replace with your API docs URL)

## Key features

- Multi-role dashboards (doctors, receptionists, medical staff, admins)
- Digital PDF prescription generation (jsPDF) and Cloudinary integration
- Patient behavior 5-star rating
- Automated fee tracking and payment status (Paid / Pending)
- Medical records with search and history
- WhatsApp integration for prescription notifications
- Responsive UI using Tailwind CSS

## Tech stack

- Frontend: React, Vite, Tailwind CSS, jsPDF
- Backend: Node.js, Express, MongoDB, Mongoose, JWT, bcryptjs
- Additional: Cloudinary, Twilio (WhatsApp)

## Installation (local)

Open PowerShell and run:

```powershell
cd 'C:\Users\Neha\Desktop\tekisky'
# install dependencies (example if project has package.json)
npm install

# set up environment variables: create a .env with required keys (DB, JWT_SECRET, Cloudinary, Twilio etc.)

# run dev servers (adjust commands to your project scripts)
npm run dev   # frontend, if using a separate frontend setup
npm run start # backend
```

Notes:
- Replace the commands above with your actual frontend/backend start scripts if they are different.
- Ensure you create a `.env` file with your MongoDB connection string and other secrets before starting the server.

## How to use this repo

1. Clone or copy the project files into a folder.
2. Create a `.env` with the required environment variables (see the code where `process.env` is used).
3. Install dependencies and run the dev servers.
4. Open the frontend in the browser and test features (login as different roles, create prescriptions, check WhatsApp notifications).

## Contributing

If you want to contribute, please open an issue or a pull request with a description of your change.

## License

Add your license here (MIT/Apache/etc.)

## Contact

Author: Full-Stack Developer
Project: Tekisky Hospital
