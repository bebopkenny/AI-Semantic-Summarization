# AI Summarizer


An AI-powered article summarizer built with **React.js**, **TailwindCSS (v3)**, and **RapidAPI**. This tool extracts and condenses long-form content into concise summaries using OpenAI's GPT-based summarization API. It also stores a history of previously summarized articles, allowing users to revisit and copy past URLs easily.

---

### Live Demo
You can view the live demo of this project here: [summarizer.kennygarcia.net](https://summarizer.kennygarcia.net)

---

## 🚀 Features


- 🌐 **AI-Powered Summarization** – Uses GPT-based API to generate summaries.
- 📝 **URL History Tracking** – Stores previously entered URLs in local storage.
- 📋 **Easy Copy & Paste** – Quickly access and reuse past URLs.
- 🎨 **Modern UI** – Styled with TailwindCSS for a sleek and responsive design.
- ⚡ **Fast Performance** – Built with Vite for optimized speed and efficiency.

---

## 🖥️ Tech Stack


- **Frontend:** React.js, TailwindCSS (v3)
- **API Integration:** RapidAPI (Article Summarization API)
- **Build Tool:** Vite
- **Storage:** Local Storage for saving user history

---

## 📂 Project Structure

```bash
AI-Summarizer/
│── src/                # Source code
│   ├── assets/         # Static assets
│   ├── components/     # Reusable React components
│   ├── services/       # API calls and state management
│   ├── App.jsx         # Main app component
│   ├── main.jsx        # Entry point
│── public/             # Static public files
│── index.html          # HTML file
│── package.json        # Dependencies and scripts
│── tailwind.config.js  # Tailwind CSS configuration
│── vite.config.js      # Vite configuration
│── README.md           # Project documentation
```

---

## 🔧 Installation & Setup 
1. Clone the repository:
  ```sh
  git clone https://github.com/your-username/ai-summarizer.git
  cd ai-summarizer
2. Install dependencies:
  ```sh
  git clone https://github.com/your-username/ai-summarizer.git
  cd ai-summarizer
  ```
3. Set up environment variables:
  - Create a ```.env``` file in the root directory.
  - Add your **Rapid** key:
  ```sh
  VITE_RAPID_API_ARTICLE_KEY=your_api_key_here
  ```
4. Start the development server:
   ```sh
   npm run dev
   ```

---

## 📌 Usage
1. Enter a URL in the input field.
2. Click the submit button to generate a summary.
3. The summarized text will be displayed below.
4. Previously summarized URLs are saved in local storage for easy access.

---

## 🛠️ Deployment
To build project for production:
  ```sh
  npm run build
  ```
To deploy on Netlify, Vercel, or any static hosting platform, upload the ```dist/``` folder.

---

## 📝 License
This project is open-source under the **MIT License**.

---

## 💡 Contributions & Suggestions are Welcome!
If you have ideas to improve the project, feel free to submit a pull request or open an issue.

---
## 📧 Contact

For any inquiries or feedback, please reach out:

- **Name**: Kenny Garcia
- **LinkedIn**: [linkedin.com/in/kennygarcia15](https://linkedin.com/in/kennygarcia15/)
- **Portfolio**: [kennygarcia.net](https://kennygarcia.net)
- **Email**: [kennygarcia15@yahoo.com](mailto:kennygarcia15@yahoo.com)
