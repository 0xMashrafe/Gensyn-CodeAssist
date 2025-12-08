# Run CodeAssist on Octa-Space (currently on progress)
This guide shows you the easiest way to run CodeAssist on Octa using a single command (copy-paste friendly)

<img src="images/codeassist.png" width="60%">

## Step 1: Create Your HuggingFace Token

<p align="center">
  <img src="images/codeassist-step2.png" width="70%">
</p>

To run CodeAssist, you'll need a HuggingFace access token.

1. Go to: https://huggingface.co  
2. Sign in → Click your **Profile**  
3. Open **Settings → Access Tokens**  
4. Click **New Token**  
5. Set:
   - **Name:** CodeAssist (for example)  
   - **Permissions:** Write (must)  
6. Click **Create**  
7. Copy the token immediately and keep it safe. (you won’t be able to see it again)


---

## 📑 Table of Contents
- [Quick Setup (1-Command Install)](#quick-setup-1-command-install)
- [Step-by-Step Slides](#step-by-step-slides)
  - [Step 1 — Create HuggingFace Token](#step-1--create-huggingface-token)
  - [Step 2 — Deploy Octa Instance](#step-2--deploy-octa-instance)
  - [Step 3 — Configure Your Node](#step-3--configure-your-node)
  - [Step 4 — Run the Auto-Installer](#step-4--run-the-auto-installer)
  - [Step 5 — Open CodeAssist Web UI](#step-5--open-codeassist-web-ui)
- [Important Notes](#important-notes)
- [Credits](#credits)

---

## ⚡ Quick Setup (1-Command Install)

Once your Octa instance is deployed (steps below),  
run this command inside **Web SSH**:

```bash
curl -LsSf https://files.octa.space/codeassist | bash
