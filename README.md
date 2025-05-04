# 🔌 Quattrofy API

## 🧭 Overview  
**Quattrofy API** is a secure, internal RESTful API designed to enable seamless integration between the **Quattrofy Web Application** and tools such as **Microsoft Power Automate**, **Microsoft Copilot Studio**, and future internal systems. It serves as the foundation for data automation, smart queries, and actionable insights across Quattro Constructors' operational environment.

---

## 💡 Idea & Concept  
The goal was to build a **centralized API layer** for securely exposing business logic and data from the Quattrofy system.  
It empowers automation, real-time querying, and task execution using tools like Power Automate and conversational agents like QuattroMan.

---

## ✨ Key Endpoints  
Some of the most commonly used and critical endpoints include:

- `/employees/location` – Return current or last known location of an employee  
- `/equipment/location` – Return last registered project or location for an asset  
- `/projects/summary` – Returns general information about project status, start, cost, team, etc.  
- `/projects/payclasses` – Retrieves pay class information for a specific project  
- `/projects/sync` – Performs secure sync operation between external and Quattrofy databases  
- `/system/ping` – Used for availability checks before automated flows run  

---

## ⚙️ Tech Stack  
| Technology | Description |
|------------|-------------|
| ![C#](https://img.shields.io/badge/C%23-239120?logo=csharp&logoColor=white&style=for-the-badge) | API developed with .NET Core |
| ![ASP.NET](https://img.shields.io/badge/ASP.NET-512BD4?logo=dotnet&logoColor=white&style=for-the-badge) | Framework for building REST APIs |
| ![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?logo=microsoftsqlserver&logoColor=white&style=for-the-badge) | Primary data store for all Quattrofy data |
| ![Power Automate](https://img.shields.io/badge/Power%20Automate-0066FF?logo=microsoftpowerautomate&logoColor=white&style=for-the-badge) | Automation engine connected via API |
| ![Microsoft Copilot Studio](https://img.shields.io/badge/Copilot%20Studio-000000?logo=microsoft&logoColor=white&style=for-the-badge) | Conversational agent integration |
| ![REST API](https://img.shields.io/badge/REST%20API-FF6F00?logo=api&logoColor=white&style=for-the-badge) | Exposed RESTful endpoints for business logic |
| ![JSON](https://img.shields.io/badge/JSON-000000?logo=json&logoColor=white&style=for-the-badge) | Response and request data format |
| ![JWT](https://img.shields.io/badge/JWT-000000?logo=jsonwebtokens&logoColor=white&style=for-the-badge) | Used for secure token-based authentication |

---

## 🧑‍💻 My Role & Contributions  
- Designed and implemented the full API architecture  
- Developed all core endpoints using C# and .NET Core  
- Secured access using role-based authentication and JWT tokens  
- Built automation hooks for Power Automate triggers  
- Connected endpoints with Microsoft Copilot Studio for dynamic AI conversations  
- Deployed API with versioning and performance logging  

---

## 🔐 Security Highlights  
- JWT token validation with expiration  
- HTTPS-only access  
- Role-based access controls  
- IP whitelisting (for high-privilege endpoints)  
- Detailed logging with internal analytics  

---

## 📈 Future Enhancements  
- Swagger documentation for all endpoints  
- GraphQL gateway for more flexible frontend consumption  
- Activity logs with real-time alerts  
- Rate limiting and throttling for abuse protection  

---

## 🔗 Related Projects  
- [Quattrofy Web](#) – The main system interfacing with this API  
- [QuattroMan](#) – AI Assistant using this API for smart queries  
- [Power Automate Flows](#) – Automations triggered via this API  

---

## 📎 License  
Internal use only – Proprietary API for **Quattro Constructors**. Not open to the public.