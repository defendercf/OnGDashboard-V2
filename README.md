# OnGDashboard Installation

## Prerequisites

Before setting up and running the repository locally, ensure you have the following system-level software dependencies installed on your machine:

### System Requirements

* **Node.js** (v18.x or v20.x highly recommended) -> *Handles the Nuxt 3 web dashboard application framework.*
* **Python** (v3.11 or v3.12) -> *Handles the background offshore prediction models, data evaluation, and machine learning layer.*
* **npm** (Comes bundled with Node.js) -> *Your primary JavaScript package manager.*

---

### Setup

1. Clone the repository into your Terminal / Code editor
```bash
git clone [repo url]
```
2. Go to the OnGDashboard directory
```bash
cd OnGDashboard
```
3. Install Python Dependencies
```bash
pip install -r server/api/offshore_forecast_api/requirements.txt
```
4. Install Node.JS Dependencies
```bash
npm install
```
5. Run the website locally
```bash
npm run dev
```
Website can be accessed in the browser via **https://localhost:3000**

---
