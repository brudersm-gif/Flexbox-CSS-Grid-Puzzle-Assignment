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
          align-content: center;
          flex-wrap: wrap;
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
      <div class="flex-item">item 5</div>
      <div class="flex-item">item 6</div>
      <div class="flex-item">item 7</div>
      <div class="flex-item">item 8</div>
    </section>
  </body>
</html>
