# SETUP_GUIDE.md for SIAKAD Universitas Mayjen Sungkono

## Table of Contents
1. [Admin Setup Workflow](#admin-setup-workflow)
2. [Academic Calendar Management](#academic-calendar-management)
3. [KRS Process Flow](#krs-process-flow)
4. [Student-Advisor Approval Workflow](#student-advisor-approval-workflow)

---

## Admin Setup Workflow

1. **System Requirements**  
   - Ensure the server meets the minimum requirements:
     - OS: Linux/Windows
     - RAM: 8GB
     - Disk Space: 100GB

2. **Installation Steps**  
   - Clone the repository:
     ```bash
     git clone https://github.com/{owner}/siakad-unimas.git
     cd siakad-unimas
     ```  
   - Install dependencies:
     ```bash
     npm install
     ```  
   - Configure environment variables in `.env` file:
     ```env
     DATABASE_URL=your_database_url
     SECRET_KEY=your_secret_key
     ```  

3. **Setup Admin Account**  
   - Run the script to create an admin account:
     ```bash
     npm run create-admin
     ```  
   - Follow the prompts to set admin username and password.

## Academic Calendar Management

1. **Accessing the Calendar**  
   - Navigate to the Academic Calendar section in the admin dashboard.

2. **Adding New Academic Year**  
   - Click on "Add Academic Year" and fill in the required fields:
     - Year: [academic_year]
     - Start Date: [start_date]
     - End Date: [end_date]
   - Save changes.

3. **Updating Existing Calendar**  
   - Select the academic year to edit.
   - Make necessary changes and click "Update."

## KRS Process Flow

1. **Opening KRS Period**  
   - Go to the KRS management section.
     - Click "Open KRS Period" and select the relevant academic year.
   - Set the start and end dates for KRS submission.

2. **Monitoring Submissions**  
   - Check KRS submissions from the dashboard:
     - Review, approve, or reject submissions as necessary.

## Student-Advisor Approval Workflow

1. **Advisor Assignment**  
   - Go to the advisor management section and assign advisors to students.

2. **Approval Process**  
   - Students submit their KRS to their respective advisors:
   - Advisors receive notifications to review and approve submissions.
   - Advisors can approve or reject and provide feedback through the system.

---

## Conclusion
This setup guide aims to streamline administrative duties within the SIAKAD Universitas Mayjen Sungkono system. For further assistance, please refer to the support documentation or contact the technical team.