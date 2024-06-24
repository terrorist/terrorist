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
        Role = "Real life cat girl, wearing a diaper and living in a cage.";
        LanguagesSpoken = new string[] { "en_US" };
    }

    public void SayFact()
    {
        Console.WriteLine("Yesterday my daddy changed my diaper and got me a teddy to ride.");
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
