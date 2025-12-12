# Student Exam Slip Search

A high-end, professional React component for searching and displaying student exam slips by roll number. Built as a single HTML file for easy deployment.

## Features

- **Instant Search**: Real-time filtering by roll number
- **Beautiful UI**: Modern, professional design with smooth animations
- **Responsive**: Works perfectly on mobile, tablet, and desktop
- **Zero Build Step**: Single HTML file - ready to deploy

## Deployment on Vercel

### Option 1: Direct File Upload (Easiest)

1. Go to [vercel.com](https://vercel.com) and sign in
2. Click "Add New..." → "Project"
3. Click "Browse" and select the `index.html` file
4. Deploy!

### Option 2: Git Repository

1. Create a new repository on GitHub
2. Push the `index.html` file to the repository
3. Import the repository on Vercel
4. Vercel will automatically detect and deploy it

### Option 3: Vercel CLI

```bash
npm i -g vercel
vercel
```

## Local Testing

Simply open `index.html` in your web browser - no server needed!

Or use a local server:

```bash
# Python
python -m http.server 8000

# Node.js
npx serve

# PHP
php -S localhost:8000
```

Then visit `http://localhost:8000`

## Sample Roll Numbers

Try searching for these roll numbers:
- `25K-5570`
- `19K-0221`
- `22K-3345`
- `24K-7890`
- `21K-4567`
- `23K-1122`

## Technologies Used

- React 18 (via CDN)
- Tailwind CSS (via CDN)
- Lucide React Icons (via CDN)
- Babel Standalone (for JSX transformation)

## License

Free to use and modify.

