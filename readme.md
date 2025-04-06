# Deployment Instructions for SynthEDU

This guide will walk you through deploying your SynthEDU project to Koyeb, Vercel, and Hop.sh.

## Prerequisites

Before you begin, ensure that you have the following:

- A GitHub account and a repository with your project code.
- A Koyeb, Vercel, or Hop.sh account (depending on where you want to deploy).
- Git installed on your local machine (if you're deploying from local files).

---

## Deploying to Koyeb

1. **Sign up / Log in to Koyeb:**
   - Go to [Koyeb](https://www.koyeb.com) and sign up or log in to your account.

2. **Connect Your GitHub Repository:**
   - On your Koyeb dashboard, click on **Create App**.
   - Select **GitHub** and authorize Koyeb to access your repository.
   - Choose your repository containing the SynthEDU project.

3. **Configure Your App:**
   - Set the runtime (e.g., **Node.js**, **Static Site**, etc.) depending on your project.
   - Make sure Koyeb pulls the right branch if you're using multiple branches.

4. **Deploy the App:**
   - Click on **Deploy** to initiate the process.
   - After the deployment is complete, Koyeb will provide a URL for your live site.

For more information on Koyeb deployment, visit [Koyeb Docs](https://docs.koyeb.com/).

---

## Deploying to Vercel

1. **Sign up / Log in to Vercel:**
   - Go to [Vercel](https://vercel.com) and sign up or log in.

2. **Import Your GitHub Repository:**
   - On the Vercel dashboard, click on **New Project**.
   - Choose **GitHub** and select your SynthEDU repository.

3. **Configure Your Project:**
   - Choose the correct framework or set it as **Static Site** if your project is just HTML/CSS/JS.
   - Set up any environment variables if needed (e.g., API keys).

4. **Deploy:**
   - Click on **Deploy** to begin the deployment process.
   - Vercel will give you a URL after the deployment is complete.

For more details on Vercel deployment, check [Vercel Docs](https://vercel.com/docs).

---

## Deploying to Hop.sh

1. **Sign up / Log in to Hop.sh:**
   - Go to [Hop.sh](https://hop.sh) and sign up or log in.

2. **Connect Your GitHub Repository:**
   - On the Hop.sh dashboard, click **Create a new project**.
   - Select **GitHub** and authorize Hop.sh to access your repository.
   - Pick the repository containing the SynthEDU project.

3. **Configure the Project:**
   - Choose the correct runtime or framework for your project.
   - Set up any necessary environment variables (e.g., for API keys or custom settings).

4. **Deploy the Application:**
   - Click **Deploy** and Hop.sh will begin the process.
   - Once deployed, Hop.sh will provide a link to your live project.

For further details on Hop.sh deployment, visit [Hop.sh Docs](https://docs.hop.sh).

---

## Troubleshooting

If you run into any issues during deployment, here are some common solutions:

- **Check your environment variables:** Ensure that any API keys or settings are correctly configured.
- **Ensure the right runtime is selected:** Make sure your project is set up with the correct runtime (e.g., Node.js, static site).
- **Verify your repository:** Ensure that your GitHub repository is connected properly and that you have access to the branch you're deploying.

If you need further help, feel free to reach out at our discord or check the deployment platform's documentation.

