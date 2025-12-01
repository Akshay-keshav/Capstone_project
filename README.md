 🧱 Features
- **Responsive Navigation Bar** – Allows users to navigate between sections easily.  
- **Hero Section** – Engaging welcome banner with a call-to-action message.  
- **Destinations Section** – Displays top travel destinations using responsive image cards.  
- **Packages Section** – Lists tour packages with pricing.  
- **Contact Form** – Simple input field and a submit button that displays a thank-you message using JavaScript.  
- **Customer Reviews** – Highlights feedback from previous travelers.  
- **Footer** – Contains copyright information.
💻 Technologies Used
- **HTML5** – Structure of the webpage  
- **CSS3** – Styling and responsive layout  
- **JavaScript (ES6)** – Adds interactivity to the contact form
 ⚙️ How It Works
1. Open `index.html` in any modern web browser.  
2. Scroll through the sections: Home → Destinations → Packages → Contact.  
3. Enter your name in the contact field and click **Submit** to see a personalized thank-you message.  
4. The website adapts to various screen sizes due to the use of `flexbox` and responsive styling.
 🖼️ Screenshots (Optional)
You can add screenshots of the main sections here:
- Home section with banner
- Destination cards
- Reviews section
- 🧠 JavaScript Functionality
The JavaScript file includes a simple function:

```js
function showMsg() {  
  var name = document.getElementById("name").value;
document.getElementById("msg").innerHTML = "Thank you " + name + "!";
}
  document.getElementById("msg").innerHTML = "Thank you " + name + "!";
}
