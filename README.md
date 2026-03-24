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
          justify-content: center;
          flex-wrap:wrap;
          max-width: 440px;
          height: 600px;
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
      <div class="flex-item">item2</div>
      <div class="flex-item">item3</div>
      <div class="flex-item">item4</div>
      <div class="flex-item">item 5</div>
      <div class="flex-item">item 6</div>
      <div class="flex-item">item 7</div>
      <div class="flex-item">item 8</div>
    </section>
  </body>
</html>
