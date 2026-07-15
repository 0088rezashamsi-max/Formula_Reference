# Formula Reference

A console application for instant calculation of physics, mathematics, and chemistry formulas.

## Features
- Organized into three sections: **Physics**, **Mathematics**, **Chemistry**
- Search formulas by name or keyword
- View all available formulas
- Enter values and get results immediately
- Easily extendable with new formulas

## Prerequisites
- [.NET 10 SDK](https://dotnet.microsoft.com/en-us/download/dotnet/10.0)
- A C# code editor (Visual Studio Code, Visual Studio, etc.)

## Installation & Usage
1. Create a new console project (optional):
   ```bash
   dotnet new console -n FormulaReference
   cd FormulaReference
Copy the entire code into Program.cs.

Run the application:

bash
dotnet run
How to Use
Run the program. At the main menu, type the name of a section: Physics, Mathematics, or Chemistry.
Inside each section, choose:

1 to search and calculate a formula

2 to list all formulas in that category

3 to return to the main menu

Example
text
Enter the name of the desired section (or 'Exit' to quit):
Physics
...
Result: F = 10 × 9.8 = 98 Newtons
Contributing
Contributions are welcome. To add a new formula:

Add its string constant in the appropriate Formulas_* struct.

Implement the calculation logic in the Solve*Formula method.

Follow the naming convention (F11, M11, C11).

Submit a pull request with your changes.

License
This project is open source.

Made with ❤️ for those who hate repetitive calculations.
