
# Twitter Bot
This Twitter Bot automatically tweets on a schedule using Node.js, the Twitter API, and cron jobs.


## Features

- Automatic tweeting on a regular schedule.
- Simple setup with environment variables for API keys and tokens.


## Prerequisites

- Node.js and npm installed on your machine.
- Twitter Developer account and API keys from the Twitter    Developer Platform.

# Installation

## Step-1: Install Node

```bash
node -v
```
## step-2: Create a new Node.js app and install dependencies
```bash
npm init -y

```
```bash
npm install twitter-api-v2 dotenv cron express

```
## Step 3: Create an .env file and load your API keys
```bash
NODE_ENV="development"
API_KEY="<your-API-key>"
API_SECRET="<your-API-secret>"
ACCESS_TOKEN="<your-access-token>"
ACCESS_SECRET="<your-access-secret>"
BEARER_TOKEN="<your-bearer-token>"
APP_ID="<your-app-id>"
```
