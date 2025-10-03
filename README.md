# DisasterWeb

**DisasterWeb** is a disaster management and emergency response coordination platform built with ASP.NET Core MVC. It streamlines monitoring disasters, allocating resources, coordinating response teams, and improving decision-making through real-time analytics and geospatial mapping.

---

## 🚀 Features

- **Real-Time Dashboard**  
  Monitor ongoing incidents and resource statuses in real time to make faster, informed decisions.

- **Incident Management**  
  Centralized system to track and manage all disaster-related incidents.

- **Resource Management**  
  Manage personnel, equipment, and supplies; track allocation and availability.

- **Responder Coordination**  
  Assign tasks to team members based on skill sets and roles; facilitate communication among responders.

- **Analytics & Reporting**  
  Generate performance reports and insights after an incident to improve future responses.

- **Geospatial Mapping**  
  Visualize incidents and resources on an interactive map for better situational awareness.

- **Security & Access Control**  
  Role-based access control (RBAC) ensures only authorized users access particular features.

- **Mobile Responsiveness**  
  Fully responsive UI, works well on mobile and tablet devices.

- **Live Alerts & Messaging**  
  Send notifications, alerts, and real-time messages between coordinators and field responders.

---

## 🧰 Technology Stack

| Layer          | Technologies / Tools                         |
|----------------|-----------------------------------------------|
| Backend        | ASP.NET Core 6.0, C#, Entity Framework Core   |
| Authentication | ASP.NET Core Identity                         |
| Frontend       | Bootstrap 5, JavaScript (ES6+), Chart.js, Leaflet.js |
| Icons & UI     | Font Awesome                                  |
| Database        | In-Memory database (for development/testing) |

---

## 📥 Installation & Setup

### Prerequisites

- .NET 6.0 SDK or newer  
- Visual Studio 2022 / Visual Studio Code  
- Git  

### Steps to Run Locally

1. Clone the repository  
   ```bash
   git clone https://github.com/JasminSibeko/DisasterWeb.git
   cd DisasterWeb


Open the solution file DisasterWeb.sln in your IDE.

Build the solution to restore and compile dependencies.

Run the project (e.g. via Visual Studio or dotnet run in the project folder).

Open your browser and navigate to https://localhost:5001 (or the configured port).

🧩 Usage & Workflow

Register / Log in — create user accounts and assign roles (e.g. admin, coordinator, responder).

Create an incident — add a new disaster event with location, severity, and details.

Allocate resources — assign equipment, personnel, vehicles, and supplies.

Coordinate responders — assign tasks to field teams, communicate via messaging.

Monitor progress — use dashboards and maps to track status in real time.

Generate reports — analyze post-incident data and generate performance insights.

🧪 Testing & Development

The project uses an in-memory database for faster iteration and testing.

To switch to a persistent store (e.g. SQL Server), update the DbContext configuration in Startup / Program.cs.

Add unit/integration tests targeting controllers, services, and data access layers.

✅ Contributing

Contributions are welcome! Here’s how you can help:

Fork the repository.

Create a feature branch (git checkout -b feature/awesome-feature).

Commit your changes (git commit -m "Add awesome feature").

Push to your fork (git push origin feature/awesome-feature).

Open a Pull Request against the main repository.

Please follow the existing code style, write meaningful commit messages, and include tests where applicable.

📝 License

This project is licensed under the MIT License
 (or whatever license you choose). Feel free to use, modify, and distribute.

Acknowledgements & Resources

The Leaflet.js library for maps

Chart.js for data visualizations

Bootstrap for responsive UI

Community and open source inspiration

Contact

For queries, feedback, or help, you can reach out to:

Author: Jasmin Sibeko

Repository: https://github.com/JasminSibeko/DisasterWeb
