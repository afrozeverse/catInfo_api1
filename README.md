# 🐱 Cat Info Fetcher using API

This is a simple front-end project that demonstrates how to work with **REST APIs** using **JavaScript's Fetch API**. When the user clicks a button, it fetches a random **cat fact** from an external API and displays it dynamically on the page.

## 🚀 Features

- Fetches live data using `fetch()` and `async/await`
- Handles API response and displays it on the webpage
- Simple and clean UI using HTML & CSS
- Styled interactive button with hover effect
- Error handling with `try-catch`
## 🌐 Live API Used

- [Cat Fact API](https://catfact.ninja/fact) — a free RESTful API that provides random cat facts.

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
  
## 📸 Screenshot
<img width="885" height="498" alt="Screenshot (176)" src="https://github.com/user-attachments/assets/12eab97b-23c9-431f-8042-92aeafb04a51" />

## 🧠 How It Works

1. User loads the page and sees a static message.
2. On clicking the **Click** button:
   - The `fetch()` API is called with the endpoint `https://catfact.ninja/fact`
   - The response is converted to JSON
   - The `fact` string is extracted and displayed in a styled box
   - If there's an error (like no internet), it's logged in the console
   
## 🎯 Purpose of This Project
This project was created to **showcase my API handling skills** using modern JavaScript. It's a beginner-friendly demonstration of:
- Making GET requests
- Updating the DOM dynamically
- Styling with CSS for better UI
