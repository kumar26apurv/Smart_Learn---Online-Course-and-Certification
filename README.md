# Smart Learn – Online Course & Certification Platform (Full Stack)

A production-ready **full-stack Online Course Enrollment & Certification web application** built using **Angular (Frontend)** and **.NET Core Web API (Backend)** with enterprise-grade features like authentication, cloud storage, monitoring, CI/CD pipelines, and serverless automation.

---

## 🚀 Features

- ✅ Online course listing and enrollment
- ✅ Secure Authentication & Authorization using **Azure AD B2C**
- ✅ User Profile management
- ✅ Course CRUD operations (Admin / Management APIs)
- ✅ Image upload support (Azure Storage)
- ✅ Transactional email notifications (SendGrid)
- ✅ Background automation using Azure Functions
- ✅ Logging & monitoring using Application Insights + Serilog
- ✅ Health checks for backend service
- ✅ CI/CD pipelines with Azure DevOps

---

## 🧰 Tech Stack

### Frontend
- **Angular**
- TypeScript
- Angular Routing, Guards
- Reactive Forms
- HTTP Client Integration

### Backend
- **.NET Core Web API**
- Entity Framework Core
- SQL Server / Azure SQL Database
- REST API with Swagger

### Cloud & DevOps
- Azure App Service (Frontend & Backend Hosting)
- Azure SQL Database
- Azure Storage Account (Image uploads)
- Azure Functions (Serverless workflows)
- Azure AD B2C (Authentication)
- SendGrid (Email service)
- Application Insights (Monitoring)
- Azure DevOps CI/CD Pipelines

---

## 📁 Project Structure

```bash
SmartCertify/
│
├── backend/                  # .NET Core Web API Solution
│   ├── LSC.OnlineCourse.sln
│   ├── LSC.OnlineCourse.API/
│   ├── LSC.OnlineCourse.Core/
│   ├── LSC.OnlineCourse.Infrastructure/
│   └── ...
│
├── frontend/                 # Angular Application
│   ├── src/
│   ├── angular.json
│   ├── package.json
│   └── ...
│
└── README.md
