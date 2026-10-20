# BIC21203 Web Development — Lab #4b: Client-Side Scripting (JSON and jQuery)

Academic Session：2026/2027  
Course Code / Name:BIC21203 Web Development  
Name:TAY YU SHIN
Student ID:AI250228
Topic: Web page development using JSON, modern JavaScript, and jQuery  
---
## 📌 Project Overview 

This repository contains the completed work for Lab #4b: Client-Side Scripting (JSON and jQuery). The primary focus is to demonstrate how to retrieve, parse, and render JSON datasets using modern JavaScript (`fetch()` API) and to compare native JavaScript DOM/event operations with equivalent jQuery implementations.
---

## 📁 Repository Structure

.
├── books.json          # Question 1: Valid JSON dataset containing book records
├── books.html          # Question 2: HTML page fetching and displaying JSON data via async/await
├── jquery-dom.html     # Question 3: HTML page demonstrating DOM updates and events via jQuery 4.0.0[cite: 1]
└── README.md           # Project documentation and setup instructions[cite: 1]

## Test Results & Screenshots
Question 1
<p>
<img width="532" height="407" alt="Screenshot 2026-10-20 135122" src="https://github.com/user-attachments/assets/ff4ccfb8-2935-487b-918a-9460bab67724" />
</p>

Question 2
<p>
<img width="572" height="353" alt="Screenshot 2026-10-20 134751" src="https://github.com/user-attachments/assets/cbbeff01-f0e7-434f-aec5-c7616949a289" />
</p>

Question 3
<p>
<img width="1848" height="245" alt="Screenshot 2026-10-20 135751" src="https://github.com/user-attachments/assets/7fe30bb2-7485-4ab0-8419-38c45ea67988" />
<img width="1837" height="350" alt="Screenshot 2026-10-20 135940" src="https://github.com/user-attachments/assets/2c818e9e-2b16-4f14-802b-72d3e8e37a58" />
</p>

One Advantage of Native JavaScript:
<p>
No External Dependencies & Higher Performance. Modern web browsers natively support JavaScript DOM manipulation and APIs such as fetch(). Using native JavaScript eliminates the need to download third-party libraries, reducing HTTP requests, lowering bandwidth consumption, and leading to faster initial page loading times.
</p>
One Situation Where an Existing Project May Still Use jQuery:
<p>
Maintaining Legacy Enterprise Systems. Many established web applications were built with jQuery in their early architecture. Completely refactoring these large codebases into modern frameworks or vanilla JS would incur high cost and unexpected regression risks. Therefore, teams continue to use jQuery to maintain system stability and maintainability.
</p>
