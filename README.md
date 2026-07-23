# OpenCode Session Viewer

A web-based interactive viewer for OpenCode `@session.json` log files.

## Features

- **Interactive Timeline**: Quickly jump between user and assistant messages.
- **Rich Rendering**: Full Markdown support with syntax highlighting for code blocks.
- **Cost & Token Tracking**: Overview of total costs, token consumption, and model details per turn.
- **Tool & Skill Insights**: Expandable views for tool executions, synthetic context, and injected skill instructions.
- **Drag & Drop**: Drop your exported session JSON file directly into the browser to view.

## GitHub Pages Deployment

This repository includes a GitHub Actions workflow (`.github/workflows/deploy.yml`) that automatically deploys the single-page application to GitHub Pages whenever changes are pushed to the `main` branch.

### Enabling GitHub Pages

To activate deployment for your repository:

1. Navigate to your repository on GitHub (`krisvandebroek/opencode-session-viewer`).
2. Go to **Settings** > **Pages**.
3. Under **Build and deployment**, set **Source** to **GitHub Actions**.
4. Once configured, push to the `main` branch or manually trigger the workflow from the **Actions** tab.

### Hosted Site URL

Once deployed, the session viewer will be publicly accessible at:

**[https://krisvandebroek.github.io/opencode-session-viewer/](https://krisvandebroek.github.io/opencode-session-viewer/)**

## Security & Privacy

- All session JSON processing is done strictly client-side in your browser. No session data is uploaded to any server or backend.
- See [SECURITY.md](SECURITY.md) for vulnerability reporting guidelines.

## License

[MIT License](LICENSE) © 2026 Kris Vandebroek
