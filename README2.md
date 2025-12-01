# Домаћи задатак из техничке документације
 
## Задатак

Програм који на основу унете дужине **полупречника** круга израчунава **обим** О

$2 \cdot r \cdot \pi$

### Алгоритамска шема

<img width="1342" height="628" alt="Snimak ekrana 2025-11-27 150402" src="https://github.com/user-attachments/assets/bb59e7bb-2175-4da3-bf55-a77b7124366e" />


## Решење
```cs
using System;
using System.Collections.Generic;
using System.Linq;
using System.Net.Http.Headers;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApp11
{
    internal class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Unesi poluprečnik kruga:");
            double r;
            r=double.Parse(Console.ReadLine());
            double O=2*r*Math.PI;
            Console.WriteLine("Obim kruga je {0} cm", O);
        }
    }
}
```
### Тест примери

```Unesi poluprecnik kruga:
5

Obim kruga je 31.4159265358979 cm

C:\Users\radlovacki-08\Desktop\ConsoleApp11\ConsoleApp11\bin\Debug\ConsoleApp11.exe (process 2772) exited with code 0 (0x0).
Press any key to close this window . . .

Unesi poluprecnik kruga:
10

Obim kruga je 62.8318530717959 cm

C:\Users\radlovacki-08\Desktop\ConsoleApp11\ConsoleApp11\bin\Debug\ConsoleApp11.exe (process 4376) exited with code 0 (0x0).
Press any key to close this window . . .
```

### Објекти

|Редни број| Назив променљиве | Тип променљиве  |
|----------|------------------|-----------------|
|1.        |       `r`        |    `double`     |
|2.        |       `O`        |    `double`     |

