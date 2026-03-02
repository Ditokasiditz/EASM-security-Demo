# EASM Security Demo

This is a frontend demonstration project for an External Attack Surface Management (EASM) dashboard, built with React, TypeScript, and Vite.

## What is ASM (Attack Surface Management)?

**Attack Surface Management (ASM)**, and specifically **External Attack Surface Management (EASM)**, is the continuous process of discovering, analyzing, and managing vulnerabilities and potential attack vectors on an organization's external-facing IT assets. 

In simpler terms, it's about looking at your organization from a hacker's perspective. It involves:
- **Discovery:** Finding all internet-connected assets belonging to your organization (domains, subdomains, IP addresses, open ports, web applications, cloud services, etc.).
- **Inventory:** Keeping an up-to-date repository of these exposed assets.
- **Analysis & Prioritization:** Assessing the risk of each asset based on vulnerabilities, misconfigurations, outdated software, or exposed sensitive information.
- **Monitoring:** Continuously watching for changes in the attack surface, as new assets are deployed or configurations are altered.

EASM solutions help organizations proactively identify blind spots before attackers can exploit them.

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development purposes.

### Prerequisites

You will need to have Node.js installed on your machine to run this frontend application.
- [Node.js](https://nodejs.org/) (v18 or newer is recommended)

### Installation & Running Locally

1. **Clone the repository**
   Open your terminal and clone the repository to your local machine:
   ```bash
   git clone <your-repository-url-here>
   cd EASM-security-Demo
   ```

2. **Install dependencies**
   You can use `npm`, `yarn`, `pnpm`, or `bun`. Use the package manager of your choice to install the project dependencies:
   ```bash
   npm install
   # or
   yarn install
   # or
   pnpm install
   ```

3. **Start the development server**
   Once the dependencies are installed, start the Vite development server:
   ```bash
   npm run dev
   # or
   yarn dev
   # or
   pnpm dev
   ```

4. **View the application**
   Open your web browser and navigate to the URL provided in your terminal output (typically `http://localhost:5173`).

## Available Scripts

In the project directory, you can run:

- `npm run dev` - Starts the development server.
- `npm run build` - Builds the app for production to the `dist` folder.
- `npm run lint` - Runs ESLint to check for code quality issues.
- `npm run preview` - Locally preview the production build.
