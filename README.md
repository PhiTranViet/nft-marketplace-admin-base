# NFT Marketplace Admin Frontend

This is the admin panel frontend for managing the NFT Marketplace. It provides an interface for administrators to oversee and manage marketplace operations such as user management, NFT listings, transaction reviews, and platform analytics.

## 🚀 Features

- **Dashboard**: Overview of marketplace activity, including sales volume, active users, and top-performing NFTs.
- **User Management**: Admins can view, suspend, or delete users and their respective NFT listings.
- **NFT Listing Management**: Ability to approve or reject newly minted NFTs, and monitor ongoing sales.
- **Transaction Management**: Review, approve, or flag transactions for manual review.
- **Analytics**: Visualize key performance indicators such as revenue, transaction volumes, and growth metrics.
- **Real-Time Notifications**: Instant alerts for important events like new listings, transactions, or user activity.
- **Role-Based Access Control (RBAC)**: Ensure that only authorized personnel can access specific features.

## 🛠️ Technologies Used

- **Next.js**: A powerful React framework for server-side rendering and static site generation.
- **Tailwind CSS**: A utility-first CSS framework for rapid UI development.
- **Redux**: State management library for handling the application state.
- **Socket.IO**: Real-time communication for live updates of transactions and listings.
- **Ethers.js**: Interaction with the Ethereum blockchain for managing NFTs and payments.
- **Axios**: HTTP client for handling API requests.
- **Docker**: Containerization to ensure consistent development and production environments.

## 📂 Project Structure

```bash
admin-frontend/
│
├── public/            # Static assets (images, fonts, etc.)
├── src/
│   ├── components/    # Reusable UI components
│   ├── pages/         # Admin pages (dashboard, users, NFTs, etc.)
│   ├── redux/         # Redux store and slices for state management
│   ├── services/      # API and blockchain service integrations
│   ├── styles/        # Global and page-specific styles
│   └── utils/         # Utility functions
├── .env               # Environment variables (API keys, endpoints, etc.)
├── next.config.js     # Next.js configuration
└── Dockerfile         # Dockerfile for admin frontend


... ... ... ... ... ... Todo
```
## 📦 Installation
1.	Clone the repository:
```bash
git clone https://github.com/PhiTranViet/nft-marketplace-admin-base.git
cd nft-marketplace-admin-base
```
2.	Install dependencies:
```bash
npm install
```
3.	Set up environment variables:
```bash
Create a .env file in the root of the project and configure the following variables:
NEXT_PUBLIC_API_URL=http://localhost:3000/api
NEXT_PUBLIC_KAFKA_BROKER_URL=kafka://localhost:9092
NEXT_PUBLIC_SOCKET_URL=http://localhost:3000
```
4.	Start the development server:
```bash
npm run dev
```
5.	Build the application for production:
```bash
npm run build
```

## 📊 Key Features

	•	User Management: Admins can view, edit, or suspend users, and review their NFT listings.
	•	NFT Monitoring: Approve or reject NFTs and manage ongoing auctions or sales.
	•	Blockchain Integration: Real-time updates on blockchain transactions using Ethers.js.
	•	Real-Time Notifications: Receive alerts on significant marketplace events using Socket.IO.
	•	Role-Based Access: Manage user roles and permissions with RBAC.
	•	Analytics: Visualize important data such as revenue, NFT trends, and user activity.

## 🤝 Contribution

We welcome contributions from the community! Please follow the guidelines below:

	1.	Fork the repository.
	2.	Create a new feature branch (git checkout -b feature/new-feature).
	3.	Commit your changes (git commit -m 'Add some feature').
	4.	Push to the branch (git push origin feature/new-feature).
	5.	Open a Pull Request.