### Part II: The CLI

Open up `bin/move`. We're ready to code the executable portion of this program.

1. Our program should first welcome the player by outputting a friendly message to the terminal: "Welcome to Tic Tac Toe!".
2. Next, establish the starting state of the game, i.e. the empty board. Create a new board by setting a variable `board` equal to instantiating a new array with 9 elements, each of which is a blank space, `" "`.  
3. Now, ask the user for input by outputting "Where would you like to go?" to the terminal.
4. We need to store the user's input. Use `gets.strip` to store their input to a variable, `input`.
5. Now we want to convert the user's input to an array index using our `#input_to_index` method and store this as the variable `index`.
6. Now we're ready to call our `#move` method. Do so with the arguments of the `board`, the `index` the user wants to access and the default player of `"X"`.
7. Lastly, display the board by calling the `#display_board` method, passing in the necessary arguments required to run this method.

Now, run your program by typing `ruby bin/move` in the terminal. Have fun playing (one round of) tic tac toe!

<p data-visibility='hidden'>View <a href='https://learn.co/lessons/ttt-5-move-rb' title='Tic Tac Toe CLI: Adding Player Movement to the Game Board'>Tic Tac Toe CLI: Adding Player Movement to the Game Board</a> on Learn.co and start learning to code for free.</p>




# Today

- Review
- More loops and iteration
- Lunch + Campus Tour
- Nested Arrays, even more iteration
- Code Challenge

# Review from yesterday

- variables
- data types
- methods
- arrays

- conditionals
def even_or_odd(num)
   if num.even?
     puts "The number is even"
   else
     puts "The number is odd"
   end
end

- loops

times
while
each




