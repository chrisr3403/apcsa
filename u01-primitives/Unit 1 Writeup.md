# Process Writeup

## Name: Christian Ramos
## Course: Java (Unit 1 primitives)
## Period: 3
## Concept: Java basics 

### Intro to Java basics!

Hello my name is Christian Ramos and I am here to talk about the intro to Java or Java basics as I call it. We are learning how to build lines of code for our starter 
for what we have learned so far. The things we want to aim and talk about will be listed down below.

In Java our two first codes we have learned is ```System.out.print("")``` and ```System.out.println("")``` these two codes codes are a method to print something out:

So if I wanted to say System.out.print(" Chris is the best ") the code will print out:

Chris is the best

Both of these methods are used frequently and every assignment and quiz and in java in general!

Lets start with a lesson from lesson 1 of intro to java!
First thing we are going to be looking at is the strings!

<img width="1133" height="409" alt="image" src="https://github.com/user-attachments/assets/220c8d9f-4907-4b92-a256-6e4355db3dcc" />

Each System println will respond to the string scan code. The string corresponds to the system println so you can answer such as questions.
Every time you answer the question the string transfers over via the scan to another system out print.
This was only many of the things I learned. Strings stores text, ints store whole numbers, double stores decimals and boolean stores two values such as true and false.

### Challenges!

# The first challenge 

The first challenge which is very minor is confusing data types. When I first started working on my partner java assignment, it was very easy to confuse data types.
Such as for example a int and a double stores for example numbers. But on a question I had the two codes swapped such as here
   ```System.out.println("Please enter the homework grades for this course.");
        double gradeHW0 = scan.nextDouble();
        double gradeHW1 = scan.nextDouble();
        double gradeHW2 = scan.nextDouble();
        double gradeHW3 = scan.nextDouble();

        System.out.println("Please enter the quiz grades for this course.");
        int quizExam0 = scan.nextInt();
        int quizExam1 = scan.nextInt();
```
So for this it asked for HW grades to be "int" since the hw grades are supposed to show whole numbers. Thinking it was the opposite I thought double is the int same goes for int being the double.
So I used past assignments and also my quiz notes and I noticed it is swapped. So I went to fix it so the int carries the whole numbers and doubles carry desmals.

# My second challenege 

My second challenge is figuring out how to actually making int statement scan as in once you enter a whole number it switches. It was simple later on but at first I did not know how to build it properly.
Strings gave me a reference such as ```String coursename = scan.nextLine();``` from my partner assignment. I needed to figure out a way to make it so it had int within so I took the time to make something such 
as this ```int gradehw0 = scan.nextLine();``` after using this It did not work which got me thinking for hours until I compared all scan line codes to see if they have differences. And one thing I noticed was 
this part  ```int gradeHW0 = scan.nextInt();``` the part next to the scan method has the "Int" which was needed to make whole numbers and the int code to work.

# My third challenge

My third challenge was my exam which I had trouble with. In a part where the exam was given on this question 
<img width="880" height="599" alt="image" src="https://github.com/user-attachments/assets/5fefa52b-53a3-4f4e-96fc-05890001f634" />

Why was this such a big challenge? I consider this to be my challenge because int data types are always whole numbers which links back to confusing data types.
I was very confused as to why does a desmal go with the int? How could it go if the int itself does not have desmals? My conclusion was that we needed to divide the int number to get a desmal number.

### Takeaways 

# My first takeaway!
My first takeaway is that each data type has their own description and as well can work with the scanner such as this line:
`Scanner scan = new Scanner(System.in);`
From what I know we can now see that the scanner scans each new system print such as if a int for example, if you put in the number the scanner will then allow you to move on to the next line.
This is a good takeaway for the future when working on FP because then you can make lines of code continue after each scan and of course scans require code such as this for example: 

Ints:
```int gradeHW0 = scan.nextInt();```

Strings 
```String coursename = scan.nextLine();```

# My second takeaway!
My second takeaway is that in java ints doubles booleans and strings have data such as booleans, doubles and ints are primative data types.
For strings, strings are non primative types which are refrence due to a string only having characters such as letters.


Inline `code` snippet

```The Print code - prints the text
System.out.println("");
System.out.print("")
```

``` Scanner - scans each code line
Scanner scan = new Scanner(System.in);
scan.nextLine();
```
