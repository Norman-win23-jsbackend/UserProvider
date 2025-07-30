# 👤 UserProvider

**UserProvider** is a backend service built with **.NET 8** and **Azure Functions**, focused on managing user data in a scalable and modular way.  
It provides endpoints for user creation, retrieval, updates, and integration with other microservices such as authentication and subscriptions.

---

## 🚀 Features

- 👥 Create and manage user profiles  
- ⚙️ Built using **Azure Functions** with clean separation of logic  
- 🔗 Designed for integration with other providers (Account, Subscription, etc.)  
- 🧱 Scalable architecture using event-driven patterns  
- 🔐 Ready for secure deployment and external identity providers  

---

## 📁 Project Structure

```

UserProvider/
├── Program.cs               # Main entry point
├── host.json               # Azure Functions runtime configuration
├── local.settings.json     # Local dev environment (not for production)
├── UserProvider.csproj     # Project definition
└── Functions/              # Azure Functions for user operations

````

---

## 🛠️ Getting Started

### 1. Prerequisites

- [.NET 8 SDK](https://dotnet.microsoft.com/en-us/download)  
- [Azure Functions Core Tools](https://learn.microsoft.com/en-us/azure/azure-functions/functions-run-local)

### 2. Run Locally

```bash
git clone https://github.com/Norman-Deen/UserProvider.git
cd UserProvider
func start
````

Open in browser:

```
http://localhost:7071
```

---

## ☁️ Azure Integration

* Deployable to **Azure Functions**
* Supports extension with **Azure AD**, **Key Vault**, or **Cosmos DB**
* Config-driven via `local.settings.json` or Azure App Config

---

## 🔐 Security Guidelines

* Keep secrets out of source control
* Store credentials in Azure Key Vault
* Add authentication & role validation for production endpoints

---

## 📄 License

This project is shared under the [MIT License](LICENSE).
Use it as a base for user service modules in microservice architectures.

---

**Nour Tinawi**

[LinkedIn](https://www.linkedin.com/in/nour-tinawi) • [Portfolio](https://www.pure-art.co) • [GitHub](https://github.com/Norman-Deen)
