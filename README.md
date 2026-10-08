# Basic Informational Site

A simple Node.js and Express web server that serves custom HTML pages (`index`, `about`, `contact-me`) and handles `404 Not Found` routes using standard HTTP request routing.

---

## 🚀 Features

- **Single Port Architecture:** Serves multiple pages from a single backend server port.
- **Express Routing:** Directs requests cleanly to specific HTML documents.
- **Custom 404 Page:** Intercepts invalid URLs and renders a friendly error page.
- **Clean Structure:** Uses modern ES Module (`import/export`) syntax.

---

## 📁 Project Structure

```text
basic-information-site/
├── index.js          # Express server & route definitions
├── index.html        # Home page
├── about.html        # About Us page
├── contact-me.html   # Contact Me page
├── 404.html          # Catch-all error page
├── package.json      # Project dependencies & scripts
└── .gitignore        # Ignored files (node_modules, environment variables)


clone the project:
git clone [https://github.com/Henry3029/basic-information-site.git](https://github.com/Henry3029/basic-information-site.git)
cd basic-information-site


Install dependencies:
npm install


start server
node index.js


Open in browser:
Navigate to http://localhost:8080 (or your configured server port).


Available Routes
/ \rightarrow Serves index.html
/about \rightarrow Serves about.html
/contact-me \rightarrow Serves contact-me.html
/* (Any unknown route) \rightarrow Serves 404.html

This project is open-source and available under the MIT License.


<FollowUp label="Want to add a license file (LICENSE) or npm script shortcuts to your package.json?" query="Show me how to configure script shortcuts like 'npm start' and 'npm run dev' in my package.json."/>