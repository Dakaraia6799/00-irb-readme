# Introduction to IRB

## Objectives

1. Describe IRB and why it's useful when programming.
2. Distinguish IRB from your terminal and other files.
3. Access and exit IRB via your terminal.
4. Execute commands in IRB.

<iframe width="960" height="720" src="https://www.youtube.com/embed/WWh1uxqQI48?rel=0&amp;showinfo=0" frameborder="0" allowfullscreen></iframe>

[MP4](http://learn-co-videos.s3.amazonaws.com/ruby/intro-to-irb.mp4)



## What is IRB?

IRB stands for "Interactive Ruby." It's a Ruby shell or REPL. REPL stands for read–eval–print loop. It is a simple, interactive computer programming environment that **r**eads user inputs (such as, in our case, snippets of Ruby code), **e**valuates them and **p**rints the result to the user, and then **l**oops so that you can enter more code. IRB is run by your computer's terminal. You can think of it as your Ruby playground or execution environment. You can open it up, insert code and execute it to see that code's return value.

## What *isn't* IRB?

IRB is not a file where you save your work. Any coding you do in the IRB console in your terminal will not get saved anywhere. It exists temporarily only. IRB is for testing, playing, manipulating your code so that you understand it better and solve problems with it.

## How do you use it?

IRB allows you to execute ruby in the terminal and you're going to get comfortable using it to test and better understand your Ruby code. To access IRB, just type `irb` in the terminal. IRB allows you to do anything you can do in a Ruby file. For instance, you can do math, get the time by typing `Time.now`, or print text to the screen.

## Instructions

1. Open up your terminal.
2. Type `irb` and hit `return`.
3. Now that you've started IRB, type the commands below to see how it works! Type each of the following lines into the irb shell and press enter.

  * `Time.now`
  * `255 / 5`
  * `9 ** 2`
  * `"6".to_i`
  * `puts "hello world"`

You can even do multiple lines of code (Do **NOT** copy/paste.  Type each line, and press 'return' after each line):
```ruby
5.times do
    puts "I <3 ruby"
end
```
To leave irb, type the `exit` command - this will get you back to your command line.  Pressing `ctrl+D` should also interrupt `irb` and return you back to the command line.

## Resource

When you don't have a terminal handy, **[repl.it/languages/ruby](http://repl.it/languages/ruby)** is another great resource.  No need to type `irb`.  Just start repl'ing.

You can even write a program on the left, run it, and repl on the right.  This is useful for things like checking values of variables.

Test it out!