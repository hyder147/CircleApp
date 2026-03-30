
# CircleApp - Social Media Platform

A full-stack social media application built with **ASP.NET Core**. Users can create accounts, make posts, connect with others, and interact through likes and comments.

## ✨ Features
- User Registration & Login (ASP.NET Identity)
- Create, Read, Update and Delete Posts
- Like and Comment on posts
- User Profile Management
- Feed showing posts from users
- Role-based Authorization (basic user roles)
- Responsive UI design

## 🛠 Tech Stack
- **Backend**: ASP.NET Core (C#)
- **Database**: SQL Server + Entity Framework Core
- **Authentication**: ASP.NET Identity
- **Frontend**: Razor Pages / MVC + Bootstrap
- **ORM**: Entity Framework Core

## 🚀 How to Run Locally

1. Clone the repository
   ```bash
   git clone https://github.com/hyder147/CircleApp.git
   ```

2. Navigate to the project folder
   ```bash
   cd CircleApp/CircleApp
   ```

3. Update the connection string in `appsettings.json` to point to your local SQL Server

4. Create and apply database migrations
   ```bash
   dotnet ef migrations add InitialCreate
   dotnet ef database update
   ```

5. Run the application
   ```bash
   dotnet run
   ```

Open in browser: `https://localhost:5001` (or the port shown in the terminal)

## 📸 Screenshots

> Screenshots will be added soon after running the project locally.

**Planned screenshots:**
- User Registration / Login page
- Home Feed with posts
- Create Post page
- User Profile page
- Comments section

## 📚 What I Learned / Challenges Solved
- Implemented full CRUD operations for social media posts
- Built user authentication and authorization using ASP.NET Identity
- Designed database relationships (User ↔ Post ↔ Comment ↔ Like)
- Managed real-time-like feed using Entity Framework Core
- Understood how to structure a backend for a social media application
- Handled many-to-many relationships (e.g., Likes between User and Post)

## 🔮 Future Improvements
- Add real-time notifications using SignalR
- Implement Follow/Follower system
- Add image upload support for posts
- Convert to RESTful Web API with Swagger
- Add Unit & Integration tests
- Deploy to Azure

---



Just paste it as-is for now, or tell me the actual main features of CircleApp so I can adjust it.  

Go ahead and add it! 🚀
