

# **GenieDock**

<p align="center">
   <img src="https://img.shields.io/badge/Next.js-15.1.6-green" alt="Next.js">
  <img src="https://img.shields.io/badge/React-19.0.0-green" alt="React">
  <img src="https://img.shields.io/badge/Drizzle ORM-0.39.3-blue" alt="Drizzle ORM">

</p>

**GenieDock** is a privacy-focused, all-in-one interface designed to help users interact seamlessly with their favorite LLMs locally. It supports both [**Ollama models**](https://ollama.com/search) and [**OpenRouter**](https://openrouter.ai/), offering a streamlined and customizable experience.

> **NEW** - added support for Open Router! Some models are free! Requires API key!

The core idea is to provide an **all-in-one** solution that runs **privately** on your **localhost**.

The main focus is on being **FREE**, **OPEN SOURCE**, and **PRIVATE**.



## **Features**

✅ **Multiple Profiles** – Create unique profiles for different household members.

✅ **Stream Chat Interface with Markdown Support** – Enjoy a modern, real-time chat experience like you would expect!

✅ **Document-Based RAG** – Upload documents to enhance retrieval-augmented generation (RAG) - feed your knowledge to the model.

✅ **Model Management & Customization** – Swap models,pull models, create you own by adjusting parameters like temperature or context size

✅ **Chat Storage** – Securely save conversations in a database and resume them anytime.

✅ **Prompt Library** – Store frequently used prompts for quick access.

✅ **Personalized Settings** – Define your name and default system prompts.

✅ **Voice support** – Tired of typing? Full voice support included!

✅ **Light/Dark themes** – Supports both light and dark theme to suit your style!

✅ **Responsive Design** – Use the app on all devices no matter the screen size!

---

## **Architecture**

**GenieDock** consists of several parts:

- **App** - A modern GUI interface built with Next.js.
- **Database** - PostgreSQL database with vector support to store all your data
- **Ollama API** - Ollama API to interact with local models

---

## **Tech stack**

| Component    | Technology                          |
| ------------ | ----------------------------------- |
| **App**      | Next.js + TypeScript                |
| **Database** | Drizzle ORM + PostgreSQL + PgVector |
| **Styling**  | Tailwind CSS                        |

---

## How to Use

To get started with development, follow these steps:

1. **Prerequisites**:

   - Ensure the **Ollama API** is installed.
   - Install **Docker** to set up the PostgreSQL database.
   - Dont forget to run **Drizzle** migrations via `npx drizzle-kit migrate` command too setup your DB tables

2. **Configuration**:

   - Create a `.env` file based on the provided `env.example` template and configure it with your settings.

3. **Setup and Run**:
   - Run `npm install` to install the required dependencies.
   - Start the application by running `npm run dev`.


