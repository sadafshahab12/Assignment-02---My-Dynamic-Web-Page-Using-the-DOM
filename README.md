# Assignment-02---My-Dynamic-Web-Page-Using-the-DOM
### Goal
You’re going to build a complete web page using only JavaScript and the DOM, not by typing HTML elements directly.
Everything — the header, profile card, paragraph text, images, and footer — should appear automatically when the page loads.

*This assignment will show how JavaScript can build an entire page and style it dynamically.*

#### What You’ll Build

- When the page runs, it should automatically show:
- A header saying “Welcome to My Page”.
- A profile card (your name, short intro, image, and “View Profile” link).
- A paragraph section with 3–4 paragraphs — each styled differently using JavaScript.
- An image gallery showing 3–5 pictures.
- A footer that says “© 2025 My First DOM Project”.

### Step-by-Step Instructions
#### Step 1 — Set Up Your Files

- Create a folder named Assignment02_DOM.
- Inside it, make two files:
- index.html
- script.js

**In your HTML file, keep only the basic structure — just link your JS file before the closing </body> tag.
(We’ll create all content through JavaScript.)**

#### Step 2 — Create a Header
- In your script.js, create a header element (like <h1>).
- Write: “Welcome to My Page”.
- Attach this header to the body so it appears at the top.

#### Step 3 — Make Your Profile Card

- Create a container (like a <div>) for the profile.

**Inside it, create:**

- A heading with your full name.
- A short intro paragraph about yourself.
- An image element (pick any picture from the internet).
- A link that says “View Profile” and goes to your LinkedIn, GitHub, or any other site.
- Attach all these elements inside the container.
- Add that container to the body.

#### Step 4 — Add Paragraphs and Style Them

- In your HTML file, create 3–4 paragraphs with random text (already written in HTML).
- Now in your script.js, grab all those paragraphs using getElementsByTagName("p").

**Change their:**

- Colors (each one different),
- Font sizes (e.g., one small, one big),
- Background color (optional).
- Add or remove class names if you want to experiment with CSS later.

#### Step 5 — Create an Image Gallery

-  Make an array (a list) of 3–5 image URLs inside your script.
-  Example: flowers, cars, or travel pictures.
- Use a loop to go through each image in that list.
-  For each one, create an <img> element and set its src to the image link.
-  Add each image into a gallery container (like a <div>).
- Attach that gallery container to the body.

#### Step 6 — Add a Footer

- At the end of your script, create a footer paragraph.
- Text: “© 2025 My First DOM Project”.
- Add it to the bottom of the page.

#### What to Submit

index.html
script.js

**A short note (2–3 lines) explaining:**

- What you learned,
- Which part you found most interesting.

#### Pro Tips

- Write one small part, test it, then move to the next.
- If something doesn’t appear, check your console for typos.
- Always save before refreshing!
- Keep your code neat and readable — future-you will thank you.

#### Outcome

- By the end of this assignment, your page will build itself — like magic.
- No buttons, no user clicks — just pure JavaScript DOM control.
- It’ll prove you can make a living, breathing webpage using logic alone. 🌼
