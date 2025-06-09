# SKNCRE - Cosmetics Brand E-commerce Demo

This project is a functional e-commerce demo for "SKNCRE", a fictional cosmetics brand. It was built to demonstrate a modern web development stack, featuring a headless architecture with Hygraph and a fast, content-driven front-end powered by Astro.

**➡️ [View the live demo here](https://skncre-cosmetics-hygraph-astro.vercel.app/)**

---

### 📸 Project Screenshot

![Screenshot of the SKNCRE project](https://path/image.png)

---

## 🎯 About The Project

SKNCRE is a proof-of-concept website designed to showcase how a modern e-commerce platform can be built using a Headless CMS for content management and a static-site generator for a fast and secure user experience. All product data, categories, and promotional content are managed through Hygraph and fetched via a GraphQL API.

## ✨ Key Features

- **Headless Architecture:** Content is decoupled from the front-end, managed entirely in a Headless CMS.
- **Statically Generated:** Built with Astro for excellent performance, security, and SEO.
- **GraphQL Powered:** Uses GraphQL for efficient and precise data fetching from the CMS.
- **Developer-Friendly:** Includes a codegen script to generate TypeScript types directly from the GraphQL schema.

## 🛠️ Technologies Used

- **[Astro](https://astro.build/)** (Front-end Framework)
- **[Hygraph](https://hygraph.com/)** (Headless CMS)
- **[GraphQL](https://graphql.org/)** (API Query Language)
- **[TypeScript](https://www.typescriptlang.org/)**

## 🚀 Getting Started & Running Locally

To get a local copy up and running, follow these steps. You will need [Node.js](https://nodejs.org/) installed.

1.  **Clone the repository:**
    ```sh
    git clone <YOUR_REPOSITORY_URL>
    ```

2.  **Install dependencies:**
    ```sh
    cd <PROJECT_FOLDER_NAME>
    npm install
    ```

3.  **Set up Environment Variables:**
    - Create a file named `.env` in the root of the project.
    - Inside, you'll need to add your Hygraph project's Content API endpoint. See `.env.example` for reference.
    ```
    GQL_HOST=https://<YOUR_HYGRAPH_ENDPOINT_URL>
    ```
    *Note: Ensure your Hygraph API settings allow public content viewing access.*

4.  **Generate GraphQL Types:**
    - This command introspects your GraphQL schema and generates corresponding TypeScript types.
    ```sh
    npm run codegen
    ```

5.  **Start the Development Server:**
    ```sh
    npm run dev
    ```
    The site will be available at `http://localhost:4321`.

## 👤 Author

**Diego Leite**
-   **GitHub:** [leitdiegousp](https://github.com/leitdiegousp)
