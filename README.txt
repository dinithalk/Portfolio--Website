HOW TO EDIT YOUR PORTFOLIO WEBSITE / WEBSITE EKA EDIT KARANA VIDIYA
========================================================================

Machan, here is how you can edit the website content easily.
Me widiyata website eke visthara wenas karaganna puluwan.

1. Open `index.html` file in a text editor (Notepad, VS Code, Sublime Text).
   (Oyaa `index.html` file eka open karanna text editor ekakin).

2. CHANGING TEXT (Wachana wenas kireema):
   - Find the text you want to change (Example: "Dinitha Chanketh").
   - Replace it with your new text.
   - Example:
     Change: <h1>Hi, I'm Dinitha Chanketh</h1>
     To:     <h1>Hi, I'm [Your Name]</h1>

3. CHANGING IMAGES (Photos wenas kireema):
   - Find the `<img>` tag.
   - Change the `src="..."` part to your image file name or URL.
   - Example:
     <img src="https://ui-avatars.com/..." ...>
     Change to:
     <img src="my-photo.jpg" ...>
   - Make sure to put your photo inside the portfolio folder first!

4. CHANGING THE "TYPEWRITER" ROLES (Eg: Software Engineer, AI Enthusiast...):
   - Open `script.js`.
   - Look for this line:
     const roles = ["Software Engineer Student", "AI Enthusiast", ...];
   - Change the text inside the quotes.

5. CHANGING COLORS (Paata wenas kireema):
   - Open `index.html`.
   - Scroll to the top `<script>` tag where `tailwind.config` is.
   - Change the hex codes in `primary` and `secondary` colors.
     colors: {
         primary: '#0ea5e9',  <-- Change this color code
         secondary: '#8b5cf6', <-- Change this color code
         ...
     }

FILES INCLUDED:
- index.html (Main website)
- style.css (Animations and effects)
- script.js (Interactivity)

Enjoy your supiri website!
Deiyan pihitai machan!
