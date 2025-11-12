# My Coding Notebook
## Day 1
### Notes
### Practice
🔡 Text Formatting
When to use: Highlight important ideas or add emphasis.

Use bold for key terms or definitions.

Use italic for emphasis or side comments.

Use inline code for keywords, functions, or commands.


**Class** = a blueprint for objects  
*Remember:* always test your code  
Use `System.out.println()` to print
💻 Code Blocks
When to use: Anytime you write multiple lines of code.
| Algorithms | Define step by step processes to follow when completing a task or solving a problem | no syntax | Make a grilled cheese | Verify user |
| Sequencing | Define an order for when steps in an algorithm are completed | Follows 1, 2, 3 | which step comes first in making a grilled cheese | Get bread, add butter, add cheese |
Inline code for short snippets.

| Term | Definition | Base Structure / Syntax | Real Life Example | App Example |
|------|------------|--------------------------|-------------------|-------------|
|Varible| A named container used to store a value that may change. | `var x = 5;` |  |  |
|Constant| A fixed value that cannot change once set. | `const PI = 3.14;` |  |  |
|Data Type| The kind of value a variable holds, like numbers or text. | `int`, `String`, `bool` |  |  |
|String| A sequence of characters used to represent words or text. | `"Hello World"` |  |  |
|Integer| Whole number values. | `int age = 16;` |  |  |
|Double| Number values with decimals. | `double age = 16.2;` |  |  |
|Boolean| A value that can be true or false. | `bool isLoggedIn = false;` |  |  |
|List| A collection of values in a specific order. | `List<String> names = [];` |  |  |
|Null| A special value that means “nothing.” | `String? name = null;` |  |  |
|Function| A reusable block of code that performs an action. | `void sayHi() { print("Hi"); }` |  |  |
|Parameter| The information passed into a function to change how it works. | `greet(String name)` |  |  |
|Return| The result a function gives back. | `return total;` |  |  |
|Scope| Where a variable or function can be used. | (No set syntax — concept-based) |  |  |
|Class| Blueprint for creating objects with specific structure and behavior. | `class Dog {}` |  |  |
|Object| A specific version of a class. | `Dog myDog = Dog();` |  |  |
|Property| A variable that belongs to a class/object. | `String name;` |  |  |
|Method| A function that belongs to a class. | `void bark() {}` |  |  |
|Constructor| A special function used to set up a class when it’s created. | `Dog(this.name);` |baby with no name gets named baby girl or baby boy  |  |
|Abstraction| Hiding the inner workings of code so users only interact with what they need. | (Concept — not specific code) |  |  |
|Override| Changing how a built-in or inherited function behaves. | `@override` |  |  |
|Void| A function that does not return a value. | `void printMessage() {}` |  |  |
Fenced code blocks with language for full examples.




## Flutter Definitions

| Term | Definition and Description | Base Structure | Real Life Example | App Example |
|------|----------------------------|----------------|-------------------|-------------|
|Main()| A function that runs when your app starts. It tells Flutter what app to show. | `void main() => runApp(MyApp());` |  |  |
|MaterialApp| The widget that sets up your whole app’s look and navigation. | `MaterialApp(...)` |  |  |
|Scaffold| A widget that gives you the basic layout: background, navigation bar, floating button, etc. | `Scaffold(...)` |  | structrue for each page|
|Column| A widget that holds and displays your content in a straight line from top to bottom. | `Column(...)` |  |  |
|Row| A widget that shows things side-by-side. | `Row(...)` |  |  |
|Container| A box that holds other widgets. You can add color, padding, borders, or size. | `Container(...)` |  |  |
|Text| A widget to display text on the screen. | `Text('Hello')` |  |  |
|Image.network| A widget to show an image using a link from the internet. | `Image.network('https://...')` |google images|  |
|onPressed| A clickable button that floats above content. You choose what happens when it's clicked. | `ElevatedButton(onPressed: ..., child: ...)` |  |  |
|StatelessWidget| The code that gets run when a button is tapped or something happens. | `onPressed: () => doSomething()` |  |  |
|@override| A class that creates widgets that never change. Good for static screens. | `class HomeScreen extends StatelessWidget` |  |  |
|build()| A class for widgets that can change while the app is running. | `class MyWidget extends StatefulWidget` |  |  |
|BuildContext| Lets you move from one screen to another using route names. | `Navigator.pushNamed(context, '/about')` |  |  |
|super.key| Makes space around a widget inside its container. | `Padding(padding: EdgeInsets.all(8.0), child: ...)` |  |  |

|      | Aligns content in the center of the screen or container. | `Center(child: ...)` |  |  |

|      | Automatically puts widgets onto a new line when there's no space. | `Wrap(children: [...])` |  |  |

|      | This marks a method as one that’s replacing a method in a parent class. | `@override` |  |  |

|      | The special function in every widget that describes what gets drawn on the screen. | `Widget build(BuildContext context) {...}` |  |  |

|      | Required in every widget class to describe what to show. | `build` |  |  |

|      | A variable that helps the widget know where it is and lets it communicate with the app. | `BuildContext context` |  |  |

|      | A keyword used to pass a value to the parent widget. | `super.key` |  |  |

|      | A keyword that means the value won't change and is set once. | `const` |  |  |
public class Hello {
  public static void main(String[] args) {
        System.out.println("Hello World!");
        | Overloaded method/funtion or consxtructor | Uses the same name, but has different parameters |Pi
        | Concatenate | To comine Strings with other Strings and/or varibles | String greeting = "hello" + name ".";|||
[string notes](#string notes        
    }
}
```
###string notes


string have indices (plural for index,) which starts at 0. "Hello" has indices 0(H), 1(e). 9
