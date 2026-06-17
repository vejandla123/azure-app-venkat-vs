# Azure App - Venkat VS

Welcome to the **Azure App - Venkat VS** repository! This is a web application project hosted on Azure.

## 📋 Overview

This repository contains the source code for an Azure-based application with automated build and deployment workflows using GitHub Actions.

## 🚀 Features

- Automated Build Pipeline
- Automated Deployment to Azure
- HTML-based user interface
- GitHub Actions CI/CD Integration

## 📁 Project Structure

```
azure-app-venkat-vs/
├── .github/
│   └── workflows/
│       ├── build.yml          # Build workflow
│       └── deploy.yml         # Deploy workflow
├── index.html
├── README.md
└── ... (other files)
```

## 🔧 Workflows

### Build Workflow
- **Trigger:** Push to `master` branch or Pull Requests
- **Location:** `.github/workflows/build.yml`
- **Purpose:** Validates the application build and verifies HTML files

### Deploy Workflow
- **Trigger:** Push to `master` branch
- **Location:** `.github/workflows/deploy.yml`
- **Purpose:** Deploys the application to Azure App Service

## 📝 Getting Started

### Prerequisites
- Git
- GitHub Account
- Azure Account (for deployment)

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/vejandla123/azure-app-venkat-vs.git
   cd azure-app-venkat-vs
   ```

2. Make changes to your HTML files

3. Push your changes:
   ```bash
   git add .
   git commit -m "Your commit message"
   git push origin master
   ```

4. Watch the automated workflows run in the **Actions** tab

## 🔄 CI/CD Pipeline

Every push to the `master` branch triggers:

1. **Build Job** - Verifies the application compiles and HTML files are valid
2. **Deploy Job** - Deploys to Azure App Service

## 📊 Actions & Deployment Status

Check the status of your workflows at: [Actions](https://github.com/vejandla123/azure-app-venkat-vs/actions)

## 🛠️ Configuration

### Environment Variables
To add deployment credentials, configure them in:
- **Settings** → **Secrets and variables** → **Actions**

### Azure Deployment
Update `.github/workflows/deploy.yml` with your Azure credentials:
- `AZURE_SUBSCRIPTION_ID`
- `AZURE_RESOURCE_GROUP`
- `AZURE_APP_SERVICE_NAME`

## 📚 Resources

- [GitHub Actions Documentation](https://docs.github.com/en/actions)
- [Azure App Service Documentation](https://docs.microsoft.com/en-us/azure/app-service/)
- [GitHub Workflows Guide](https://docs.github.com/en/actions/learn-github-actions)

## 👤 Author

**Venkat** - Created as a first-time GitHub Actions and Azure deployment project

## 📄 License

This project is open source and available under the MIT License.

---

**Last Updated:** June 17, 2026    

For more information, visit the [repository](https://github.com/vejandla123/azure-app-venkat-vs)
