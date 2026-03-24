<!DOCTYPE html>
<html>
  <head>
      <title>Flexbox CSS Grid Puzzle Assignment</title>
  </head>
    <style>
      section.container1 {
        display: flex;
        flex-direction: row;
        flex-wrap: wrap;
        justify-content: center;
        align-items: center;
        width: 440px;
        height: 600px;
      }
      section div.flex-item {
        text-align: center;
        width: 110px;
        height: 150px;
      }
    </style>
    <section class="container1" style="display: flex;">
      <div class="flex-item"><img src="images/puzzle1_A.jpg"/></div>
      <div class="flex-item"><img src="images/puzzle1_A.jpg"/></div>
      <div class="flex-item"><img src="images/puzzle1_A.jpg"/></div>
      <div class="flex-item"><img src="images/puzzle1_A.jpg"/></div>
      <div class="flex-item"><img src="images/puzzle1_A.jpg"/></div>
      <div class="flex-item"><img src="images/puzzle1_A.jpg"/></div>
      <div class="flex-item"><img src="images/puzzle1_A.jpg"/></div>
      <div class="flex-item"><img src="images/puzzle1_A.jpg"/></div>
    </section>
</html>
