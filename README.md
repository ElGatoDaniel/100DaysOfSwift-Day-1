# 100 Days Of Swift Day 1

This README documents what I have learned through experimenting with Swift in an Xcode Playground.

### Code overview

<code>
import UIKit

var str = "Hello, playground"
str = "Danny"

let birthplace = "México"
var age: Int = 28
let pi: Double = 3.14
var answer: Bool = true

let sentence = "My name is \(str), I'm \(age) years old and I was born in \(birthplace)"

let multiline = """
        I'm a multiline string text
        Isn't it awesome?
        I think it is.
"""
</code>

### Concepts Learned

1. Importing Modules

	•	import UIKit: This imports the UIKit framework, which is commonly used in iOS development for building user interfaces.

2. Variables and Constants

	•	var str = "Hello, playground": Declares a variable of type String and assigns it a value. Variables can be changed after their initial assignment.
	•	str = "Danny": Changes the value of the previously declared variable str.
	•	let birthplace = "México": Declares a constant of type String and assigns it a value. Constants cannot be changed once they are assigned.

3. Data Types

	•	var age: Int = 28: Declares a variable of type Int (integer) and assigns it a value.
	•	let pi: Double = 3.14: Declares a constant of type Double (double-precision floating point) and assigns it a value. I read that there's a better way to put pi, but we are going to dive into it later.
	•	var answer: Bool = true: Declares a variable of type Bool (boolean) and assigns it a value.

4. String Interpolation

	•	let sentence = "My name is \(str), I'm \(age) years old and I was born in \(birthplace)": Uses string interpolation to include variable values within a string. The \() syntax is used to insert the value of a variable or constant into a string.

5. Multiline Strings

	•	let multiline = """ I'm a multiline string text 
                        Isn't it awesome? 
                        I think it is. """:

Demonstrates the use of multiline string literals, which allow for strings that span multiple lines. Triple double quotes (""") are used to define a multiline string.

In summary

Through this exercise, I gained an understanding of basic Swift syntax and concepts, including importing modules, declaring variables and constants, using different data types, string interpolation, and creating multiline strings. These were easy because i have a Javascript and C## background, but i'm pretty sure that the difficulty will increase in the next days. See you later!
