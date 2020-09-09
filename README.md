# guessing-game
n=22 guess=1 while(guess&lt;=10):     n1=int(input('pls guess the number'))     if n1>22:         print('you have entered a greater no.')     elif n1&lt;22:         print('you have entered a smaller no.')     else:         print('you have won')         guess = guess + 1         break          if guess>10:         print('game over!')
