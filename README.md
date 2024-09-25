# Cegłozbiór
Gra w zbijanie cegieł.
## Jak grać
### Sterowanie
Streruj myszką i kółkiem od myszki (tym takim do skrolowania)
albo steruj strrzałkami i przyciskiem enter
### cel gry
zbij jak najwięcej cegieł
### wskazówka
kierunek piłki zależy od tego jak daleko od środka paletki się odbije
## Jak to zaprogramowałam
gra jest zrobiona na podstawie tego tutorialu https://developer.mozilla.org/en-US/docs/Games/Tutorials/2D_Breakout_game_pure_JavaScript
najpierw zrobiłam wszystko według tutorialu a potem dodałam sporo własnych ulepszeń
  * piłka odbija się jak kółko a nie jak punkt
  * masz wpływ na kąt odbicia piłki
  * kolory są ładniejsze
  * niektóre cegły mają po kilka żyć
  * kod jest ładniejszy. To jeden z moich najładniejszych kodów. 
  * można łatwo programować poziomy np
    var lvl5 = createLevel('poziom 5', [
    [2, 3, 4, 4],
    [3, 4, 4, 0],
    [4, 0, 4, 4],
    [3, 4, 4, 0],
    [2, 3, 4, 4]

  ])
  
