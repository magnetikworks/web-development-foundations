# Deployment Steps
Choose one of the below options to deploy your web pages after committing to your GitHub account.

## 1.1 Deploy to Vercel
    1. Prepare: Ensure your main entry point is named index.html at the root of your project.
    2. Push: Commit and push all final changes to your GitHub repository.
    3. Connect: Log into Vercel using your GitHub account.
    4. Import: Click "Add New Project" and select your portfolio repository.
    5. Deploy: Click "Deploy." Vercel will provide a URL (e.g., my-portfolio.vercel.app).
    6. Continuous Integration: Make a small change to your CSS, push to GitHub, and watch Vercel automatically update your live site.

## 1.2 Deploy to GitHub Pages
    1. Prepare  Ensure your main entry point is named `index.html` and is located at the root of your project.
    2. Push Commit and push all final changes to your GitHub repository (usually the `main` branch).
    3. Open Repository Settings  Navigate to your GitHub repository and click Settings → Pages.
    4. Configure Pages Source  Under Source:
      - Select Branch: `main`
      - Select Folder: `/ (root)`
      - Click Save
    5. Deploy  GitHub Pages will automatically build and deploy your site.
    6. Access URL Your site will be available at: `https://<your-username>.github.io/<repository-name>/`

## 1.3 Deploy to Netlify
    1. Prepare  Ensure your project contains an `index.html` file at the root (no build step required for simple HTML projects).
    2. Push  Commit and push all final changes to your GitHub repository.
    3. Log In  Visit <https://www.netlify.com> and log in using your GitHub account.
    4. Create New Site  Click Add new site → Import an existing project.
    5. Connect Repository 
      - Choose GitHub as your Git provider.
      - Select your project repository.
    6. Configure Build Settings
      - Build command: (leave empty)
      - Publish directory: `/` (root)
    7. Deploy  Click Deploy site. Netlify will build and publish your site automatically.
    8. Access URL  Netlify will generate a live URL such as: `https://your-site-name.netlify.app`
