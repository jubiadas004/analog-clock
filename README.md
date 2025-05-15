# 🕰️ Analog Clock

A simple and visually appealing analog clock built using **HTML**, **CSS**, and **JavaScript**. This project demonstrates DOM manipulation, CSS positioning, and JavaScript's `Date` object to create a live, ticking analog clock.

---

## 📸 Demo

![Analog Clock Screenshot](screenshot.png)  
*Live clock with rotating hour, minute, and second hands.*

---

## 🚀 Features

- Real-time analog clock
- Rotating hour, minute, and second hands
- Tick marks representing hours
- Center dot for aesthetic finish
- Smooth updates every second

---

## 📁 Project Structure

analog-clock/
│
├── clock.html # Main HTML file
├── clock-style.css # Styles for clock face and hands
├── clock.js # JavaScript for time logic and animations

yaml
Copy
Edit

---

## 🛠️ Technologies Used

- **HTML5** – Structure of the clock
- **CSS3** – Styling and layout
- **JavaScript** – Logic to calculate and rotate the clock hands

---

## 📦 Installation & Usage

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/analog-clock.git
   cd analog-clock
Open clock.html in your browser:

bash
Copy
Edit
open clock.html
# or simply double-click the file
That's it! You'll see the analog clock running and updating every second.

🧠 How It Works
The clock hands are updated every second using setInterval().

The current time is retrieved using new Date().

Angles are calculated:

Hours: 30° × hours + 0.5° × minutes

Minutes: 6° × minutes + 0.1° × seconds

Seconds: 6° × seconds

CSS transforms rotate the elements accordingly.

🤝 Contributing
Contributions are welcome! If you have improvements or new features in mind, feel free to open an issue or submit a pull request.
