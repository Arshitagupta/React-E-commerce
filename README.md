# React-E-commerce

## Deployment on Vercel

This project is ready to be deployed on Vercel. There are two ways to deploy:

### Method 1: Deploy via Vercel Website (Recommended)

1. Push your code to GitHub/GitLab/Bitbucket
2. Go to [vercel.com](https://vercel.com)
3. Sign up or log in with your GitHub account
4. Click "Add New Project"
5. Import your repository
6. Vercel will automatically detect it's a Create React App project
7. Click "Deploy" - no configuration needed!

### Method 2: Deploy via Vercel CLI

1. Install Vercel CLI:
   ```bash
   npm install -g vercel
   ```
   Or use npx (no installation needed):
   ```bash
   npx vercel
   ```

2. Deploy to production:
   ```bash
   npm run deploy
   ```
   Or:
   ```bash
   vercel --prod
   ```

3. Follow the prompts to link your project to Vercel

### Configuration

The project includes a `vercel.json` file that configures:
- Build command: `npm run build`
- Output directory: `build`
- Routing: All routes redirect to `index.html` for React Router

### Notes

- The first deployment will create a preview URL
- Production deployment will create a permanent URL
- Vercel automatically detects Create React App and sets up the build configuration
- All future pushes to your main branch will trigger automatic deployments