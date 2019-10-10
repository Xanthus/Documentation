---
uid: Meadow.Foundation.Displays.ePaper.EPD1i54
remarks: *content
---

Meadow.Foundation.Displays.ePaper.EPD1i54

### Code Example

The following example shows how to ...:

```csharp
using System.Threading;
using Meadow;
using Meadow.Foundation.Displays.ePaper;

namespace EPD1i54_Sample
{
    public class Program
    {
        static IApp _app; 
        public static void Main()
        {
            _app = new MeadowApp();
        }
    }
    
    public class MeadowApp : AppBase<F7Micro, App>
    {
        public MeadowApp ()
        {
            //Example code here
        }
    }
}
```

### Circuit Example

![](../../API_Assets/Meadow.Foundation.Displays.ePaper.EPD1i54/EPD1i54.svg)