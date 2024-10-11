# FSJ 3

## Introduction

Welcome to **FSJ 3**, a project designed to [brief description of your project].

## Technologies Used

- [Next.js](https://next.js/?form=MG0AV3)
    
- Firebase (Firestore, Auth)
    
- React
    
- CSS/SCSS
    

## Setup Instructions

### Prerequisites

- [Node.js](https://node.js/?form=MG0AV3)
    
- npm
    
- Firebase project
    

### Installation

1. **Clone the repository:**
    
    bash
    
    Copy
    
    ```
    git clone https://github.com/yourusername/your-repo.git
    cd your-repo
    ```
    
2. **Install dependencies:**
    
    bash
    
    Copy
    
    ```
    npm install
    ```
    
3. **Create** `.env.local` **with Firebase config:**
    
    env
    
    Copy
    
    ```
    NEXT_PUBLIC_FIREBASE_API_KEY=your-api-key
    NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your-auth-domain
    NEXT_PUBLIC_FIREBASE_PROJECT_ID=your-project-id
    NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your-storage-bucket
    NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your-messaging-sender-id
    NEXT_PUBLIC_FIREBASE_APP_ID=your-app-id
    ```
    
4. **Run the development server:**
    
    bash
    
    Copy
    
    ```
    npm run dev
    ```
    
5. **Open your browser at:**
    
    plaintext
    
    Copy
    
    ```
    http://localhost:3000
    ```
    

## Usage

### Authentication

Sign up, sign in, and sign out functions are managed with Firebase Authentication. The current auth state is displayed on the frontend using `AuthContext`.

### Adding a Review

Users can add and display reviews for products. Reviews include rating and comment fields.
