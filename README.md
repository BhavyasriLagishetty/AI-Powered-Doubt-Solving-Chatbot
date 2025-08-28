
# AI-Powered Doubt Solving Chatbot

An intuitive web-based chatbot application that allows users (students) to ask academic doubts, and receive real-time answers powered by the Groq AI API. Built with **pure HTML**, **JavaScript**, and **jspdf**, this application brings an easily deployable solution with no backend needed.

---

## 🚀 Features

* **Interactive chat interface** with distinct styling for user vs bot messages
* **Real-time API integration** with Groq's `llama3-8b-8192` model
* Clean layout inspired by your main homepage theme: dark-blue gradient + light card UI
* **Client-side PDF export** of chat history using **jsPDF**
* Entirely runs in the browser — **no server required**
* Optional **localStorage-based history** (if previously implemented)

---

## 🛠️ Tech Stack

* **Frontend**: HTML, CSS, JavaScript
* **AI Integration**: Groq API (via `fetch` calls with bearer token)
* **PDF Export**: `jsPDF` library
* (Optional) **Local persistence**: `localStorage`

---


## ⚙️ Setup & Usage

1. **Clone this repo**

   ```
   git clone https://github.com/BhavyasriLagishetty/AI-Powered-Doubt-Solving-Chatbot.git
   cd AI-Powered-Doubt-Solving-Chatbot
   ```

2. **Add your API Key**
   Open `chatbot.html`, locate:

   ```js
   const GROQ_API_KEY = "YOUR_API_KEY";
   ```

   Replace `"YOUR_API_KEY"` with your valid Groq API key.

3. **Open in browser**
   Simply double-click `chatbot.html`, and the chatbot UI appears.
   (Or host on GitHub Pages for a live deployment)

4. **Chat and Export**

   * Ask a question → bot responds
   * Click “Save as PDF” to download the entire convo in PDF format

---

## 🎨 Customizing the UI

The default color scheme matches your main homepage:

* **Background**: Dark navy gradient
* **Chat container**: Light card-style
* **User bubbles**: Blue with white text
* **Bot bubbles**: Green with white text
* **Save button**: Yellow highlight

You can modify the colors and fonts directly in the `<style>` section within `chatbot.html`.

---

## ✅ Why Use This?

* **Easy to deploy** — no servers, frameworks, or databases needed
* **Privacy-friendly** — everything runs client-side
* **Thematic consistency** — blends seamlessly with your main portal
* **Portable expertise** — ideal for doubt-solving, study guides, or help desks

---

## 📦 Optional Enhancements

Consider upgrading this project with:

* A **backend proxy** to secure the API key (Node.js / Flask / PHP)
* **Persistent chat history** across visits with `localStorage` or a small database
* A more scalable **doubt management backend** (e.g., Firebase, Supabase)
* **User authentication** for student accounts and history
* Rich formatting: syntax highlight, image support, or response suggestions

---

## 📬 Questions or Contributions?

Feel free to open an issue on this repo if you find a bug, or want help setting it up.
Fork it to experiment, re-theme, or expand the functionality as needed!

---

### 🧩 Summary Table

| Component  | Purpose                                     |
| ---------- | ------------------------------------------- |
| HTML/CSS   | Lightweight UI with theme consistency       |
| JavaScript | Handles chat input, API calls, PDF export   |
| Groq API   | Generates responses using `llama3-8b`       |
| jsPDF      | Converts chat history into downloadable PDF |

---

Thanks for checking out this chatbot project!
Hope it serves well for academic doubt-solving, student support, or demonstrations of AI integration in web interfaces. 😊
