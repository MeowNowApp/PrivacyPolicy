# MeowNow Privacy Policy Site

Simple static site hosting the MeowNow privacy policy for App Store compliance.

## Deploy to Vercel

1. Install Vercel CLI (if not already installed):
   ```bash
   npm install -g vercel
   ```

2. Navigate to this directory:
   ```bash
   cd /Users/wbreiler/Developer/MeowNow/privacy-site
   ```

3. Deploy:
   ```bash
   vercel
   ```

4. Follow the prompts:
   - Set up and deploy? **Y**
   - Which scope? (select your account)
   - Link to existing project? **N**
   - What's your project's name? **meownow-privacy**
   - In which directory is your code located? **.**

5. Your site will be live at: `https://meownow-privacy.vercel.app`

6. For production deployment:
   ```bash
   vercel --prod
   ```

## Update Privacy Policy

Edit `public/index.html` and redeploy with `vercel --prod`.

## URL for App Store

Use the production URL in your App Store Connect privacy policy field:
`https://meownow-privacy.vercel.app`

Or set up a custom domain in Vercel settings.