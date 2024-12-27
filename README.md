# CEKA - Civic Education Kenya App

Welcome to the official repository of **CEKA** (Civic Education Kenya App), an open-source initiative to enhance civic knowledge and engagement in Kenya. This platform is designed to bridge gaps in legislative transparency and empower citizens with the information they need to drive civic action.

## Project Vision
CEKA aims to provide a decentralized, secure, and user-friendly application that promotes civic education. By leveraging cutting-edge technology, CEKA seeks to:
- Bridge the informational divide in civic matters.
- Enhance public participation in legislative processes.
- Offer a reliable and censorship-resistant platform for civic engagement.

## Core Features
### 🛠️ Phase 1: Foundation
- **Offline Access:** IndexedDB and SQLite integration for offline functionality.
- **Secure Authentication:** Decentralized Identity (DID) and multi-factor authentication support.
- **Progressive Data Download:** Efficient storage and bandwidth use.

### 📡 Phase 2: Content Distribution
- **Decentralized Data:** IPFS implementation for immutable content storage.
- **Real-Time Sync:** CRDT architecture for conflict-free data updates.

### 🔒 Phase 3: Security Implementation
- **Data Encryption:** End-to-end encryption using ChaCha20-Poly1305.
- **Trust Verification:** Role-based access control and trust scoring mechanisms.

### 🌍 Phase 4: Resilience Features
- **Offline First:** Document caching and state persistence.
- **Anti-Censorship:** Domain fronting and bridge relay systems for secure content delivery.

## Tech Stack
### **Front End**
- [React Native](https://reactnative.dev/) - Cross-platform app development.
- [Tailwind CSS](https://tailwindcss.com/) - Modern utility-first CSS framework.
- [React Navigation](https://reactnavigation.org/) - Intuitive navigation for React Native.

### **Back End**
- [Node.js](https://nodejs.org/) - Server environment.
- [Express.js](https://expressjs.com/) - Backend framework.
- [GraphQL](https://graphql.org/) - Efficient data querying.
- [Supabase](https://supabase.com/) - Database and authentication services.

### **Database**
- [PostgreSQL](https://www.postgresql.org/) via Supabase for primary storage.
- [SQLite](https://www.sqlite.org/) for local, offline-first storage.

### **Security**
- [DIDs](https://www.w3.org/TR/did-core/) for decentralized identity.
- [ChaCha20](https://tools.ietf.org/html/rfc8439) for encryption.
- [Argon2id](https://github.com/P-H-C/phc-winner-argon2) for password hashing.

## Contribution Guidelines
We welcome contributions from developers, civic educators, and anyone passionate about bridging knowledge gaps in civic education. Here's how you can contribute:
1. **Fork the Repository:** Start by forking this repository.
2. **Explore Issues:** Look through open issues and find one you can contribute to.
3. **Submit a PR:** Make your changes and submit a pull request for review.

## Getting Started
### Prerequisites
- Node.js and npm installed
- Git installed on your machine
- Basic knowledge of React Native and backend frameworks

### Installation Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/ceka.git
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm start
   ```

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For inquiries, support, or collaboration opportunities:
- **Email:** [civiceducationke@gmail.com](mailto:civiceducationke@gmail.com)
- **Social Media:** Follow us on [Twitter](https://x.com/civicedkenya) and [Facebook](https://facebook.com/CivicEdKenya).

---

Thank you for your interest in CEKA. Together, we can build a platform that empowers citizens and fosters a more informed and active society.
