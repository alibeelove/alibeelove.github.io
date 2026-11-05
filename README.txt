ALISON CAUCHI — ABSTRACT ART WEBSITE

CONTENTS
- index.html: complete one-page artist website
- styles.css: responsive visual design
- script.js: mobile navigation and current-year footer

HOW TO VIEW
1. Extract this ZIP file (right-click it and choose Extract All).
2. Open index.html in a web browser.

HOW TO REPLACE THE SAMPLE GALLERY ARTWORK WITH YOUR OWN PAINTINGS
The gallery currently uses sample abstract graphics. Follow these steps to show photos of your own paintings:

1. Take or prepare clear photos of your paintings. Use JPG, JPEG, PNG or WebP files.
2. In the extracted website folder, create a new folder named images.
3. Copy your painting photos into the images folder. Use simple filenames, for example:
   garden-of-love.jpg
   layers-of-life.jpg
   emotions.jpg
   where-light-begins.jpg
4. Open index.html in a text editor such as Notepad (right-click index.html > Open with > Notepad).
5. Find the gallery section. For each artwork, replace the existing <div class="artwork ..."> ... </div> sample graphic with an image tag. For example, replace the first artwork graphic with:

   <div class="artwork">
     <img src="images/garden-of-love.jpg" alt="Garden of Love by Alison Cauchi">
   </div>

   Repeat for the other gallery paintings, changing the image filename and alt text to match each painting. Keep the surrounding <article class="art-card"> and artwork title/description in place.
6. Save index.html. Open or refresh it in your browser to check that your paintings appear.
7. If an image does not appear, check that the image is inside the images folder and that its filename (including extension and capitalization) matches the src value exactly.

OPTIONAL: REPLACE THE LARGE HOMEPAGE SAMPLE ARTWORK
The large artwork on the homepage is also a sample graphic. In index.html, find <div class="hero-art" ...> and replace the entire hero-art block with:

   <div class="hero-art">
     <img src="images/my-featured-painting.jpg" alt="Abstract painting by Alison Cauchi">
   </div>

Use the filename of the photo you copied into the images folder.

SOCIAL MEDIA AND WHATSAPP
Social links are included in the website footer:
- Facebook: https://facebook.com/alison.cauchi.7
- Instagram: https://www.instagram.com/cauchialison?rpxt=emZyeTNnZGQyN2k1
- WhatsApp: https://wa.me/35679463470

Clicking WhatsApp opens a chat with the supplied number. Make sure you are happy to publish these contact links before putting the website online.

BEFORE PUBLISHING
1. Replace hello@alisoncauchi.com in index.html with your preferred contact email.
2. Update artwork titles and descriptions to match your real collection.
3. Add prices, dimensions, shipping details and a secure checkout provider if you want direct online purchases. The current shop section invites customers to enquire; it does not process payments.
4. Connect a domain and hosting service, then upload the website files and images folder.

This is a responsive static website starter. Google Fonts require an internet connection; system fonts are used as a fallback.
