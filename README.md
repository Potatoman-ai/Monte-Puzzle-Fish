# Monte-Puzzle-Fish
<!DOCTYPE html>

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
     
       
</style> 
