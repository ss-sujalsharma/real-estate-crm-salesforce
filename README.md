# 🏡 My Real Estate CRM – Salesforce Lightning Web App

Welcome to **My Real Estate CRM**, a fully customized Salesforce application built using Lightning Web Components (LWC), Apex, and Salesforce DX (SFDX).  
This project is adapted from Salesforce's official DreamHouse LWC app and redesigned for CRM functionalities specific to real estate use cases.

---

## 🚀 Key Features

- 🏘️ Browse and search property listings
- 👩‍💼 View broker and agent profiles
- 🗺️ Map-based property visualization
- 📁 Organized using Salesforce DX project structure
- 🔐 Custom permissions and objects
- 📊 Sample data import for testing
- ⚙️ Fully deployable using Scratch Orgs

---

## 🧰 Tech Stack

- **Salesforce DX (SFDX CLI)**
- **Lightning Web Components (LWC)**
- **Apex Classes**
- **SOQL & SOSL**
- **Git + GitHub**
- **Scratch Org (Dev Environment)**

---


---

## 🔧 How to Setup the Project Locally

### 1. Clone the Repository

```bash
git clone https://github.com/ss-sujalsharma/real-estate-crm-salesforce.git
cd real-estate-crm-salesforce

````

### 2. Authenticate with Salesforce

```bash
sf org login web --set-default-dev-hub --alias DevHub
```

### 3. Create a Scratch Org

```bash
sf org create scratch --definition-file config/project-scratch-def.json --alias mycrm --set-default --duration-days 30
```

### 4. Deploy Source to Scratch Org

```bash
sf project deploy start
```

### 5. Assign Permission Set

```bash
sf org assign permset --name DreamHouse
```

### 6. Import Sample Data

```bash
sf data tree import --plan data/sample-data-plan.json
```

### 7. Open the Org

```bash
sf org open
```

➡️ Then, open the **App Launcher** and search for `"My Real Estate CRM"` to explore the app.

```

---

Let me know if you'd like the **entire `README.md` file rebuilt** or want to include **badges, screenshots, or live demo links**!
```

