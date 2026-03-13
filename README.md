🦷 Dentwise – AI-Powered Dental Management SaaS
Dentwise is a modern, full-stack solution designed to revolutionize dental clinic workflows. By integrating Vapi AI, the platform offers a voice-activated assistant that handles patient assessments and scheduling, bridging the gap between traditional healthcare and cutting-edge automation.
Live Demo | Report Bug

🚀 Key Features
1. 🎙️ AI Voice Assessment: Integrated Vapi AI to provide a natural language voice interface for preliminary patient diagnosis and appointment inquiries.
2. 📅 Smart Scheduling: A seamless booking system that syncs patient requests directly with the clinic’s availability.
3. 🔐 Secure Authentication: Implemented Clerk for robust, HIPAA-aligned user management and role-based access control.
4. 📊 Clinical Dashboard: A centralized hub for practitioners to manage patient records, treatment history, and digital invoices.
5. 📱 Responsive Design: Built with Tailwind CSS to ensure a premium experience across desktops, tablets, and mobile devices.

🛠️ Tech Stack
Layer        Technology
Frontend     React.js, Tailwind CSS, Lucide Icons
Backend      Node.js, Express.js
Database     MongoDB (Mongoose)
AI/Voice     Vapi AI
Auth         Clerk
Deployment   Render

📦 Installation & Setup
1. Clone the repository
    Bash
    git clone https://github.com/yourusername/dentwise.gitcd dentwise
2. Install dependencies:Bash# Install backend deps
      npm install
    # Install frontend deps
    cd client && npm install
3. Environment Variables:
   Create a .env file in the root directory and add your credentials:
   Code snippetPORT=5000
   MONGO_URI=your_mongodb_uri
   VAPI_API_KEY=your_vapi_key
   CLERK_PUBLISHABLE_KEY=your_clerk_key
4. Run the application:
   Bash
   npm run dev


   
🛡️ Security & PrivacyDentwise is built with data integrity in mind. By utilizing Clerk for session management and sandboxed environments for data processing, the platform ensures that sensitive patient information remains protected and compliant with modern web standards.

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
