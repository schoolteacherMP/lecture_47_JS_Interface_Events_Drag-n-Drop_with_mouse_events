## Задача     
###  Создайте простой интерфейс для Drag'n'Drop, который позволяет перемещать элементы на странице с помощью мыши.  

Шаги:  
1. Создайте несколько блоков на странице с разными цветами фона.  
2. Добавьте обработчики событий мыши (mousedown, mousemove, mouseup) к каждому блоку.  
3. При нажатии на блок, сохраните его координаты относительно окна браузера в переменную.  
4. При перемещении мыши (mousemove), измените позицию блока на странице с учетом координаты мыши и сохраненной начальной позиции блока.  
5. При отпускании мыши (mouseup), удалите обработчики событий мыши для блока.  
`<style>`  
    `.block {`  
      `position: absolute;`  
      `width: 100px;`  
      `height: 100px;`  
      `border: 2px solid black;`  
      `border-radius: 10px;`  
    `}`  
    `#block1 {`  
      `background-color: red;`  
      `top: 50px;`  
      `left: 50px;`  
    `}`  
    `#block2 {`  
      `background-color: blue;`  
      `top: 150px;`  
      `left: 150px;`  
    `}`  
    `#block3 {`  
      `background-color: green;`  
      `top: 250px;`  
      `left: 250px;`  
    `}`  
  `</style>`  
  `<div id="block1" class="block"></div>`  
  `<div id="block2" class="block"></div>`  
  `<div id="block3" class="block"></div>`  
  
