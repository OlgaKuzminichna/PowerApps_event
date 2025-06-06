# Event Management App

This is a custom-built **Event Management** application developed using **Microsoft PowerApps**. 
The app is a part of a larger tool suite that I have developed to streamline various office tasks and improve team collaboration. 

## App Overview

The **Event Management App** is designed to help users efficiently organize, manage, and attend events. Users can view upcoming and past events, register for them, and receive invites. This app is ideal for workplaces, teams, or organizations to schedule and track events seamlessly.

<img src="image.png" alt="alt text" width="800"/>

### Key Features:

- **Upcoming Events, Past Events, All Events**: The app allows users to toggle between different event categories. You can view all events, upcoming events, or past events, making it easy to track and stay updated.
- **Event Card**: The app shows detailed information about each event, including the event's date and time, along with buttons to register or get the invite. If the event is in the past then instead of get invite button view slide or watch recording will appear. All event details are pulled directly from the SharePoint list, ensuring the information is always up-to-date.
- **Filter Events**: In the top-right corner, you'll find a filter icon. Clicking on it will open a panel on the left side, allowing you to filter the event list by date, title, or event type.
- **Create Event**: If you are an Admin, you'll find the Create Event option in the right navigation bar. Clicking on it will open a form where you can input all the necessary details about the event. Once submitted, the new event will be stored in a SharePoint list and automatically created in the Outlook calendar.
- **Event Registration**: For each event, users can register if it's an external event or click Get Invite to receive the internal event link. Power Automate will then send the link directly, making it simple to join events with just one click.
- **Subscription Management**: Users can manage their subscriptions to different event types, ensuring they only receive notifications for the events that are most relevant to them. In the navigation bar, they can click Manage My Subscription to add or update their preferences.
Once an event is created, the app admin has the option to invite subscribers by clicking the Invite Subscribers button. After the button is clicked, it will disappear, indicating that the invitation has been sent.


## Technical Details

### Built Using
- **PowerApps** for the front-end development and user interface.
- **Power Automate** for workflow automation related to event creation, registration, and notification.

### Supported Devices
- The app is fully responsive, ensuring compatibility across desktops, tablets, and smartphones.

### System Requirements
- The app requires an active **Microsoft account** for usage with PowerApps access.
- No installation is required, as the app runs directly in the browser or the PowerApps mobile app.

---
