<p align="left"> <img src="https://komarev.com/ghpvc/?username=terrorist&label=Profile%20views&color=f5c2ec&style=flat" alt="terrorist" /> </p>

```csharp
using System;

class Info
{
    public string Name { get; set; }
    public string Role { get; set; }
    public string[] LanguagesSpoken { get; set; }

    public Info()
    {
        Name = "Terrorist";
        Role = "Software Engineer";
        LanguagesSpoken = new string[] { "da_DK", "en_US" };
    }

    public void SayFact()
    {
        Console.WriteLine("I love myself. Even though I look like a BURNT chicken nugget, I still love myself.");
    }
}

class Program
{
    static void Main()
    {
        Info me = new Info();
        me.SayFact();
    }
}
