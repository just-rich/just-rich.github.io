# Cloudflare's pages.dev
This repository is used for hosting a website or splash page on **Cloudflare Workers & Pages**, deployed at `<name>.pages.dev`.

## Setup Instructions

1. Log into your Cloudflare account and, in the left sidebar, select **Workers & Pages**.
2. Click **Create**, select **Pages**, and then click **Connect to Git** to link your GitHub or GitLab repository.
3. If your GitHub/GitLab account isn't connected yet, follow the prompts to do so. Once connected, select the repository you want to deploy and click **Begin Setup**.
4. Configure your project:
   - Optionally change the **Project Name**.
   - For **Framework preset**, select your framework (e.g., `None` if you’re just using a simple `index.html` in the root).
5. If using a framework (e.g., Next.js, React, etc.), specify the **Build command** (e.g., `npm run build`).
   - If using `None` for a simple `index.html` in the root directory, you can leave **Build command** blank.
   - If your `index.html` is inside a subdirectory (e.g., `/docs`), specify that directory under **Root directory**.
6. Adjust any additional settings as needed, then click **Save and Deploy**.