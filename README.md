## WelcomeApp.exe
```cs
//WelcomeApp.cs
using System.Windows.Forms;

namespace DashApplication
{
  public class DashApp
  {
    public DashApp()
    {
      Console.WriteLine($"{WelcomeMessage}");
    }
  }

  static class Program
  {
    static void Main()
    {
      using (var app = new DashApp())
      {
        Application.Run(app);
      }
    }
  }
}
```
```
1>------ Build started: Project: ZIPCrackler, Configuration: Release Any CPU ------
1>  ZIPCrackler -> F:\Programming\Skidware\ZIPCrackler\app\ZIPCrackler.exe
========== Build: 1 succeeded, 0 failed, 0 up-to-date, 0 skipped ==========
1> Runtime-Output:
> I am Dashie and I love to code.  

> I have a ton of hobbies, one of them is programming, another one of my many hobbies is writing books.  You can find any public project related to the last two named categories in here.  If you prefer more context because of the not-user-friendly organization of folders and what not; then I would recommend going to my website PugPawz over ![here](https://pugpawz.com) if you are interested.  
> I also have my contact information present more nicely on there, but, if you are here just for my repositories, what are you waiting for?  Do not let me hold you back, live like you have never done before.  I love you all.  Peace out.

-Dashie
```
