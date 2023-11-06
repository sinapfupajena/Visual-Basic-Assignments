# CS15
Module Program
  Sub Main(ags As String())
    Console.WriteLine("hello 555 Workld!")
  End Sub
End Module
________
Module Module1
  Sub Main()
  Dim myNum As integer
  myNum = 5
  Console.WriteLine(myNum)
 End Sub
End Sub Module
  1. Main is the drop in point of the program
  2. The Tim line is called a delcaration. It delcares a variable called MyNum
  and it specifies the data type of that variable is Integer. MyNum creates a box in 
  memory where an integer can go
  3. The myNum = 5, puts a 5 in that box. This is called an assignment statement. You are
  assigning whatever is on the right side which is the 5, to whatever is on the left, which
  is myNum. Bottom line, the myNum box will have a  5 in it. 
  4. The WriteLine, writes out the value
  
  Quiz Question
  What is the difference between the two console lines? The first and second console write lines.
  - One is writing a boc, the other is writing a value. The first one is writing out a literal 
  string, whereas the second is writing out an INteger so you don't see the quotes. It is a 
  different data type. An integer is definitely different from a string.
  
  If I wanted to (optionally) collapse the delcaration of MyNum together with setting it to some initial value,
  I could use this syntac. It's a combo of declaring a varbiable together with assigning it value.
  
  What is the difference between assigning a variable and declaring one? 
  Declaring = when you give it a name and tell it what data type it is, like it is an integer
  Assigning = when you put an actual value into the variable
  *YOU CANNOT USE A VARIABLE UNLESS YOU HAVE DECLARED IT
  
  >>>VIDEO: Virtual Basic tutorial - 8 - Variables
  
  Module Module1
    Sub Main ()
      Dim myNum As Integer = 5
      myNum = 7
      Console.WriteLine(myNum)
      Console.ReadLine()
     End Sub
   End MOdule
   
   Module Module1
    Sub Main()
        Dim myBool As Boolean = 'Hello!')
        Console.WriteLine(myBool)
        Console.ReadLine()
    End Sub
End Module
_________
In the video:
1. Integer - a whole number positive, negative, or zero, but no fractional parts,
ie. no decimal points
2. Double - a REAL number, which is going to have a fraction (write as decimals)
ie. 1.5 or 2.347
3. Character - a single character, can be letter, number, punctuation, even a blank
space 
4. String - a seqeuncce of one or more characters
5. Boolean - it's truth value, can be either true or false 

VB Beginner 3 - Varables, Data types Assignment 
- yo dont need (args As String())

IDE stands for integrated development environment. What this is, is a program/
software application that let's you write programs in it. Visual Studio is an IDE.
It provides all these bells and whistles, like exgra features, auto complete, etc.,
and in one of the windows of the IDE is where your actual code is. you write
the ode in the syntax of the programming language you are using. To run any code you have to compile
it into a lower level executable form and then you actually run it. you write code,
you complie code, then you can run the code. thats all hidden and taken care of in the Visual
Studio environment. They give you a window to write the high
level Visual Basic code, then when you press the green button its actually compiling
the code for you and then it's showing the output in a differnet window. All teh colored lines 
and little visual symbols and auto stuff are just features of Visual Studio to make
it easier to write the basic code, gives you hints about syntax and so forth. 

"Dim" a key word that declares a variable 
Dim gallons As Double

What is a variable? 
A variable is a box that holds a certain type of data, and you give a name to that box

What is an assignment? 
You assign a value to a variable. What is on the right gets assigned over to the left
num = 100 

What is a key word? 
It is  a built in key word of the langauge. For example Dim, Integer, Module, End, etc. 

What is a procedure
Sometimes you hear it referred as a procedure, or a method, or a subroutine, or a function.
But it is something that carries out a function 
For example MAIN, is a procedure that is the main 

What is an argument 
An argument (also referred to as aparamenter) is information that you want to sent to a
procedure. For examplle if oyu want to use the WriteLine procedure, you can send it to 
the hting that you want to print out as a parameter 

Console.WriteLine("foo")
I am calling the WriteLine routeine and I am sending "ffoo" to it as an argument.
Notice that the argument is the thing that goes in parentheses to the proceedure.

You always know if something is a procedure bc you will see the (). You always know
if you are sending an argument because tehre would be things in the () if there is an argument.

String Concatenation
Imports system 

Module Program
  Sub Main()
    Dim num As Integer
    num = 100
    Console.WriteLine(num)
    Console.WriteLine("My num is" & num)
  End Sub
End Module 

Notice you can concatenate (join) things together that you want to print out. So, in 
this example you are printing a string which is "My Num is" and you are concatenating (attaching) on to that
other thing which is a variable. So the output of this program would be
My num is 100
Pay attention to the black space. If you didn't print a blank spacce, the output would be 
Console.WriteLine("My num is" & num)

My num is 100 

<p>Module Program</p>
 <div> Sub Main()
  Dim x As Integer
  Dim y As integer
  x = 100
  y = 200
  COnsole.WriteLine('x is"&x)
  </div>
