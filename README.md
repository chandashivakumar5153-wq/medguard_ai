# MedGuard AI: Medicine Label Detector

An AI-powered tool to identify potentially counterfeit medicine packaging by analyzing labels for inconsistencies, typos, and regulatory marks.

## 🚀 Deployment to GitHub Pages

This project is configured for easy deployment to GitHub Pages using GitHub Actions.

### Steps to Deploy:

1. **Create a GitHub Repository**: Create a new repository on GitHub and push this code to the `main` branch.
2. **Set up API Key**:
   - Go to your GitHub repository **Settings** > **Secrets and variables** > **Actions**.
   - Click **New repository secret**.
   - Name: `GEMINI_API_KEY`
   - Value: Your Google Gemini API Key (get one from [Google AI Studio](https://aistudio.google.com/)).
3. **Enable GitHub Pages**:
   - Go to **Settings** > **Pages**.
   - Under **Build and deployment** > **Source**, select **GitHub Actions**.
4. **Push Changes**: Any push to the `main` branch will now automatically trigger the deployment workflow.

## 🛠 Tech Stack

- **React 19** + **TypeScript**
- **Vite** (Build tool)
- **Tailwind CSS 4** (Styling)
- **Framer Motion** (Animations)
- **Lucide React** (Icons)
- **Google Gemini API** (AI Analysis)

## ⚠️ Disclaimer

MedGuard AI is an experimental tool for informational purposes only. It is not a substitute for professional pharmaceutical verification. Always purchase medication from licensed pharmacies.
