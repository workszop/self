# Self operating website
**self** is self operating website using Alibaba [page-agent](https://github.com/alibaba/page-agent)

The site loads a self-hosted `page-agent.bundle.js` and initializes `PageAgent` with the OpenAI-compatible Cloudflare Worker endpoint at `https://agent.andrzey-jankowski.workers.dev/`. It also uses the quiet feedback pattern from `workszop/agent`: history is hidden by default, automatic expansion is suppressed, and a compact steps toggle exposes agent progress when needed.
