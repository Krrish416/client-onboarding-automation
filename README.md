# Client Onboarding Automation (n8n + Google Workspace)

This is a complete no-code automation built using **n8n** and **Google Workspace** tools — designed to automate the entire client onboarding process from form submission to personalized PDF contract delivery via email.

> Created by **Krrish Gupta** — automation enthusiast focused on solving real-world problems using smart, low-code workflows.

---

## 🚀 What It Does

✅ Collects client details using **Google Forms**  
✅ Saves responses in **Google Sheets**  
✅ Automatically copies a **Google Docs template**  
✅ Dynamically fills the document with client info  
✅ Converts the doc to **PDF**  
✅ Sends the contract to the client via **Gmail**

---

## 🛠 Tools Used

- **n8n** (automation engine)
- **Google Forms**
- **Google Sheets**
- **Google Docs**
- **Google Drive**
- **Gmail**

---

## ⚙️ Workflow Overview

1. **Google Sheets Trigger**  
   Watches for new Google Form submissions

2. **Google Drive → Copy File**  
   Duplicates the onboarding contract template

3. **Google Docs → Update Document**  
   Replaces placeholders like `{{name}}` with real data

4. **Google Drive → Download File (PDF)**  
   Converts the filled document into a PDF

5. **Gmail → Send Email**  
   Sends a personalized email with the contract attached

---

## 📄 Files in This Repo

| File | Description |
|------|-------------|
| `My_workflow.json` | Exported n8n workflow file |
| `README.md` | You're reading it :) |

---

## 🔧 How to Use

1. Import the workflow into n8n
2. Connect your **Google OAuth credentials**
3. Replace the template ID and folder IDs as needed
4. Customize the Google Docs template placeholders
5. Activate and test with a Google Form submission

---

## 👋 About the Creator

Hi! I'm **Krrish Gupta**, a self-taught automation builder using tools like n8n, Python, and AI to solve business problems.  
You can reach out to me for:
- Workflow design
- Automation consulting
- Freelance no-code projects

---

## 📬 Contact

- GitHub: [@yourusername](https://github.com/yourusername)
- LinkedIn: *(Add your link here if you'd like)*
- Email: *(Optional)*

---

## 🏷 License

This project is open-source and free to use. Attribution appreciated 🙌
