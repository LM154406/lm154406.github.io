# My Coding Notebook

## Table of Contents
- [Binary Notes](#binary-notes)
  - [Binary](#binary-flippy-do-number-system)
  - [Practice](#practice)
- [Day 2](#day-2)
- [Code Definitions](#code-definitions)
- [Notebook Style Guide](#markdown-style-guide-for-coding-notebooks)


## Binary Notes

### Binary Flippy-do/number system

|1|2|3|4|5|6|7|8|9|
|-|-|-|-|-|-|-|-|-|
|1|2|3|4|5|6|7|8|9|

| Power | 2^7 | 2^6 |  2^4 |  2^3 |  2^2 |  2^1 |  2^0 | solution |
|-|-|-|-|-|-|-|-|-|
| Value | 128 | 64 | 32 | 16 | 8 | 4 | 2 | 1 |
| Binary |  1 | 1  | 0  | 1  | 1 | 0 | 1 | 1 | = 219 | 

another example of xreating a table
|header|a|b|c|d|
|-|-|-|-|-|
|dividers in row 2, data in 3|-|-|-|-|
|and beyond |-|-|-|-|

## Code Definitions
| Term | Definition | Base Structure / Syntax | Real Life Example | App Example (ignore)|
|------|------------|--------------------------|-------------------|-------------|
|   variable   | A named container used to store a value that may change. | `var x = 5;` | age |  |
|   constant   | A fixed value that cannot change once set. | `const PI = 3.14;` | birth day |  |
|  Data type    | The kind of value a variable holds, like numbers or text. | `int`, `String`, `bool` | games, internet, texts |  |
|   string   | A sequence of characters used to represent words or text. | `"Hello World"` | links |  |
|  integer    | Whole number values. | `int age = 16;` | streaks |  |
|   double   | Number values with decimals. | `double age = 16.2;` | money |  |
|   boolean   | A value that can be true or false. | `bool isLoggedIn = false;` | decisions |  |
|   list   | A collection of values in a specific order. | `List<String> names = [];` | a list |  |
|   null   | A special value that means “nothing.” | `String? name = null;` |  |  |
|    funtion  | A reusable block of code that performs an action. | `void sayHi() { print("Hi"); }` | light switch |  |
|   parameter   | The information passed into a function to change how it works. | `greet(String name)` | operators on calculator |  |
|   return   | The result a function gives back. | `return total;` | frisbee |  |
|    scope  | Where a variable or function can be used. | (No set syntax — concept-based) | pngs |  |
|   class   | Blueprint for creating objects with specific structure and behavior. | `class Dog {}` |  |  |
|   object   | A specific version of a class. | `Dog myDog = Dog();` |  |  |
|   property   | A variable that belongs to a class/object. | `String name;` |  |  |
|   method   | A function that belongs to a class. | `void bark() {}` |  |  |
|      | A special function used to set up a class when it’s created. | `Dog(this.name);` |  |  |
|      | Hiding the inner workings of code so users only interact with what they need. | (Concept — not specific code) |  |  |
|      | Changing how a built-in or inherited function behaves. | `@override` |  |  |
|      | A function that does not return a value. | `void printMessage() {}` |  |  |


## Day 1
Notes for the day 

## Day 2 
Notes for day 2

8/25 in class we're:

## Unit 1 8/28/ 25
-----
111
110
100
000
010
011
001
101
-----
## Binary 0 or 1
---------
Binary is a number system that uses 0 and 1.0
Power: 2^7 2^6 3^5 2^4 2^3 2^2 2^1 2^0
Value: 128  64  32  16  8   4   2   1
Binary: 1   1   0   1   1   0   1   1
Add up the values to get the answer:
100010 = 34
10100011 = 163
1111111 = 126
11011011 = 219
10101010 = 170
01000101 = 69
00000100 = 4
00111011
0100111 =
## Q
lossy: temp data, compressed, less quality 
lossless: 
metadata:



## Markdown Style Guide for Coding Notebooks

Follow this guide to keep your coding notebook **clear, consistent, and professional**.  
This ensures your notes are easy for you (and others) to read later.

---

## 🔹 Headings
**When to use:** Organize your notebook into sections (like days, topics, or projects).  
- `#` for the notebook title (use once at the top).  
- `##` for each day or major topic.  
- `###` for subsections (like "Notes", "Practice", "Reflections").  

✅ Example:


# My Coding Notebook
## Day 1
### Notes
### Practice

🔡 Text Formatting
When to use: Highlight important ideas or add emphasis.

Use bold for key terms or definitions.

Use italic for emphasis or side comments.

Use inline code for keywords, functions, or commands.

 

✅ Example:

**Class** = a blueprint for objects  
*Remember:* always test your code  
Use `System.out.println()` to print

 

💻 Code Blocks
When to use: Anytime you write multiple lines of code.

Inline code for short snippets.

Fenced code blocks with language for full examples.

✅ Example:

```java
public class Hello {
    public static void main(String[] args) {
        System.out.println("Hello World!");
    }
}
```

🧾 Lists
When to use: Organize steps, notes, or key points.

Numbered lists for sequences or steps.

Bulleted lists for unordered ideas.

✅ Example:

1. Define the class
2. Write the main method
3. Test your program

Variables
- Loops
- Conditionals
 

✅ Checklists
When to use: Track progress on assignments or tasks.

✅ Example:

[x] Complete coding warm-up
- [ ] Finish project draft
- [ ] Reflect on learning

 

➡️ Blockquotes
When to use: Call out notes, reminders, or teacher comments.

✅ Example:

> 💡 Remember: Loops repeat code until a condition is false.

 

📊 Tables
When to use: Compare values, track progress, or organize data neatly.

✅ Example:

| Task        | Status   | Notes          |
|-------------|----------|----------------|
| Homework 1  | Done ✅  | Submitted      |
| Homework 2  | Pending  | Needs review   |

 

🔗 Links & Images
When to use: Add references, resources, or visuals.

✅ Example:

[Java Docs](https://docs.oracle.com/javase/8/docs/api/)  
![Markdown Logo](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg)

 

📂 Collapsible Sections
When to use: Hide solutions, extended notes, or extra details.

✅ Example:

<details>
  <summary>Click to reveal solution</summary>
  
System.out.println("Answer: 42");

</details>

 

📝 Footnotes
When to use: Add references or side notes without cluttering the page.

✅ Example:

This concept is related to object-oriented programming.[^1]

[^1]: See "Objects and Classes" in your textbook.

 

🎯 Style Rules
Consistency matters more than creativity

Always use headings to structure your notes.

Always use code blocks for multi-line code.

Clarity first

Bold key terms.

Use lists instead of long sentences when outlining steps.

Professional tone

Don’t mix casual notes with formal work in the same section.

Use blockquotes for reflections or teacher feedback.

Track your learning

Use checklists to mark what’s done.

Use collapsible sections if you want to hide answers until review time.

 

✅ Bottom Line:

Headings = Structure

Bold/Italic = Emphasis

Code blocks = Code

Lists = Steps/Ideas

Tables = Organization

Checklists = Progress

Blockquotes = Notes/Tips

Collapsible = Hide/Show detail

Keep it simple, consistent, and clear.
