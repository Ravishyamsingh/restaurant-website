<div align="center">
  <h2 align="center">Hyatt - Restaurant Website</h2>

  Hyatt is a fully responsive restaurant website, <br />responsive for all devices and built using HTML, CSS, and JavaScript.
</div>

<br />

### Demo Screeshots

![Hyatt Desktop Demo](./readme-images/desktop.png "Desktop Demo")

### Prerequisites

Before you begin, ensure you have met the following requirements:

* [Git](https://git-scm.com/downloads "Download Git") must be installed on your operating system.

### Run Locally

To run **Hyatt** locally, run this command in Git Bash:

Linux and macOS:

```bash
git clone https://github.com/Ravishyamsingh/restaurant-website.git
```

Windows:

```bash
git clone https://github.com/Ravishyamsingh/restaurant-website.git
```

### Deploy to Cloudflare Pages

This is a static website and requires no build command.

1. Sign in to the [Cloudflare dashboard](https://dash.cloudflare.com/).
2. Open **Workers & Pages** and select **Create application** → **Pages** → **Connect to Git**.
3. Choose GitHub and select `Ravishyamsingh/restaurant-website`.
4. Use these build settings:
   - **Framework preset:** `None`
   - **Build command:** leave empty
   - **Build output directory:** `.`
   - **Root directory:** `/` (repository root)
5. Select **Save and Deploy**.

Cloudflare Pages will automatically redeploy whenever changes are pushed to the selected GitHub branch. The [`_headers`](./_headers) file configures security headers and long-term caching for static assets.

### Author

Ravi Shyam Singh ([Ravishyamsingh](https://github.com/Ravishyamsingh))

### License

[MIT](https://choosealicense.com/licenses/mit/)
