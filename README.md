# IIIT Trichy Devs — Community Member Roster

Welcome to the official developer directory for the **IIIT-Trichy-Devs** community! This repository is designed as the first hands-on open-source contribution for students at the Indian Institute of Information Technology, Tiruchirappalli.

## How to Add Yourself to the Roster

Follow these steps to make your first open-source Pull Request:

1. **Fork this repository** by clicking the **Fork** button in the top-right corner of this page.
2. **Clone your fork** to your local machine:
   ```bash
   git clone https://github.com/<YOUR-USERNAME>/community-roster.git
   cd community-roster
   ```
3. **Create a new branch** for your profile:
   ```bash
   git checkout -b add-<your-name>
   ```
4. **Edit your batch file** inside the `members/` directory (e.g. `members/batch-2026.json`):
   Add your entry to the JSON array following the existing format:
   ```json
   {
     "name": "Your Name",
     "department": "CSE / ECE / VLSI",
     "batch": "2026",
     "github": "https://github.com/your-username",
     "interests": ["Web Development", "AI/ML", "Systems Programming"]
   }
   ```
5. **Commit and push** your changes:
   ```bash
   git add members/batch-2026.json
   git commit -m "feat: add <your-name> to batch-2026 roster"
   git push origin add-<your-name>
   ```
6. **Open a Pull Request**: Go to the original `IIIT-Trichy-Devs/community-roster` repo on GitHub, click **Compare & pull request**, and submit!

---

Maintained by the [IIIT-Trichy-Devs Community](https://github.com/IIIT-Trichy-Devs).
