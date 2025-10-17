# FETSCR Version 1 - No-Code Web Scraping Automation

[https://www.fetscr.in/](https://www.fetscr.in/)

## Overview
**FETSCR Version 1** is a no-code web scraping automation tool built using **n8n**.  
It allows users to extract, organize, and manage web data effortlessly for lead generation, business intelligence, and more—without coding.

---

## Features
- Visual **No-Code Workflow Builder**
- Integrations: LinkedIn, Max, Myntra, Zomato, Indeed, Unstop, GeeksforGeeks
- Export scraped data: CSV, JSON, or Google Sheets
- Scheduled automated workflows
- Upgraded UI for total visibility and control
- Beta workflows available for testing

---

## Version
- **v1 (n8n-based)**: Core scraping and automation capabilities  
- **v2 (upcoming)**: Advanced UI, faster scraping, intelligent automation

---

## Screenshots

**Workbench Dashboard:**  
[![Workbench Dashboard](https://framerusercontent.com/images/XD6HgZm7Rw2znvnXwR3O1aNFRM.png?scale-down-to=1024)](https://framerusercontent.com/images/XD6HgZm7Rw2znvnXwR3O1aNFRM.png?scale-down-to=1024)

**Example Workflow:**  
[![Example Workflow](https://framerusercontent.com/images/h9prinz0SiFA0M5tz9opYoMvodo.png)](https://framerusercontent.com/images/h9prinz0SiFA0M5tz9opYoMvodo.png)

---

## Getting Started

### Access
1. Visit [FETSCR](https://www.fetscr.in/)  
2. Sign up or log in  
3. Open **Workbench** to start creating workflows

### Example Workflow
1. Create a workflow to scrape LinkedIn job listings  
2. Select fields: Job Title, Company, Location, Post Date  
3. Add a **Google Sheets node** to export results  
4. Schedule it to run daily automatically

### Managing Workflows
- **View**: Monitor workflow status and output  
- **Edit**: Update workflows anytime  
- **Delete**: Remove outdated workflows

---

## How to Use in n8n

## Requirements
Before starting, ensure you have the following:

- **n8n Cloud account**  
  - To run and automate workflows in the cloud without self-hosting  
  - Sign up at [n8n.io](https://n8n.io/)  

- **Google Cloud Console project** with:  
  - **Programmable Search Engine** enabled (for web searches)  
  - **API Key generated** (for authentication)  

- **Google Sheet** for storing results  
  - Columns: `Name`, `Company`, `Profile URL`  

---

## Detailed Setup Instructions

### 1️⃣ Sign Up for n8n Cloud
1. Visit [n8n.io](https://n8n.io/)  
2. Create a **Cloud account**  
3. Log in and access your **Dashboard**  
4. Familiarize yourself with **Workbench**  

---

### 2️⃣ Configure Google Cloud Console
1. Go to [Google Cloud Console](https://console.cloud.google.com/)  
2. Create a **new project**  
3. Navigate to **APIs & Services → Library**  
4. Search for **Custom Search API** and enable it  
5. Go to **APIs & Services → Credentials**  
6. Click **Create Credentials → API Key**  
7. Copy this **API Key** for n8n

---

### 3️⃣ Set Up Programmable Search Engine
1. Visit [Programmable Search Engine](https://cse.google.com/cse/all)  
2. Click **Add → New Search Engine**  
3. Leave sites blank or specify domains  
4. Select **“Search the entire web”**  
5. Click **Create**  
6. Go to **Control Panel → Details**  
7. Copy the **CX ID** for workflow configuration

---

### 4️⃣ Prepare Google Sheet
1. Open **Google Sheets**  
2. Create a new sheet with columns:  
   - `Name`  
   - `Company`  
   - `Profile URL`  
3. Connect to n8n via **OAuth2** credentials  
4. Test access to ensure n8n can write to the sheet

---

### 5️⃣ Import Workflow into n8n
1. In n8n **Workbench**, click **Import**  
2. Upload `Linkedin.json` workflow file  
3. Open the workflow editor  
4. Configure nodes:  
   - Google Custom Search Node → Add **API Key** and **CX ID**  
   - Google Sheets Node → Select the target sheet  
5. Validate that credentials are connected correctly

---

### 6️⃣ Run Workflow
1. Set the **search query**:  
   - Example: `site:linkedin.com/in "UI/UX Designer" Bangalore`  
2. Execute workflow manually or schedule automation  
3. Monitor output in the Google Sheet  
4. Verify scraped data is stored correctly

---

### Tips & Best Practices
- Test **API Key and CX ID** with a small query first  
- Use **specific search queries** to reduce irrelevant results  
- Schedule workflows for daily or weekly updates  
- Ensure Google Sheet permissions allow writing  
- Monitor execution logs in n8n to debug issues

---

## Support
- Documentation & FAQs: [FETSCR](https://www.fetscr.in/)  
- Contact: [Contact Page](https://www.fetscr.in/)

---

## Contribution
- Feedback & suggestions via **Contact Form**  
- Future contributions: workflow templates, bug fixes, and feature enhancements

---

## License
MIT License - see [LICENSE.md](LICENSE.md)

---

## Acknowledgments
- [n8n](https://n8n.io/) – Workflow automation engine  
- FETSCR Team – Design & deployment support
