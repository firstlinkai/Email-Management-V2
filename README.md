# AI-Powered Email Management – Version 2

Built with **n8n**, **OpenAI (ChatGPT)**, and **Gmail**.

---

## 🔄 What’s New in Version 2

After sharing [[Version 1](https://github.com/firstlinkai/N8N_Email_Management)), I rebuilt the workflow from the ground up to make it cleaner, faster, and easier to maintain.

### ✅ Improvements:
- 🧠 **Single AI Agent** – One step handles classification, summarization, and reply drafting.
- 🏷️ **Dynamic Labeling** – No more hardcoded label IDs.
- ✉️ **Gmail Drafts** – AI-generated replies are saved directly as drafts.
- 🧩 **Simplified Workflow** – Fewer nodes with smarter logic and easier debugging.

It's now easier to scale, adapt, and maintain.

---

## 💡 Common Question

**“Can this work with other email providers?”**  
Yes – the AI logic is platform-independent.

If you're not using Gmail, just replace Gmail-specific nodes with:
- **IMAP/SMTP** connections
- Or your provider’s **API**

The AI classification, summaries, and replies still work the same.

---

## 🛠️ Tools Used
- [n8n](https://n8n.io/)
- [OpenAI](https://openai.com/)
- Gmail (can be swapped with other email providers)

---

## 📎 License

Feel free to copy, modify, or improve on this workflow. Attribution appreciated but not required.
