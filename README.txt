CLASS 9A DIGITAL MAGAZINE

Open index.html in a browser to preview the website.

Pages included:
- Home
- About
- Teachers
- Our Mascot
- Photos
- Student Works

TEACHERS PAGE
Jacob Kerketta is featured at the top as Class Teacher and Head of Class 9A, with Social Studies and Commerce listed as subjects. The other eight teachers appear below in a responsive card grid. Photo placeholders are included for all teachers so photos can be added later.

ADDING TEACHER PHOTOS LATER
1. Create a folder named images next to the HTML files.
2. Add each teacher's photo to that folder, using simple names such as jacob-kerketta.jpg or biraj-boruah.jpg.
3. In teachers.html, replace a placeholder block such as:
   <div class="teacher-photo" aria-label="Photo placeholder for Biraj Boruah"><span>📷</span><small>PHOTO COMING SOON</small></div>
   with:
   <img class="teacher-real-photo" src="images/biraj-boruah.jpg" alt="Biraj Boruah">
4. Add this CSS to style.css:
   .teacher-real-photo { width:100%; height:185px; object-fit:cover; display:block; }
   For Jacob's larger image, use class="teacher-real-photo teacher-real-photo-large" and add:
   .teacher-real-photo-large { height:250px; border-radius:9px; }
5. Keep originals and use good-quality copies. Ask permission before publishing identifiable photos.

PHOTO GALLERY
The gallery currently uses sample online photos. Replace these with class photos before publishing if you prefer.

For GitHub Pages, upload all HTML, CSS, JavaScript, and image files to the same repository while preserving the folder structure.
