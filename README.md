# Guess-the-number
This repository stores the files for the Game-Guess the number
hello my name is manav(Shadow)
Below is the code.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Guess the Game</title>
</head>
<body>
    <script>
        (function main(){
            var number;
            var guess;
            var nguesses=0;

             number=Math.ceil(Math.random()*100)
            console.log(number)

            alert("Enter the Game of GUESS THE NUMBER. The Game is easy The computer generates               a number between 1 to 100 and you just have to guess it . if your guess is lower               than the actual number then it will alert you as higher number please and if it is             higher than it will alert lower no plz . Understood Now lets go")
            do{
                guess=parseInt(prompt("Enter your guess"))
                if(number<guess){
                    alert("Lower Number Plz")
                }
                else if(number>guess){
                    alert("Higher Number Plz")
                }
                else{
                    alert("Congratulations you have completed it in  "+nguesses+" attempts")
                }
                nguesses++;
            }while(guess!=number);
        })();
    </script>
    
</body>
</html>
