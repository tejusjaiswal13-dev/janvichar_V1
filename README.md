# JanVichar - Indian PIL Filing Portal

JanVichar is a modern platform designed for Indian citizens to collaboratively draft, track, and manage Public Interest Litigations (PILs). Built for the hackathon, it empowers users to raise their voices and shape a better India.

## Features

- **Google Authentication:** Secure login using Firebase Auth.
- **PIL Creation:** Simple form to file PILs with AI-powered draft validation.
- **Real-time Tracker:** Live list of all filed PILs with up-vote functionality.
- **Sorting/Filtering:** Sort PILs by Trending, Hot, or Newest.
- **PDF Export:** Generate and download a PDF version of your PIL draft.
- **Gemini AI Integration:** Get instant feedback and suggestions for your PIL draft.
- **Upvote & Share:** Support other PILs and share them on social media.

## Tech Stack

- **Frontend:** Next.js 14 (App Router), TypeScript, Vanilla CSS.
- **Backend:** Firebase (Authentication, Firestore).
- **AI:** Google Gemini API (@google/generative-ai).
- **Tools:** jsPDF, Lucide React.

## Getting Started

### Prerequisites

- Node.js installed.
- A Firebase project.
- A Google Gemini API Key.

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd JanVichar
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables:
   Create a `.env.local` file in the root directory and add your keys:
   ```env
  
   ```

4. Run the development server:
   ```bash
   npm run dev
   ```

Open  https://janvichar.vercel.app/  to see the result.

## Deployment

This project is ready to be deployed to **Vercel**. Simply push your code to a GitHub repo and connect it to Vercel. Don't forget to add your environment variables in the Vercel dashboard.

## License

This project is for hackathon purposes. Use responsibly.
