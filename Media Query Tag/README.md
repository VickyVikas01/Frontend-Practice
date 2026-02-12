CSS Media Queries Practice
A lightweight demonstration of responsive web design using CSS media queries. This project illustrates how background colors and typography can dynamically adapt based on the user's viewport width.

🎯 Project Purpose
The goal of this exercise was to practice setting specific "breakpoints" to change the visual state of a webpage without altering the HTML structure.

🛠️ Responsive Features
1. Dynamic Background Colors
The <body> element changes its background color based on the following width thresholds:

Viewport Width,Background Color,Logic Applied
Below 600px,🔵 Blue,max-width: 600px
601px to 1023px,🟢 Green,max-width: 1024px
1024px and Above,🔴 Red,min-width: 1024px

Note: Because CSS follows a "top-down" cascading order, the blue background (defined later in the code) overrides the green when the screen is smaller than 600px.

2. Adaptive Typography
The text "Vicky Vikas" (with the class .hide) scales its font size to ensure readability across devices:

Mobile (< 500px): 12px

Tablet (500px - 900px): 16px

Desktop (> 900px): 20px

🚀 How to Use
Clone the repository or download the media.html file.

Open the file in any modern web browser (Chrome, Firefox, Edge).

Open the Developer Tools (F12 or Right Click > Inspect).

Toggle the Device Toolbar and resize the window to watch the colors and font sizes shift in real-time.

📝 Technical Learnings
Media Query Ranges: Using min-width and max-width to create specific brackets for styles.

CSS Specificity & Order: Understanding how the order of @media rules affects which style is applied when multiple conditions are met.

Responsive Typography: Adjusting font-size to improve user experience on smaller screens.
