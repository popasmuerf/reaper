url : https://sunjay.dev/learn-game-dev/refactor-traditional-game-loop.html

A sensible thing to do 
at this point is to 
restructure our code 
to match the traditional
game loop we saw in the
earlier Game Loop section

        loop{
            processInput() ;
            update() ;
            render() ;
        }

1. processInput()
   - Process user input(event)
   - Process game input(event)
2. update()
   - based on events input update on screen image in memory
3. render()
   - render new screen image