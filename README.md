# Syntax and Commenting THA
In this assignment you will edit a basic program showcasing the concepts you learned about in the tutorial. This is to be completed individually without aid from fellow students.

## Instructions
To submit this assignment, please perform the following:
1. Follow the instructions below.
1. When prompted, name your project app `firstname_lastname_app` where `firstname` is your first name and `lastname` is your last name.
1. Save your screenshots (if any) to the directory `assets`.
1. Link your screenshots (if any) in `submission.md` where appropriate.
1. Answer questions (if any) in `submission.md`.
1. Push your assignment to GitHub.

## Fix another's syntax mistakes
The below code contains a number of errors. Additionally, the code needs cleaning up so that it is more presentable. This requires your expertise to add indentations, semicolons, spelling corrections, and other adjustments.

Create a new C# project for this assignment. Be sure to select the folder this repo is in. It should be the default directory presented by VS Code. Once done, copy the code below into `Program.cs`.

```C#
string name = "Griz"
int quantity = 1
Console.WriteLine("The weather is phenomenal in Montana.");           
if (quantity == 1)
{
Console.Writeline("We have just 1 Griz");
}
else
{
Console.writeLine("Sorry. We don't have a Griz.")
}
```

Please perform the following corrections to the code:
1. Please insert a single line comment at the very top with your first name and last name. (1 pt.)
1. Three semicolons are missing. Please insert those into the code. (1 pt.)
   1. Hint: If statements do not need semicolons after them since they rely on curly brackets.
1. At the top of the code you have two variables `string name...` and `int quantity...`. Add comments to both of them by performing the following (note, you will not add the comments below them, but to the right of them) (2 pts.)
   1. Add a comment at the end of `string name...` that indicates it is a mascot.
   1. Add a comment at the end of `int quantity...` that indicates it is a count for the number of mascots.
1. Create white space between the variables at the top and the method `Console.WriteLine("The weather...`, then right below the same method. (1 pt.)
1. Correct the spelling errors in the program. Two spelling mistakes are present. (2 pts.)
1. Within the `if` and `else` statements, use indentation once in each to create some pleasant spacing. (1 pt.)
1. Right above the `if` statement, insert a comment block that contains the following: (2 pts.)
   1. First line: Today's date and time
   1. Second line: copy this text `This code assesses the number of mascots.`
   1. Third line: Your feelings about Griz