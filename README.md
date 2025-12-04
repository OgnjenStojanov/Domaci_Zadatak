# Domaci_Zadatak

## Zadatak

Програм који на основу унете дужине **дијагонале** правоугаоника d израчунава 
**полупречник** описане кружнице r. 

### Formula

$$r=\frac{d]{2}$$

## Resenje

```csharp
using System;

namespace ConsoleApp11
{

    internal class Program

    {

        static void Main(string[] args)
        {
            
            Console.Write("Unesi dijagonalu d ");
            int d = int.Parse(Console.ReadLine());
            int r = d / 2;
            Console.WriteLine("r je {0}", r);


        }

        

    }
}
```

### primeri

``` text
Unesi dijagonalu d 12
r je 6

C:\Users\radlovacki-01\Desktop\ConsoleApp11\ConsoleApp11\bin\Debug\ConsoleApp11.exe (process 15180) exited with code 0 (0x0).
To automatically close the console when debugging stops, enable Tools->Options->Debugging->Automatically close the console when debugging stops.
Press any key to close this window . . .
```

``` text
Unesi dijagonalu d 6
r je 3

C:\Users\radlovacki-01\Desktop\ConsoleApp11\ConsoleApp11\bin\Debug\ConsoleApp11.exe (process 15180) exited with code 0 (0x0).
To automatically close the console when debugging stops, enable Tools->Options->Debugging->Automatically close the console when debugging stops.
Press any key to close this window . . .
```








| Naziv promenljive | Tip    | Opis                          |
|-------------------|--------|-------------------------------|
| `d `                | `double` | dijagonala                    |
| `r`                 | `double` | poluprecnik                   |
