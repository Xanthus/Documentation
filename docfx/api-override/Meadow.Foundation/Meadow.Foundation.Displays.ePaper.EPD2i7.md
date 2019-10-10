---
uid: Meadow.Foundation.Displays.ePaper.EPD2i7
remarks: *content
---

Meadow.Foundation.Displays.ePaper.EPD2i7

### Code Example

The following example shows how to ...:

```csharp
using System.Threading;
using Meadow;
using Meadow.Foundation.Displays.ePaper;

namespace EPD2i7_Sample
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

![](../../API_Assets/Meadow.Foundation.Displays.ePaper.EPD2i7/EPD2i7.svg)