# game1

# PLay UNO!

![screenshot](playUno.png)

## The game is called "Play Uno!"?

> PlayUno is a digital card game played between the computer and a user. To start, each, the player and the computer recieve 7 cards. The objective of the game is for either player to end up with only one card left. 

## Technical Discussion

> Technologies used. 
  -HTML
  -CSS
  -JavaScript
 
### Notes on Game Structure
##Code Sample:

```javascript
let checkActionCards=function(card){
   
                console.log (card.special);
                 if (card.special==="DrawTwoCards"){
                    whoseTurnIsIt(SpecialCardDrawTwoCards("player"), true);
                 }
                 else if (card.special==="ReverseCards"){
                     console.log ("ReverseCards was placed ");
                     whoseTurnIsIt( SpecialCardReverseCards("player"), true);
                 }
                 else if (card.special==="SkipCards"){
                     whoseTurnIsIt( SpecialCardSkipCards("player"),true);
                 }
                 else if (card.special==="Wild"){
                     
                     SpecialCardWild("player");
                 }
                else if (card.special==="DrawFour"){
                     SpecialCardDrawFour("player");
                   }
            }  
        

```
> Code samples, description of challenges you overcame, etc.

## The Making of [Your Game]

> Any credits or notes you feel you should add

## Opportunities for Future Growth

> If you had more time to work on your game, what would you do?

