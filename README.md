# azure-function-pipeline

Event-driven Azure Function for automated reporting, deployed via GitHub Actions.

---

## Tech Stack

- Python 3.12
- Azure Functions
- GitHub Actions (CI/CD)

---

## How It Works

Push to `main` → GitHub Actions builds and deploys automatically to Azure Functions (Production).

---

## Setup

```bash
git clone https://github.com/Ashwin52/azure-function-pipeline.git
cd azure-function-pipeline
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
func start
```

---

## Required GitHub Secrets

| Secret | Description |
|--------|-------------|
| `AZUREAPPSERVICE_CLIENTID` | Azure AD Client ID |
| `AZUREAPPSERVICE_TENANTID` | Azure Tenant ID |
| `AZUREAPPSERVICE_SUBSCRIPTIONID` | Azure Subscription ID |

---

## Course

Built as part of an AI + Azure hands-on course.
