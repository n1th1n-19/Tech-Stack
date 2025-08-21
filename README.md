# AI Research Paper Summarizer - Tech Stack

## Frontend Stack
- **React.js** - Main UI framework
- **React Router** - Navigation
- **Axios** - API calls
- **Tailwind CSS** - Styling framework
- **React Context API** - State management

## Backend Stack
- **Node.js** - Runtime environment
- **Express.js** - Web framework
- **Multer** - File upload handling
- **CORS** - Cross-origin resource sharing
- **helmet** - Security headers
- **morgan** - HTTP request logging

## Authentication
- **JWT (jsonwebtoken)** - Token-based auth
- **Google OAuth 2.0** - Social login
- **passport.js** - Authentication middleware
- **passport-google-oauth20** - Google strategy
- **bcrypt** - Password hashing

## Database Options

### Option 1: Supabase (Recommended)
- **PostgreSQL** - Primary database
- **Supabase pgvector** - Vector storage
- **Supabase Storage** - File storage
- **Free Tier**: 500MB database, 1GB storage

### Option 2: MongoDB Atlas
- **MongoDB** - Document database
- **Mongoose** - Object modeling
- **Pinecone** - Vector database (1M vectors free)
- **Free Tier**: 512MB cluster

## AI Services
- **OpenAI API** - GPT models for summarization & chat
- **Cohere API** - Alternative NLP service (generous free tier)
- **Hugging Face Inference API** - Open-source models

## File Processing
- **pdf-parse** - PDF text extraction
- **mammoth** - Microsoft Word (.docx) processing
- **xlsx** - Excel spreadsheet processing
- **file-type** - File type detection

## Storage Solutions
- **Cloudinary** - Document storage (free tier)
- **Supabase Storage** - If using Supabase

## Hosting (Free Tiers)
### Frontend
- **Vercel** - React app deployment
- **Netlify** - Alternative hosting

### Backend
- **Railway** - Full-stack hosting
- **Render** - Web service hosting
- **Supabase Edge Functions** - Serverless functions

### CDN & Domain
- **Cloudflare** - CDN and DNS (free tier)
