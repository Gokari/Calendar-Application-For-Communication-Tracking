#ENTNT Technical Assignment : Calendar Application for Communication Tracking

***Deployment***

  https://calendar-application-for-communication-tracking-lime.vercel.app/user
  
  
***ADMIN*** 


![Admin1](https://github.com/Gokari/Calendar-Application-For-Communication-Tracking/blob/master/Screenshots/Admin1.png?raw=true)
![Admin2](https://github.com/Gokari/Calendar-Application-For-Communication-Tracking/blob/master/Screenshots/Admin2.png?raw=true)
![Admin3](https://github.com/Gokari/Calendar-Application-For-Communication-Tracking/blob/master/Screenshots/Admin3.png?raw=true)
![Admin4](https://github.com/Gokari/Calendar-Application-For-Communication-Tracking/blob/master/Screenshots/Admin4.png?raw=true)
![Admin5](https://github.com/Gokari/Calendar-Application-For-Communication-Tracking/blob/master/Screenshots/Admin5.png?raw=true)

***User***


![User1](https://github.com/Gokari/Calendar-Application-For-Communication-Tracking/blob/master/Screenshots/User1.png?raw=true)
![User2](https://github.com/Gokari/Calendar-Application-For-Communication-Tracking/blob/master/Screenshots/User2.png?raw=true)
![User3](https://github.com/Gokari/Calendar-Application-For-Communication-Tracking/blob/master/Screenshots/User3.png?raw=true)
![User4](https://github.com/Gokari/Calendar-Application-For-Communication-Tracking/blob/master/Screenshots/User4.png?raw=true)



***Reports***


![Reports1](https://github.com/Gokari/Calendar-Application-For-Communication-Tracking/blob/master/Screenshots/Reports1.png?raw=true)
![Reports2](https://github.com/Gokari/Calendar-Application-For-Communication-Tracking/blob/master/Screenshots/Reports2.png?raw=true)
![Reports3](https://github.com/Gokari/Calendar-Application-For-Communication-Tracking/blob/master/Screenshots/Reports3.png?raw=true)
![Reports4](https://github.com/Gokari/Calendar-Application-For-Communication-Tracking/blob/master/Screenshots/Reports4.png?raw=true)


Objective

 # React-Based Calendar Application

## Objective

This application is designed to help maintain strong professional relationships with other organizations by accurately tracking communication. It ensures timely follow-ups and consistent engagement through a centralized platform. The key features include:

1. **Admin Module**: To set up companies and communication parameters.
2. **User Module**: To visualize, manage, and perform communication tasks.
3. **Reporting and Analytics Module** (Optional): Provides actionable insights into communication trends and performance.

---

## Features and Modules

### Admin Module

#### Company Management
- Add, edit, and delete company details.
- Each company entry includes:
  - **Name**: Company name.
  - **Location**: Physical or operational location.
  - **LinkedIn Profile**: Link to the company’s LinkedIn page.
  - **Emails**: One or more communication email addresses.
  - **Phone Numbers**: Contact numbers.
  - **Comments**: Notes or additional information.
  - **Communication Periodicity**: Default time interval for scheduled communications (e.g., every 2 weeks).

#### Communication Method Management
- Define available communication methods, including:
  - **Name**: E.g., "Visit" or "LinkedIn Post."
  - **Description**: E.g., "Visit to company premises."
  - **Sequence**: Order of communication steps.
  - **Mandatory Flag**: Marks whether a communication method is mandatory.
- Default communication methods (in sequence):
  - LinkedIn Post
  - LinkedIn Message
  - Email
  - Phone Call
  - Other

---

### User Module

#### Dashboard
- Grid-like view with the following columns:
  - **Company Name**: Name of the company.
  - **Last Five Communications**: Type and date of the five most recent interactions.
  - **Next Scheduled Communication**: Type and date of the next planned interaction.
- **Color-Coded Highlights**:
  - **Red**: Overdue communications.
  - **Yellow**: Communications due today.
- **Interactive Features**:
  - Hover over completed communications to display notes in a tooltip.

#### Communication Actions
- Select one or multiple companies.
- Log a new communication through a modal:
  - Select the communication type (e.g., LinkedIn Post, Email).
  - Input the date.
  - Add notes.
- Reset any existing highlights for the selected companies.

#### Notifications
- **Overdue Communications Grid**: Companies with overdue actions.
- **Today’s Communications Grid**: Companies with tasks due today.
- Notification icon with a badge for overdue and due tasks.

#### Calendar View
- View past communications (dates and methods).
- Manage upcoming communications (dates and methods).

---

### Reporting and Analytics Module (Optional)

#### Features:
- **Communication Frequency Report**:
  - Visual representation (bar chart/pie chart) of communication methods used over time.
  - Filter by company, date range, or method.
- **Engagement Effectiveness Dashboard**:
  - Metrics on the success of communication methods (e.g., response rates).
- **Overdue Communication Trends**:
  - Trendline/heatmap of overdue communications over time, categorized by company.
- **Downloadable Reports**:
  - Export data as PDF or CSV.
- **Real-Time Activity Log**:
  - Live feed of communication activities.

---

## Installation and Setup

1. Clone the repository.
2.  git clone <https://github.com/Gokari/Calendar-Application-For-Communication-Tracking.git>
3. Open the project in **VS Code**.
4. Run the following commands:
   ```bash
   npm install
   npm run start
   ```

To view the application documentation:
```bash
npm run readme.md
```

---

## Technology Stack
- **Frontend**: React.js
- **Backend**: Node.js (optional integration for API handling)
- **Database**: MongoDB/MySQL (optional)
- **Styling**: CSS/Bootstrap/Tailwind CSS

---

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature/fix.
3. Commit your changes and push to your branch.
4. Create a Pull Request.





