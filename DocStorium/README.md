🚀 Storium — Secure File Storage & Sharing Platform














A modern decentralized file storage and sharing application that ensures data security, scalability, and user-friendly management.
Storium integrates IPFS via Pinata, secure Google OAuth login, and subscription-based storage tiers — built using the MERN + Next.js stack.


🌟 Features

Storium combines security, simplicity, and decentralization in one seamless platform:

🔐 Secure Authentication – Login effortlessly using Google OAuth with Better Auth.

🌐 Decentralized Storage – Upload and retrieve files through IPFS using Pinata, ensuring data immutability and privacy.

📁 File Management Suite – Upload, rename, delete, and download files with a modern, minimal interface.

🤝 Granular File Sharing – Share your files securely with custom permissions (read/update/delete).

💳 Subscription System – Integrated Paddle Payments for managing premium plans and extended storage capacity.

🧭 Infinite Scrolling – Smooth browsing experience for large file lists using lazy loading.

🎨 Modern UI/UX – Built with Tailwind CSS, Shadcn UI, and responsive dark mode for a polished user experience.

🛠️ Technology Stack

This project leverages a modern full-stack architecture to provide scalability and performance:

Category	Technologies
Frontend	Next.js 14, React 18, TypeScript, Tailwind CSS, Shadcn UI, React Query
Backend	Node.js, Hono
Database	MongoDB (Mongoose ORM)
Authentication	Better Auth (Google OAuth)
Storage	IPFS (via Pinata)
Payments	Paddle
Deployment	Vercel
⚙️ System Workflow

The Storium platform follows a robust and modular workflow:

User Authentication – Secure sign-in through Google OAuth.

File Upload – Files are pinned and stored in IPFS via Pinata.

Metadata Storage – File metadata (owner, permissions, IPFS hash, size) is saved in MongoDB Atlas.

File Access & Sharing – Authorized users can access, rename, or delete files using the UI.

Subscription Management – Users can upgrade their storage plans via Paddle’s API.

Data Retrieval – Files are served via Pinata Gateway for fast and reliable access.

🚀 Getting Started

Follow these steps to run Storium locally on your system.

Prerequisites

Node.js (v18 or higher)

Bun, npm, or yarn

MongoDB Atlas account

Google Cloud credentials (OAuth Client)

Pinata account (for IPFS)

Paddle account (for payment integration)

Installation & Setup

Clone the repository:

git clone https://github.com/Ankitkumar9006/Storium
cd storium


Install dependencies:

bun install


Create a .env file in the root directory with the following variables:

# Authentication
BETTER_AUTH_SECRET="your_strong_secret_for_better_auth"
BETTER_AUTH_URL="http://localhost:3000"
GOOGLE_CLIENT_ID="your_google_client_id"
GOOGLE_CLIENT_SECRET="your_google_client_secret"
NEXT_PUBLIC_APP_URL="http://localhost:3000"

# Database
MONGODB_URI="your_mongodb_connection_string"

# File Storage (Pinata)
PINATA_JWT="your_pinata_jwt"
NEXT_PUBLIC_GATEWAY_URL="your_pinata_gateway_url"

# Payments (Paddle)
NEXT_PUBLIC_PADDLE_CLIENT_TOKEN="your_paddle_client_token"
PADDLE_API_KEY="your_paddle_api_key"
PADDLE_PRODUCT_ID="your_paddle_product_id"
PADDLE_SUBSCRIPTION_WEBHOOK_SECRET_KEY="your_paddle_webhook_secret"


Run the development server:

bun run dev


Access the app:
Open your browser and visit 👉 http://localhost:3000

💡 Future Enhancements

🔒 End-to-End Encryption – Implement client-side encryption for zero-knowledge file security.

👥 Team Collaboration – Enable shared team drives and collaborative workspaces.

📂 File Previews – Support document, image, and video previews directly in the browser.

🔍 Intelligent Search – Integrate semantic search to locate files by name or content.

📱 Mobile Optimization – Enhance responsiveness for mobile-first access.

📬 Contact

For questions, feedback, or collaboration opportunities, feel free to reach out:

Author: Ankit Kumar

This project is licensed under the MIT License — see the LICENSE
 file for details.
