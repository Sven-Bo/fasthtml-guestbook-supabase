# Sven's Guestbook (Supabase Version)

A simple, real-time guestbook application built with:
This version is based on the [original FastHTML Guestbook](https://github.com/Sven-Bo/fasthtml-guestbook) but uses Supabase for the database instead of Google Sheets.

- [FastHTML](https://fastht.ml): A Python framework for building HTML applications
- [HTMX](https://htmx.org): For seamless AJAX requests and updates
- [Supabase](https://supabase.io): For database storage and management

👋 Say hi: [https://guestbook.pythonandvba.com](https://guestbook.pythonandvba.com)

![Website Demo](assets/demo.gif)


## Inspiration
This project was inspired by [Matt's Guestbook](https://github.com/mattppal/fasthtml-guestbook/tree/main). Thanks, Matt! 🙏


## Video Tutorial (Coming soon!)
[![YouTube Video](https://img.youtube.com/vi/XXX/0.jpg)](https://youtu.be/XXX)

## Setup

### Prerequisites

To set up the guestbook, you'll need:

- **Python 3.x** installed on your system.
- **Supabase Account:** Sign up at [https://supabase.io](https://supabase.io) if you haven't already.
- **Supabase Project:** Create a new project in Supabase and note down your project URL and API key.

### Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/Sven-Bo/fasthtml-guestbook-supabase.git
   cd fasthtml-guestbook-supabase
   ```

2. **Install Dependencies:**

   Install the required Python packages using \`pip\`:

   ```bash
   pip install supabase-py python-dotenv pytz fasthtml
   ```

3. **Set Up Supabase:**

   - Create a new table named `guestbook` in your Supabase project with the following columns:
     - `id` (int8, primary key)
     - `name` (text)
     - `message` (text)
     - `timestamp` (text)

   - Create a `.env` file in the root directory of your project with the following content:
     ```
     SUPABASE_URL=your_supabase_project_url
     SUPABASE_KEY=your_supabase_api_key
     ```
   Replace `your_supabase_project_url` and `your_supabase_api_key` with your actual Supabase project URL and API key.

4. **Run the Application:**

   Start the server by running:

   ```bash
   python main.py
   ```

   Visit `http://localhost:5001` in your browser to see the guestbook in action.

## Deployment

You can deploy this guestbook application using your preferred hosting service. Follow the steps in the [FastHTML documentation](https://docs.fastht.ml/tutorials/by_example.html#deploying-your-app) to learn how to deploy your application.

## 🤝 Connect with Me
- 📺 **YouTube:** [CodingIsFun](https://youtube.com/c/CodingIsFun)
- 🌐 **Website:** [PythonAndVBA](https://pythonandvba.com)
- 💬 **Discord:** [Join the Community](https://pythonandvba.com/discord)
- 💼 **LinkedIn:** [Sven Bosau](https://www.linkedin.com/in/sven-bosau/)
- 📸 **Instagram:** [sven_bosau](https://www.instagram.com/sven_bosau/)

## Support 
If you appreciate the project and wish to encourage its continued development, consider [supporting my work](https://pythonandvba.com/coffee-donation).
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://pythonandvba.com/coffee-donation)

## Feedback & Collaboration
For feedback, suggestions, or potential collaboration opportunities, reach out at contact@pythonandvba.com.
![Logo](https://www.pythonandvba.com/banner-img)
