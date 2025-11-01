# 📝 Wikipedia Article Scraping

A Python script to fetch key details from any Wikipedia article — just enter your topic name!

---

## ✨ Features

- **Fetches live Wikipedia articles by topic**
- **Prints article title and first summary paragraph**
- **Extracts and displays up to 5 main article headings**
- **Lists 5 related Wikipedia links from the article**
- **Handles errors for unavailable topics or connection issues**

---

## 🚀 How to Run

1. Make sure Python is installed.
2. Install required packages: `pip install requests beautifulsoup4`
3. Save the script as `scraping.py`.
4. Run in your terminal/command prompt: `python scraping.py`
5. Enter a topic, e.g.: Enter a topic to search on Wikipedia: Python (programming language)

---

## 💡 Example Output

--- Wikipedia Article Details ---

Title: Python (programming language)

Summary: Python is a high-level, general-purpose programming language...

Headings:

History

Features and philosophy

Syntax and semantics

Libraries

Development environments

Related Links:

https://en.wikipedia.org/wiki/Guido_van_Rossum

https://en.wikipedia.org/wiki/Programming_language

...

---

## 🛠 How it Works

- Forms a Wikipedia article URL from your input.
- Requests the article HTML (using a User-Agent header to avoid blocking).
- Uses BeautifulSoup to extract the title, summary, main headings, and related article links.

---

## 📄 License

MIT License — Use, modify, or share freely.

---

Search Wikipedia from your terminal and get fast, friendly results!
