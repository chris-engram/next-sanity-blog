# Next.js Sanity Blog

A modern blog built with Next.js and Sanity CMS.

## Features
- Next.js 14 with App Router
- Sanity CMS for content management
- TypeScript support
- Tailwind CSS for styling
- SEO optimized

## Getting Started

### Prerequisites
- Node.js 18+ 
- npm or yarn
- Sanity account

### Installation

1. Install dependencies:
```bash
npm install
```

2. Set up environment variables:
```bash
cp .env.example .env.local
```

3. Configure Sanity:
- Update `.env.local` with your Sanity project ID and dataset

4. Run development server:
```bash
npm run dev
```

## Project Structure
```
├── app/              # Next.js app directory
├── components/       # React components
├── lib/             # Utility functions and configs
├── public/          # Static assets
├── sanity/          # Sanity studio and schemas
└── styles/          # Global styles
```

## License
MIT