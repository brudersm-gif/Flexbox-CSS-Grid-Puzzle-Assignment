<!DOCTYPE html>
<html>
  <head>
      <title>Flexbox CSS Grid Puzzle Assignment</title>
  </head>
  <body>
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
      <div class="flex-item"><img src="images/puzzle1_A.jpg" alt="puzzle piece"/></div>
      <div class="flex-item"><img src="images/puzzle1_B.jpg" alt="puzzle piece"/></div>
      <div class="flex-item"><img src="images/puzzle1_C.jpg" alt="puzzle piece"/></div>
      <div class="flex-item"><img src="images/puzzle1_D.jpg" alt="puzzle piece"/></div>
      <div class="flex-item"><img src="images/puzzle1_E.jpg" alt="puzzle piece"/></div>
      <div class="flex-item"><img src="images/puzzle1_F.jpg" alt="puzzle piece"/></div>
      <div class="flex-item"><img src="images/puzzle1_G.jpg" alt="puzzle piece"/></div>
      <div class="flex-item"><img src="images/puzzle1_H.jpg" alt="puzzle piece"/></div>
    </section>
  </body>
</html>
