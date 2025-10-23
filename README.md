# Monte-Puzzle-Fish
<!DOCTYPE html>
<head>
  <title>Monte's snowman</title>
 <style>
  section.snow-container {
    display: grid;
    grid-template-columns: repeat(4, 150px);
    grid-template-rows: repeat(3,133px);
    column-gap: 0px;
    row-gap: 0px;
  }

   section.grid-container {
     display: gris;
     gap: 10px;
     grid-template-columns: repeat(3, 1fr);
     grid-template-area:
       '.hd.'
     'mn mn mn'
     '.ft.'
     ;
   }
   div.grid-item1 {
     grid-area: hd ;
     grid-column-start: 2;
     justify-context: center;
     display: flex;
     font-weight: 500;
     font-size: 1.5em;
     /*header*/
   }
     div.grid-item2 {
       grid-area: mn;
       display: flex;
       justify-content: center;
       /*main content*/
     }
  div.grid-item3 {
    grid-area: ft;
    grid-column-start: 2;
    justify-content: center;
    display: flex;
    font-style: italic;
    /*footer*/
  }
   section.grid-puzzle {
     display: flex;
     flex-direction: column;
   }
   div.flex-puzzle {
     display: flex;
     justify-content: center;
     align-content: center;
   }
   section.div.flex-item {
     display: flex;
   }
   .hidden {
     display: none;
   }    
</style> 
</head>

<body>
  <section class="grid-container">
    <div class="grid-item1"> Monte Lodahl</div>
    <div class="grid-item2">
      <section class="grid-puzzle">
        <div class="flex-puzzle">
          <section class="snow-container">
            <div class="flex-item"><img src="puzzle2_K.jpg"></div>
            <div class="flex-item"><img src="puzzle2_M.jpg" ></div>
            <div class="flex-item"><img src="puzzle2_E.jpg" ></div>
            <div class="flex-item"><img src="puzzle2_G.jpg"></div>

            <div class="flex-item"><img src="puzzle2_A.jpg"></div>
            <div class="flex-item"><img src="puzzle2_D.jpg"></div>
            <div class="flex-item"><img src="puzzle2_L.jpg"></div>
            <div class="flex-item"><img src="puzzle2_B.jpg"></div>

            <div class="flex-item"><img src="puzzle2_F.jpg"></div>
            <div class="flex-item"><img src="puzzle2_J.jpg"></div>
            <div class="flex-item"><img src="puzzle2_H.jpg"></div>
            <div class="flex-item"><img src="puzzle2_I.jpg"></div>

            <div class="flex-item hidden"><img src="puzzle2_C.jpg"></div>
          </section>
        </div>
        <div class="flex-puzzle"> Snowmen Puzzle: A picture of two snowmen on a capped mountain.</div>
      </section>
      </div>
      <div class="grid-item3">October 23 2025</div>
  </section>
</body>
</html>

