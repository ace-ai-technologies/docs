# AceAI Documentation

This repository contains the source code for the AceAI documentation. It serves as a central hub for guides, API references, and resources to help users understand and work with AceAI.

## Getting Started

To contribute to the documentation or preview changes locally, follow these steps:

### Prerequisites

Ensure you have the following installed on your system:
- [Node.js](https://nodejs.org/) (LTS version recommended)
- [npm](https://www.npmjs.com/) (comes with Node.js)

-0-
### Development Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/ace-ai-technologies/docs.git
   cd docs
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Open your browser to `http://localhost:3000` to view the documentation.

### Deployment

Changes pushed to the main branch will be automatically deployed to the live documentation site. Ensure all contributions are reviewed and approved before merging.


## Troubleshooting

- **Development server not starting**: Delete `node_modules` and `package-lock.json`, then reinstall dependencies:
  ```bash
  rm -rf node_modules package-lock.json
  npm install
  ```
- **Page not found (404)**: Ensure the page exists in the `/pages` directory and is correctly linked in the navigation.
