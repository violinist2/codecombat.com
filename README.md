# codecombat.com
The Agrippa Defense - solution (Оборона Агриппы решение)

  while(true) {
    var enemy = hero.findNearestEnemy();
    if(enemy) {
        // Определи расстояние до противника с помощью distanceTo.
     var distance = hero.distanceTo(enemy);   
        // Если дистанция меньше 5 метров ...
        if(distance < 5){
            // ... если рассечение ("cleave") готово, руби!
 
      hero.attack(enemy);
     hero.cleave(enemy);
      hero.moveLeft();
      hero.moveLeft();
       hero.cleave(enemy); 
            
        }
            // ... или же просто атакуй.
      else{
            hero.moveRight();
          hero.moveLeft();
          hero.attack;
            
      }
        } 
       
    }


