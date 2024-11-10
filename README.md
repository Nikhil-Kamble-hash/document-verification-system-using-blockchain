# document-verification-system-using-blockchain
This is a Document Verification System that uses blockchain technology to verify and track document authenticity. Here's a breakdown of its key features and components:

Core Functionality:

Users can upload documents to be verified and stored on the blockchain
Each document gets hashed using SHA-256 encryption
Documents are stored in blocks with proof-of-work verification
Complete blockchain explorer to view all verified documents
Real-time verification results

Main Components:

FileUpload: Modern drag-and-drop interface for document uploads
BlockchainExplorer: Visual display of the entire blockchain, showing:
Block number and timestamp
Document name and owner
Block hashes and previous block references
VerificationResult: Real-time feedback on document verification status

Security Features:

Cryptographic hashing (SHA-256) for document fingerprinting
Proof-of-work system requiring blocks to have hashes starting with "00"
Immutable chain of blocks, each referencing the previous block
Transparent verification process

Technical Implementation:

Built with React and TypeScript for type safety
Uses CryptoJS for secure hashing
Responsive design with Tailwind CSS
Lucide React icons for modern UI elements
User Experience:

Clean, intuitive interface
Real-time feedback on document verification
Visual blockchain explorer for transparency
Responsive design that works on all devices

The system is currently deployed and live, making it ready for production use. While this is a simplified version of blockchain technology, it demonstrates the core concepts of document verification using blockchain principles.

Note: In a production environment, this would typically be enhanced with:

User authentication
Persistent storage
Network consensus mechanisms
More robust proof-of-work algorithms
Additional security measures
