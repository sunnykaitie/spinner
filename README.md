# spinner
my first coding project! with help of @qiaochloe my beloved &lt;3

This summer, I decided to embark on a side quest that I've wanted to start for a long time. I wanted to learn how to *code*. Tons of my high school friends code, and I always admired them for their technical abilities. It seems to come naturally to them, but it's just not intuitive for me. What's intuitive for me? Biology. Psychology. Sociology. Even chemistry, to some degree. Math, physics, coding, I struggle a lot more with that. But coding is such a useful skill to have that I might as well try my best. And, I know it'll come in handy in the future – very near future. So, I'm trying to get familiar with Python and I'll be documenting my progress along the way! Welcome to my journey :) 

For my first project, I wanted to create a spinner: inspired by my indecisiveness and my government teacher, Ms. Cassidy. She would use a wheel to decide if we were allowed extra credit opportunities, or something to that effect. This spinner had the goal of dictating what I would do after I came home from lab. This project has a whopping five lines of code. Mighty impressive, I know. But for me, this is the first time that I'm being exposed to a lot of the language and why it's typed the way that it is. Heck, the only two things I had known beforehand were print("Hello world!") and a little bit of exposure to the for-loop and while-loop (courtesy of Chloe again!). From these five lines, here's what I learned: 

1. How to set a variable:
   The first variable I set was number_of_sections = 8. I learned that the name of the variable comes first, followed by what you want the variable to mean. In this case, number_of_sections is the name of my variable, and that variable means 8. My goal was that the spinner would have eight total sections, as you probably figure!
2. The import keyword:
   Keywords are special words in Python (35 total), like for-loops, and if-else. Here, we imported a module called random – which is like a library that contains other functions, which are distinguished by parentheses following them. We used random to then create a random number generator.
3. What functions do:
   The function that I used was random.randint(). I initially had it as random.randint(1, number_of_sections) but I later changed it to random.randint(0, number_of_sections-1). This is so that if we wanted to change the variable, say to ten, then we wouldn't have to change this line as well. We also had it start at 0 because of indexing, which I'll talk about soon!
4. Generating a random number:
   Now, I wanted to generate a random number between 1 and 8 (later changed to be between 0 and 7), so I used "spin" as the name of my variable and set that equal to random.randint(0, number_of_sections-1) and then used print("spin") to print the resulting number. 
