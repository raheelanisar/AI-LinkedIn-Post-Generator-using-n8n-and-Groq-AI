
# 🤖 AI LinkedIn Post Generator using n8n & Groq AI

## 📌 Project Overview

The **AI LinkedIn Post Generator** is an automation workflow built using **n8n** and **Groq AI**. It automatically generates professional LinkedIn posts based on a user-provided topic, saves the content to Google Sheets, and sends it via Gmail.

---

## 🚀 Features

- ✅ AI-generated LinkedIn title
- ✅ Professional LinkedIn post
- ✅ Automatic hashtag generation
- ✅ Google Sheets integration
- ✅ Gmail integration
- ✅ Automatic date and time
- ✅ Easy topic customization

---

## 🛠️ Technologies Used

- n8n
- Groq AI
- JavaScript
- Google Sheets API
- Gmail API
- Google OAuth

---

## 📂 Workflow

```text
Manual Trigger
      │
      ▼
Edit Fields (Topic)
      │
      ▼
AI Agent (Groq)
      │
      ▼
Code (JavaScript)
      │
      ▼
Google Sheets
      │
      ▼
Gmail
```

---

## 📋 How It Works

1. Enter a topic in the **Edit Fields** node.
2. Execute the workflow.
3. The AI Agent generates:
   - Professional Title
   - LinkedIn Post
   - Relevant Hashtags
4. The JavaScript Code node parses the AI response.
5. The generated content is saved in Google Sheets.
6. The final LinkedIn post is automatically sent via Gmail.

---

## 📁 Project Structure

```text
AI_LinkedIn_Post_Generator/
│
├── workflow.json
├── README.md
├── project_notes.docx
└── screenshots/
    ├── workflow.png
    ├── ai_output.png
    ├── google_sheet.png
    ├── gmail.png
    └── execution.png
```

---

## 📸 Screenshots

Add screenshots of:

### Complete Workflow
<img width="639" height="319" alt="image" src="https://github.com/user-attachments/assets/d95b6f06-eb10-413e-b32c-98744c7c7cd8" />
### AI Agent Output
<img width="640" height="311" alt="image" src="https://github.com/user-attachments/assets/3e07542f-18b5-41fa-a83c-bfd9b9a577dc" />
### Google Sheets Output
<img width="640" height="311" alt="image" src="https://github.com/user-attachments/assets/f34b157f-2793-44bc-964e-671e8a664b64" />
### Gmail Output
<img width="640" height="316" alt="image" src="https://github.com/user-attachments/assets/07d22def-bffc-4dfc-9466-db9e5febbe98" />
### Workflow Execution
<img width="640" height="319" alt="image" src="https://github.com/user-attachments/assets/55562d56-c0d8-4187-ad75-c47fa88ef6df" />
<img width="640" height="295" alt="image" src="https://github.com/user-attachments/assets/3c20a932-ea12-44f6-883d-bfc605961d18" />

---

## 🎯 Learning Outcomes

After completing this project, I learned:

- AI Workflow Automation
- Prompt Engineering
- Groq AI Integration
- JavaScript Data Processing
- Google Sheets Automation
- Gmail Automation
- API Integration
- Workflow Debugging

---

## 🔮 Future Improvements

- Replace manual topic input with a web form
- Publish directly to LinkedIn
- Add AI image generation
- Support multiple social media platforms
- Schedule automatic post generation

---

## 👩‍💻 Developed By

**Raheela Nisar**

---

## 📄 License

This project is developed for educational and portfolio purposes.
