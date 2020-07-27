# Project-7-WebApp-Dashboard

Treehouse Techdegree - WebApp Dashboard

+ link

Project Requirements
====================

### Create a responsvie web page from the supplied `dashboard.png` mockup with the following:
  * Header with app name, notification icon badge, and profile avatar and name.
  * SVG icon based navigation with the following links: Dashboard, Members, Visits, and Settings.
    - **NOTE:** You only have to build out the main dashboard page, not any of the other pages.
  * Ensure that the design responds well to:
    - Mobile (320px)
    - Tablet (768px)
    - Desktop (1024px)
  * Use CSS grid to lay out the main elements (header, sidebar navigation, main content) on the page.
  
---    

### Demo Alert Notification: 
  * In the dashboard.png, this appears as the purple bar near the top of the page with the word "Alert" in it.
  * When the page loads this alert should be visible, but the user should be able to close the alert by clicking the X button.

---

### Chart Widget:
  * Using chart.js, create and include the information for the following chart widgets, as shown in the mockup for the:
    - Web Traffic (line chart)
    - Daily Traffic Bar Chart (bar chart)
    - Mobile User Pie Chart (donut chart)
  * Style the charts to match the overall style of the dashboard.
  * You will need to make up this data -- you can see the mockup for sample data.

---

### Social Stats Widget:
  * Create a widget (or three separate widgets) to display social network stats for Facebook, Twitter, and Google+.
  * Use the provided SVG icons for each of the social networks.
  * SVG icons are added as inline SVG's.
  * SVG fill colors have been changed to match the mockups.
  * Style the social information to match the corresponding social network.
  * Style to match the overall look and feel of the dashboard.

---

### New Members and Recent Activity Widgets:
  * Create widgets that list users for both widgets.
  * Include avatars for each member (member avatars are inside images folder).
  * Add the information for each user as shown in the mockup, such as:
    - Member name
    - Email address
    - Sign up Date, 
    - Etc...

---

### Message User Widget:
  * Create a field for searching for a user.
    - You don't have to add real search functionality
    - But if you attempt to get the exceeds grade, you'll need to make up some user data.
  * Add a message textarea field that lets you add a message.
  * Create a “Send” button and use JS to allow you to submit the form and display a confirmation the message was sent.
    - You won't actually submit the form, just simulate the action using JavaScript.
  * Use JS to display error messages if a user isn’t selected or message field is empty.
  * Style to match the overall look and feel of the dashboard.

---

### Settings Widget:
  * Create a settings widget to display various setting options using different form elements.
  * Create an on/off widget for whether to send email notifications.
  * Create an on/off widget for whether to set the profile to public or private.
  * Create a drop-down to select the timezone.
  * Add Save and Cancel buttons
    - Unless going for the Exceeds Expectations localStorage requirement
  * Style to match the overall look and feel of the dashboard.

---

### Extra Credit: 
  * Display at least two notifications at the same time when the user clicks the alerts icon.
    - This could be a pop-up window or dropdown menu.
  * Traffic chart widget.
    - Create a navigation similar to the one in the mockup to display different data when the Hourly, Daily, Weekly and Monthly button is selected.
    - Add functionality to the Hourly, Daily, Weekly and Monthly buttons so that a different line chart is displayed on click.
  * Add an "autocomplete" feature for the "Search for User" box, listing names that match the search term.
  * Use local storage to save the settings.
    - The settings are saved to local storage when the "Save" button is clicked.
    - The settings are reset when the "Cancel" button is clicked.
    - When page is reloaded the settings are remembered.
