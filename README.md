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
        }
      section div.flex-item {
        flex: 1;
        text-align: center;
        background-color:lavender;
        margin: 5px;
        padding: 5px;
      }
    </style>
    <section class="flexbox-container">
      <div class="flex-item">item1</div>
      <div class="flex-item">item2</div>
      <div class="flex-item">item3</div>
      <div class="flex-item">item4</div>
    </section>
  </body>
</html>
