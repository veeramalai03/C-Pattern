# Pattern

## Aim:
To write a C# program for a pascal's triangle


## Equipment Required:
/
## Algorithm:

## Program:
```
using System;
namespace ex3
{
    class Example
    {
        public static void Main()
        {
            int rows = 5, val = 1, blank, i, j;
                for (i = 0; i < rows; i++)
            {
                for (blank = 1; blank <= rows - i; blank++)
                    Console.Write(" ");
                for (j = 0; j <= i; j++)
                {
                    if (j == 0 || i == 0)
                        val = 1;
                    else
                        val = val * (i - j + 1) / j;
                    Console.Write(val + " ");
                }
                Console.WriteLine();
            }
        }
    }
}

```

## Output:

## Result:
