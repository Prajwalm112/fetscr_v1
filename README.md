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

Follow these steps to create and run workflows in FETSCR:

1. **Access Workbench**  
   - Log in at [FETSCR](https://www.fetscr.in/)  
   - Navigate to **Workbench** → **Create New Workflow**

2. **Choose a Template or Start from Scratch**  
   - Template: Pre-built workflows (LinkedIn, Zomato, Indeed, etc.)  
   - From Scratch: Drag and drop nodes to define your workflow

3. **Add Trigger Node**  
   - Example: Cron Node to schedule automation (daily/hourly)

4. **Add Scraper Node**  
   - Configure target website and select fields to extract  
   - Test node to ensure data is pulled correctly

5. **Add Data Processing Nodes (Optional)**  
   - Function Node: Transform or clean data  
   - Set Node: Organize fields for output

6. **Add Output Node**  
   - Google Sheets Node: Export data to a sheet  
   - CSV Node: Save data as CSV  
   - Webhook/Email Node: Send data to an app or inbox

7. **Connect & Activate Workflow**  
   - Connect nodes in order: Trigger → Scraper → Processing → Output  
   - Save and **Activate** workflow

8. **Monitor Workflows**  
   - Check logs, view errors, edit or delete workflows from the dashboard

**Example Use Case**: Scraping LinkedIn Jobs  
- Cron node runs daily → Scraper node pulls Job Title, Company, Location, Post Date → Google Sheets node exports data → Workflow updates automatically every day

---

## Support
- Documentation & FAQs: [FETSCR](https://www.fetscr.in/)  
- Contact: [Contact Page](https://www.fetscr.in/)

---

## Contribution
- Feedback & suggestions via **Contact Form**  
- Future contributions: workflow templates and enhancements

---

## License
MIT License - see [LICENSE.md](LICENSE.md)

---

## Acknowledgments
- [n8n](https://n8n.io/) – Workflow automation engine  
- FETSCR Team – Design & deployment support
