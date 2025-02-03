🎡 Lucky Wheel

This project creates a Lucky Wheel using JavaScript. Users can click the “Spin the Wheel” button to spin the wheel and win various prizes. 🍀

🚀 Features
	•	Customizable Wheel: Different prizes and colors can be configured.
	•	Spinning Wheel Animation: Animated wheel using GSAP and Winwheel.js.
	•	Prize Display: The winning prize is displayed on the screen when the wheel stops.
	•	Win & Lose Scenarios: A special message appears if you don’t win.

📸 Preview

🛠️ Technologies Used
	•	HTML – For structure and elements
	•	CSS – For stylish design
	•	JavaScript (Winwheel.js & GSAP) – For wheel animation and interactions

📦 Installation

Follow these steps to run the project:
	1.	Clone the repository
```
git clone https://github.com/Mucahitakin/Wheel.git
cd Wheel

```
2.	Open the file in your browser
```
index.html
```


🎮 How to Play
	1.	Open the page and click the “Spin the Wheel” button.
	2.	The wheel will stop at a random position, and your prize will be displayed. 🎁
	3.	Try your luck again!

🎨 Customization

To change the prizes and colors, modify the items array:
```
var items = [
    { 'text': '10% Domain Discount', 'fillStyle': '#38A0E6' },
    { 'text': '20% Hosting Discount', 'fillStyle': '#FCA628' },
    { 'text': 'Free Personal Hosting', 'fillStyle': '#E65051' },
    ...
];
```
