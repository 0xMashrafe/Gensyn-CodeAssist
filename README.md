# Gensyn-CodeAssist (currently on progress)
This guide shows you the easiest way to run CodeAssist on Octa using a single command (copy-paste friendly)
# 🚀 CodeAssist on Octa — Minimal Setup Guide

This repository provides the simplest and cleanest guide for running **CodeAssist** on **Octa**, designed for beginners and non-technical users.

You can use **any GPU instance** on Octa —  
(Recommendation: RTX 3090 or higher for smoother experience.)

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
