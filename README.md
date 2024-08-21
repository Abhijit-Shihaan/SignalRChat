# SignalRChat
 <!-- Replace with your project's logo if available -->

Overview
SignalRChat is a real-time chat application built using ASP.NET Core SignalR and SQL Server. It enables users to send and receive messages instantly, view online users, and update their profile pictures dynamically. This project showcases the powerful real-time communication capabilities of SignalR combined with the reliability of SQL Server for data storage.

Features
Real-Time Messaging: Instant message sending and receiving between users using SignalR.
Online Users Display: View the list of users currently online in the chat.
Profile Picture Updates: Change and display profile pictures dynamically for a personalized experience.
Scalable Architecture: Designed to handle multiple users with efficient real-time communication.
User Authentication: Secure login and user authentication.
User Profiles: Each user has a customizable profile with a display name and picture.
SQL Server Integration: Reliable storage of chat history, user profiles, and other critical data.
<h2>Tech Stack</h2>

- Frontend: HTML5, CSS3, JavaScript, Bootstrap
- Backend: ASP.NET Core, SignalR
- Database: SQL Server
- Development Tools: Visual Studio, Git

<h2>Getting Started</h2>
Prerequisites

- .NET Core SDK (v6.0 or later)
- SQL Server
- Visual Studio (with ASP.NET and web development workload)
- Node.js and npm (for managing frontend dependencies)


<h2>Installation</h2>
Clone the repository:
<br>

```bash
git clone https://github.com/yourusername/SignalRChat.git
cd SignalRChat 
```
Configure SQL Server:

Update the connection string in appsettings.json with your SQL Server credentials.
Run the database migrations to set up the necessary tables:

```bash
dotnet ef database update
```
Restore dependencies:

```bash
dotnet restore
```
Run the application:

```bash
dotnet run
```

<h2>Usage</h2>

- Login: Users can log in using their credentials.
- Chat: Start a conversation with other users in real-time.
- View Online Users: See who is currently online.
- Update Profile Picture: Click on your profile picture to update it.
