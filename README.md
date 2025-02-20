The **Submission Reminder App** automates checking student assignment submissions and generating reminders for those who haven't submitted. It features an automated setup, submission status verification, and reminder notifications.

### **Setup & Usage**  
1. **Clone & Navigate**:  
   ```bash
   git clone https://github.com/<your-github-username>/submission_reminder_app.git  
   cd submission_reminder_app  
   ```
2. **Run Setup Script**:  
   ```bash
   chmod +x create_environment.sh  
   ./create_environment.sh  
   ```
3. **Run the App**:  
   ```bash
   ./startup.sh  
   ```

### **Structure & Key Files**  
- `apps/reminder.sh` – Main script for checking submissions.  
- `modules/functions.sh` – Helper functions for processing data.  
- `assets/submissions.txt` – Stores student submission statuses.  
- `config/config.env` – Stores environment variables.  
- `startup.sh` – Initializes the app.

### **Contributing**  
Fork, create a branch, commit changes, and submit a pull request.  

Let me know if you need further refinements! 🚀
