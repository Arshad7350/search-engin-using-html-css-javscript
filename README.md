# 🔍 Image Search Engine

A simple, user-friendly image search engine built using **HTML**, **CSS**, and **Vanilla JavaScript**, powered by the [Unsplash API](https://unsplash.com/developers). Search for high-quality images by keyword and load more results dynamically.

---

## 🌐 Live Demo

[Click here to view live](#) <!-- Replace with actual link if deployed -->

---

## 📸 Preview

![Preview](preview.png) <!-- Optional: Add a screenshot of your project -->

---

## 📁 Project Structure

Image-Search-Engine/
├── index.html # Main HTML structure
├── style.css # Styling for UI
├── script.js # JavaScript logic (API calls, dynamic content)


---

## 🚀 Features

- 🔎 Search any keyword to get image results from Unsplash
- 📄 Paginated image results with "Show More" button
- 🖼️ Clickable image links open in a new tab (to original Unsplash page)
- ⚡ Clean, responsive layout with fast search capability

---

## 🧪 How It Works

- On form submission:
  - Sends a request to the Unsplash API with the user’s query
  - Displays 12 image results per page
  - Resets previous results on new search
- On clicking **Show More**:
  - Increments the page count
  - Appends more images to the results container

---

## 🛠️ Technologies Used

- **HTML5**  
- **CSS3**  
- **JavaScript (ES6)**  
- **Unsplash API** – for fetching image results

---

## 🔑 API Key Setup

This project uses the [Unsplash API](https://unsplash.com/developers) to fetch images.

Your key is currently hardcoded:

```js
const accessKey = "yml6OEaovIBn2xhc7sCUjPaK4mQMItVh9m-d6xLirS0";


---
