New Calculator
A lightweight, self-hosted calculator suite designed to run as a Docker container on your local network. Pull it up from any device on your network through a clean web UI — no installation, no accounts, no internet required.
Features

Mortgage Calculator — monthly payments, amortization breakdown
Loan Calculator — general purpose loan payment estimates
MPG Calculator — fuel efficiency and cost per mile
Tax Calculator — estimated tax liability
Take Home Pay Calculator — net pay after deductions

Tech Stack

Backend: Python / FastAPI / Javascript
Frontend: Web-based UI
Containerization: Docker / Docker Compose

Getting Started
Prerequisites

Docker
Docker Compose

Run it
bashgit clone https://github.com/bigjoetx/new_calculator
cd new_calculator
docker compose up -d

Then open your browser and navigate to http://localhost:8000 (or your local network IP) to access the UI from any device on your network.

Use Case
Designed for home or small office use — run it once on any machine, access it from your phone, tablet, or any browser on the same network without needing to install anything.

Disclaimer
The tax and take home pay calculators are provided for estimation purposes only and should not be relied upon for financial or tax planning decisions. Tax laws vary by jurisdiction and change frequently. Always consult a qualified tax professional for advice specific to your situation.
