# Cars Dealership - Full-Stack Development Capstone

A full-stack dealership web application developed for the IBM Full-Stack Software Developer Capstone Project.

## Project Overview

Cars Dealership is a web application designed for a US-based car retailer. The intended application allows visitors to browse dealerships, filter dealerships by state, view dealer details and customer reviews, create accounts, sign in, and post reviews.

## Technology Stack

- **Backend:** Python, Django, Django REST Framework
- **Frontend:** HTML, CSS, JavaScript, React (to be integrated)
- **Services and data:** Node.js/Express, Cloudant or MongoDB-based dealer/review services, SQLite for Django models
- **Sentiment analysis:** IBM Watson Natural Language Understanding
- **DevOps:** GitHub Actions, Docker, Kubernetes, IBM Cloud deployment

> **Project status:** Work in progress. Some features, integrations and deployment artifacts listed above are planned and not yet implemented or verified.

## Planned Features

1. Responsive Home, About Us, and Contact Us pages.
2. Registration, login, logout, and Django administration.
3. Dealer listing, detail pages, and state filtering.
4. Reviews, review submission, and sentiment analysis.
5. Car makes and models API endpoints.
6. CI/CD checks and cloud deployment.

## Repository Structure

- `server/`: Django project and application.
- `functions/`: Backend service templates and setup.
- `cloudant/`: Dealership data resources.
- `.github/workflows/`: GitHub Actions workflow files.

## Getting Started

Clone this repository:

```bash
git clone https://github.com/DefaultCode117/agfzb-CloudAppDevelopment_Capstone.git
cd agfzb-CloudAppDevelopment_Capstone
```

Inspect `server/requirements.txt` and configure the required services and environment variables before starting Django. Never commit credentials or secrets.

## Author

Jhon Sebastian Tribaldos Torres

## Credits

Adapted from the IBM Developer Skills Network Full-Stack Development Capstone starter repository. The project is developed as an educational exercise.
