A lightweight, interactive web application designed to help users manage their upcoming events. This project demonstrates core CRUD (Create, Read, Update, Delete) functionality using vanilla JavaScript, modern CSS layouts, and efficient DOM manipulation techniques.
Add Events: Input a title, date, category, and description to create a custom event card.

Dynamic UI: Events are rendered instantly without a page reload.

Event Delegation: Uses a single listener on the parent container to handle deletions efficiently.

Sample Data: Quickly populate the dashboard with pre-set events for testing.

Real-time Interaction: Includes a DOM manipulation demo that tracks and displays keyboard inputs.

Responsive Styling: A clean, modern interface featuring a glass-morphism inspired background and flexbox layouts.
Technology,Purpose
HTML5,Semantic structure of the dashboard.
CSS3,"Flexbox layout, linear gradients, and component styling."
JavaScript (ES6),"DOM manipulation, event listeners, and dynamic template literals."
1. Adding an Event
The script gathers data from the input fields and passes them to the createEvent function. This function uses Template Literals to inject a new HTML block into the eventsContainer.

2. Event Delegation
Instead of attaching a listener to every "Delete" button (which would be memory-intensive), the app listens for clicks on the eventsContainer and checks if the clicked element has the .delete class.

3. Keyboard Tracking
The dashboard monitors the keydown event on the entire document, updating the "DOM Manipulation Demo" section with the specific key you pressed.

🚦 Getting Started
Clone or Download the source code files.

Ensure all three files (index.html, style.css, script.js) are in the same folder.

Open index.html in any modern web browser.

Start adding events or click "Add Sample Events" to see it in action!

🌟 Future Improvements
Local Storage: Save events so they persist after refreshing the browser.

Edit Functionality: Allow users to update existing event details.

Search/Filter: Add a search bar to filter events by category or title.
