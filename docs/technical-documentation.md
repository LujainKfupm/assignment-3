# Technical Documentation

## 📂 Project Structure
```
assignment-1/
├── index.html       Main HTML file
├── css/
│   └── styles.css   Styling rules
├── js/
│   └── script.js    Interactivity
├── assets/
│   └── images      Placeholder images
├── docs/
│   ├── ai-usage-report.md
│   └── technical-documentation.md
└── README.md
```


## Key Components

### 1) Dynamic Content
- **Project Filter**
    - HTML: three buttons 
    - Cards: each card has a `data-category`.
    - JS: applies filter, shows empty when none visible.
    - saves selected filter to `localStorage`.
    - live search bar.

- **Greeting**
    - JS computes part of day (morning/afternoon/evening) and sets the greeting.

- **Inspiring Quote**
    - JS fetches from ZenQuotes and fades card in.

### 2) Data Handling
- Theme and Project Filter stored in `localStorage`.

### 3) Validation & Feedback
- Minimal inline errors for name/email/message and success text.

### 4) Styling & Transitions
- quote card fades/slide-in using.
- faded card for search results.



