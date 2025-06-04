# Metamask Extension E2E Docker Image

This image is built for running Metamask Extension end-to-end (E2E) tests.  
It includes:

- Node 22.15 (with browsers)
- Yarn 4.9.1 (via Corepack)
- zstd compression tool
- Xvfb for headless GUI environments

## 🚀 Build the Docker Image

```bash
docker build --platform linux/amd64 -t metamask-extension-e2e .
```

## 🏷️ Tagging the Image
Docker image tagging for release pipelines is currently done manually via the GitHub
Tagging points to the latest commit on the main branch by default.
