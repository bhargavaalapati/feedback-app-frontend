### 2\. `feedback-frontend/README.md`

# 🎨 Feedback Form & Viewer

A simple, responsive frontend for collecting and viewing feedback. It includes a form with interactive buttons and live toasts, all styled with Bootstrap.

-----

### 📚 Tech Stack

  * **Frontend:** HTML, CSS (Bootstrap 5), JavaScript
  * **Hosting:** Netlify / GitHub Pages
  * **Connection:** Communicates with a separate backend API via `fetch`.

### 📂 Project Structure

```
feedback-frontend/
│
├── index.html          # The feedback submission form
├── view.html           # The feedback viewer page
├── script.js           # The main JavaScript logic
└── README.md           # This file
```

### ⚙️ Getting Started (Local)

You can open `index.html` or `view.html` directly in your browser. However, the feedback submission and viewing features will only work if you update the `backendURL` variable to point to your live backend.

### 🚀 Key Features

  * **Submit & Redirect:** Submits feedback and redirects the user to your Google Maps review page.
  * **WhatsApp Button:** Direct link to message on WhatsApp.
  * **Light/Dark Mode:** Toggles the page's theme.
  * **Share Link:** Copies the page's URL to the clipboard.
  * **Live Toasts:** Shows a pop-up notification every 2 minutes with the latest feedback submission.

### ☁️ Deployment on Netlify / GitHub Pages

1.  **Update the Backend URL:** Open `index.html` and find the `script` tag. Replace the `backendURL` placeholder with your **live Render URL**:
    ```javascript
    const backendURL = "https://your-render-app.onrender.com/feedback";
    ```
2.  Push this entire folder to a new GitHub repository.
3.  Go to **Netlify** or **GitHub Pages** and connect it to your `feedback-frontend` repo.
4.  Netlify will automatically detect and deploy your static files, making your site live in minutes.

### 📸 Screenshots

*(Optional: Add screenshots of your feedback form and viewer pages here for a professional touch.)*
