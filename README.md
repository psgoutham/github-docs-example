# Writing good documentation

## Step 1 - Using Code Blocks

Code blocks in markdown make it *very easy* for tech people to **copy, paste and share** code. 
A good __cloud engineer__ user code blocks wherener possible.
Because it allows others to copy and paste their code to replicate or research issues.

- In order to create code blocks in markdown you need to use three backticks (`)
- Not to be confused with quotation (')

```c#
using System;

class Program
{
    static void Main()
    {
        int dividend = 10;
        int divisor = 0;

        try
        {
            int result = dividend / divisor;
            Console.WriteLine($"Result: {result}");
        }
        catch (DivideByZeroException ex)
        {
            Console.WriteLine($"Error: {ex.Message}");
        }
    }
}
```
<!-- ![sample](https://github.com/psgoutham/github-docs-example/assets/123158351/c7539087-7aef-44ee-8ea2-85eac1a4c133) -->

<img width="200px" height="200px" src="https://github.com/psgoutham/github-docs-example/assets/123158351/c7539087-7aef-44ee-8ea2-85eac1a4c133" />
