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
          flex-wrap: wrap;
          justify-content: center;
        }
      section div.flex-item {
        flex: 1;
        text-align: center;
        background-color:lavender;
        margin: 0px;
        padding: 0px;
      }
    </style>
    <section class="flexbox-container">
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
