# Flexbox-CSS-Grid-Puzzle-Assignment
<!DOCTYPE html>
<html>
  <head>
      <title>Flexbox CSS Grid Puzzle Assignment</title>
  </head>
  <body>
    <style>
      section.flexbox-container {
          display:flex;
          flex-direction: row;
          flex-wrap:wrap;
          max-width: 440px;
      }
      section div.flex-item {
        flex: 1;
        background-color: lavender;
        width: 110px;
        height: 150px;
      }
    </style>
    <section class="flexbox-container" stle="display: flex;">
      <div class="flex-item"><img src="images/puzzle1_A.jpg"/></div>
      <div class="flex-item"><img src="images/puzzle1_A.jpg"/></div>
      <div class="flex-item"><img src="images/puzzle1_A.jpg"/></div>
      <div class="flex-item"><img src="images/puzzle1_A.jpg"/></div>
      <div class="flex-item"><img src="images/puzzle1_A.jpg"/></div>
      <div class="flex-item"><img src="images/puzzle1_A.jpg"/></div>
      <div class="flex-item"><img src="images/puzzle1_A.jpg"/></div>
      <div class="flex-item"><img src="images/puzzle1_A.jpg"/></div>
    </section>
  </body>
</html>
