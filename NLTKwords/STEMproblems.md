#=================================АНАЛИЗ ОШИБОК СТЕММИНГА===============================#


### I Стеммер Портера

   * У глаголов was и is нет s на конце
      
      ***Пример:***               was--->'wa'
  *  В наречиях вместо -ly после стеммера появляется -li
  
       ***Пример:***               badly---> 'badli'
  *  В ненужных местах убрана буква -e на конце
  
       ***Пример:***               able---> 'abl'
   
      





### II Стеммер Snowball
	 
  *  Слова, заканчивающиеся на "и" и не являющимися существительными, не достают  "и"
      
      ***Пример:***               если--->'есл'
  *  Слова, заканчивающие на "е" и не являющимися существительными, не достают  "е"
  
       ***Пример:***               даже---> 'даж'
  *  Слова, заканчивающие на "о" и не являющимися существительными, не достают  "о"
  
       ***Пример:***               около---> 'окол'
  *    Воспринимает существительные  и т.п., оканчивающиеся  на "ь", как глаголы, что приводит к тому, что мягкий знак "отсекается"
       
       ***Пример:***                пять--->'пят', двадцать ---->'двадцат'     
      
      

       