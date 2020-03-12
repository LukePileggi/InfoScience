# This is my journal for *Info Science*

1/30
1. What did we do?
- We tried to explain how to make a jelly sandwich so anybody could make one with no knowledge of making it.
2. What did you learn?
- I learned that it takes many steps to explain something. It is difficult, but is very interesting how we can clarify things with words.
3. What questions do you have?
- Is the ability of explaning things lower in our generation? Or is it just me?

#Homework: making my initial with triangles
I made it simple, by using two triangles.

```.py
triangle(25, 75, 35, 20, 41, 75);
triangle(25, 75, 27, 65, 71, 75);
```


2/6
1. What did we do?
- We made a program that will make colorful patterns. We started from making simple circles, than made them appear sideways, diagnal, and then randomly. Then we added color and lines that lead to the shapes so it makes a radial pattern.
2. What did we learn?
- I learned that programing is challenging but very fun an feels good when you finish something. Even the smallest errors will effect the results.
3.What questions do you have?
- Do I have to remember all the things I learned today? I forgot half of the programs that we used today already.

#Homework: Making a dice with a square and seven circles
This was easy after how to place shapes in coordinates.

```.py
def setup():
    size(600, 600)
    background(255)
    
    square(50, 50, 500)
    circle(150, 150, 50)
    circle(150, 300, 50)
    circle(150, 450, 50)
    circle(300, 300, 50)
    circle(450, 150, 50)
    circle(450, 300, 50)
    circle(450, 450, 50)
```

2/10
1. What did we do?
- We made a working dice and messed with the odds.
2. What did we learn?
- The random feature is really convenient. I can use it in many programs. Also, I learned that I have **bad luck**
3.What questions do you have?
- What is the best way to guess the odds of the dice in a case like today's class?

2/20
1. What did we do?
- We made an optical illusion using coding.
2. What did we learn?
- We learned if we can code we can trick people.
3.What questions do you have?
- I couldn't finish the code because the pace was too fast. Prehaps we could slow the pace of the class a bit?

#Homweork: Find an optical illusion you could make using coding
https://en.wikipedia.org/wiki/Ebbinghaus_illusion

2/2
1. What did we do?
- We presented the optical illusions we made for homework.
2. What did we learn?
- Citing is important!
3.What questions do you have?
- No questions :)

The Ebbinghaus illusion code!

```.py
x = 220

def mouseClicked():
    fill(255)
    global x
    x += 5

def setup():
    size(800,800)
    background(255)
    
def draw():
    background(255)
    global x
    fill(0)
    circle(100, 400, 100)
    circle(340, 400, 100)
    circle(160, 296, 100)
    circle(280, 296, 100)
    circle(160, 504, 100)
    circle(280, 504, 100)
    circle(520, 400, 40)
    circle(640, 400, 40)
    circle(550, 348, 40)
    circle(610, 348, 40)
    circle(550, 452, 40)
    circle(610, 452, 40)
    fill(255)
    circle(580, 400, 60)
    circle(x, 400, 60)
```

3/2
1. What did we do?
- We used the new circuit website.
2. What did we learn?
- We learned a new website.
3.What questions do you have?
- No questions!

3/12
1. What did we do?
- We used LEDs and other stuff and made it work with programing.
2. What did we learn?
- We learned how to use the program to light up LEDs.
3.What questions do you have?
- No questions.
