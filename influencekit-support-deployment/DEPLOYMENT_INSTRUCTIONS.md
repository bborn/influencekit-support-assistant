# InfluenceKit Support Assistant - Deployment Instructions

## Quick Deployment Options

### Option 1: Vercel (Recommended - Free & Easy)

1. **Sign up for Vercel**: Go to [vercel.com](https://vercel.com) and sign up with GitHub
2. **Upload files**: 
   - Drag and drop the entire `influencekit-support-deployment` folder to Vercel
   - Or use Vercel CLI: `npx vercel --prod`
3. **Get your URL**: Vercel will provide a permanent URL like `https://your-app.vercel.app`

### Option 2: Netlify (Also Free & Reliable)

1. **Sign up for Netlify**: Go to [netlify.com](https://netlify.com)
2. **Drag & Drop Deploy**: 
   - Drag the `influencekit-support-deployment` folder to the Netlify deploy area
3. **Get your URL**: Netlify will provide a permanent URL like `https://your-app.netlify.app`

### Option 3: GitHub Pages (Free with GitHub)

1. **Create GitHub repository**: Create a new repository on GitHub
2. **Upload files**: Upload all files from `influencekit-support-deployment` to the repository
3. **Enable Pages**: Go to Settings > Pages > Deploy from branch > main
4. **Get your URL**: GitHub will provide a URL like `https://username.github.io/repository-name`

### Option 4: Your Own Web Hosting

If you have existing web hosting (cPanel, FTP, etc.):
1. Upload all files from `influencekit-support-deployment` to your web server's public folder
2. Access via your domain

## Files Included

- `index.html` - Main application file
- `assets/` - CSS, JavaScript, and other assets
- `favicon.ico` - Website icon

## Important Notes

⚠️ **API Key Security**: The OpenAI API key is currently embedded in the client-side code. For production use, consider:
- Setting up environment variables on your hosting platform
- Using a backend service to proxy API calls
- Monitoring API usage to prevent abuse

✅ **Features Included**:
- AI-powered support guidance
- Real-time question answering
- Mobile-responsive design
- Conversation history
- Professional interface

## Support

The application is ready to use immediately after deployment. Your support representatives can:
1. Bookmark the deployed URL
2. Ask questions in natural language
3. Get instant, detailed guidance based on your support procedures

## Recommended: Vercel Deployment

For the easiest deployment experience, we recommend Vercel:
1. It's completely free for this use case
2. Automatic HTTPS
3. Global CDN for fast loading
4. Easy updates by re-uploading files

Your permanent URL will be available within minutes!

