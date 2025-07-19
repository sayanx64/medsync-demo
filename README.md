![Syntax Status](https://github.com/openemr/openemr/workflows/Syntax/badge.svg?branch=rel-703)
![Styling Status](https://github.com/openemr/openemr/workflows/Styling/badge.svg?branch=rel-703)
![Testing Status](https://github.com/openemr/openemr/workflows/Test/badge.svg?branch=rel-703)

[![Backers on Open Collective](https://opencollective.com/openemr/backers/badge.svg)](#backers) 
[![Sponsors on Open Collective](https://opencollective.com/openemr/sponsors/badge.svg)](#sponsors)

# MedSync (Based on OpenEMR)

**MedSync** is a MedTech research project by three students - Sriyam Dasgupta, Sayan Pal and Ankit Kumar, focused on improving patient data flow in Indian hospitals. Built on OpenEMR and deployed on Google Cloud, it includes API integration and OAuth-based authentication.

---

## 🔧 Team Members

- **Sayan Pal**
- **Sriyam Dasgupta** 
- **Ankit Kumar** 

---

## 🔐 Demo Credentials

|  Role |    Username    |     Password     |
|-------|----------------|------------------|
| Admin | `UNN-admin-08` | `Admin@2024open` |

> **Note:** These credentials are for demonstration purposes only. Do not use them in production environments.

---

## 🚀 Features

- Custom API module based on `oe-module-api-explorer`
- Secure OAuth-based authentication
- Modular architecture for easy deployment
- Runs on Ubuntu VM, tested with Apache2 + MySQL

---

## 🧑‍💻 How to Contribute

MedSync builds upon OpenEMR and welcomes developers, students, and healthcare technologists to contribute. Check out the original [OpenEMR CONTRIBUTING.md](https://github.com/openemr/openemr/blob/master/CONTRIBUTING.md) for development guidelines.

---

## 📚 Resources

- [OpenEMR Docs](https://open-emr.org/wiki/index.php/Main_Page)
- [OpenEMR Forums](https://community.open-emr.org/)
- [API Explorer Docs](modules/oe-module-api-explorer/README.md) *(custom module)*

---

## 🐞 Reporting Issues

Please report bugs or suggestions via the GitHub [Issues tab](https://github.com/your-repo-name/issues).  
You can also reach out through the [OpenEMR Community Chat](https://www.open-emr.org/chat/).

---

## 🧪 Developer Setup

```bash
composer install --no-dev
npm install
npm run build
composer dump-autoload -o
