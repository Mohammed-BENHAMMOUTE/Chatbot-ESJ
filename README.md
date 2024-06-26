# ChatBot Project - README

## Project Overview

This project involves the development of a ChatBot aimed at supporting doctors by answering their frequently asked questions related to eESJ (Electronic Health Records System) and assisting them in accessing pertinent medical information. The ChatBot operates in two modes:
- **Synchronous Mode:** During patient consultations, as needed.
- **Asynchronous Mode:** At any time, as an alternative to tele-expertise.

The ChatBot is designed to respond to common questions from doctors on medical, pharmaceutical, and administrative topics. It provides up-to-date and verified information on diagnostics, treatments, medical protocols, and medications. It can connect (via API) to various eESJ modules to help access information on medical records, IES (Information Exchange Systems), etc.

## Features

- **Medical Information:** Provides accurate and up-to-date information on diagnostics, treatments, protocols, and medications.
- **Synchronous Support:** Available during patient consultations to provide real-time assistance.
- **Asynchronous Support:** Accessible at any time for non-urgent queries.
- **API Integration:** Connects to eESJ modules to access medical records and other information systems.
- **Tele-Expertise:** Powered by transcripts of discussions between doctors, enhancing the knowledge base.
- **Programmable Prompting:** Configurable to align the discussion context with the doctor’s specialty.
- **Newsletter Integration:** Summarizes discussions for a newsletter intended for doctors.

## Installation

To install and run this project, you need to have `yarn` installed. Follow the steps below:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/chatbot-project.git
    cd chatbot-project
    ```

2. **Install dependencies:**
    ```bash
    yarn install
    ```

3. **Run the development server:**
    ```bash
    yarn dev
    ```

    The development server will start on `http://localhost:3000`.

4. **Build the project for production:**
    ```bash
    yarn build
    ```

5. **Start the production server:**
    ```bash
    yarn start
    ```
## Environment Variables
Create a .env.local file in the root directory to store your environment variables:
```plaintext
API_KEY=your_api_key
API_URL=https://api.example.com
```
