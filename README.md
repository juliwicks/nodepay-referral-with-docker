# Nodepay Referral with Docker

This project automates the process of signing up for the Nodepay referral program and handles captcha challenges. It runs inside a Docker container for easy deployment.

## Prerequisites

- Docker installed on your machine
- `curl` installed

## Basic Script

You can go here if you don't want to use Docker: https://github.com/juliwicks/nodepay-referral

## Installation

Run the following command to download and run the setup script:

```bash
curl -sSL https://raw.githubusercontent.com/juliwicks/nodepay-referral-with-docker/refs/heads/main/nodref-start.sh -o nodref-start.sh && chmod +x nodref-start.sh && ./nodref-start.sh
```
## The script will:

- Ask for a Docker container name.
- Generate a random UUID and MAC address.
- Build and run the Docker container.

## How It Works

The script creates a Docker container with the necessary dependencies.
It clones the Nodepay referral repo and runs the referral script.
The Docker container is configured with a random UUID and MAC address for each run.
