
## Experience 
> Columbia College Chicago: Programming 101
> - *Proficient in C#*


## Works 
### C# Console Applications 

> **Adventure Game** 
>
> - A text-based adventure game that changes based on the player's choice of "class" (Sorcerer, Thief, Bard)
> 
> 	![AdventureGameScreenshot](https://github.com/user-attachments/assets/d300d6b3-3a2f-469f-a581-3800429d9e83)


> **Cumulative Verse Song** 
> - An application that efficiently prints the lyrics of "The 12 Days of Christmas" using nested loops.
> 
> 	![CumulativeVerseSong](https://github.com/user-attachments/assets/0de43fb8-3ee2-4cd4-9e96-77a079b6de32)
> - Additionally, the application it plays a short gingle upon startup...
> 	```
> 	public void PlayNote(int frequency, int duration)
> 	{
>     	Console.Beep(frequency, duration);
>     	Thread.Sleep(50); // Short pause between notes
> 	}
> 
> 	public void PlaySong()
> 	{
>     	int C = 261, D = 294, E = 329, F = 349, G = 392, A = 440, A_Sharp = 466, B = 494;
>     	int quarter = 300, half = 600, whole = 850;
> 
>     	PlayNote(C, quarter); PlayNote(C, quarter); PlayNote(C, half); // "On the first"
>     	PlayNote(F, quarter); PlayNote(F, quarter); PlayNote(F, half); PlayNote(E, quarter);// "Day if Christmas"
>     	PlayNote(F, quarter); PlayNote(G, quarter); PlayNote(A, quarter); //"My true love"
>     	PlayNote(A_Sharp, quarter); PlayNote(G, quarter); PlayNote(A, whole); //  "Came to me!"
> 	}
> 	```


> **Simple Cipher** 
>  - A substitution cipher that encodes a string of the user's choice
>
> 		![SubstitutionCipherScreenshot](https://github.com/user-attachments/assets/e2ca7e2d-3cef-4f29-b762-b9d52060bb6c)


### C# WPF Applications
> **Pet Bear Game** 
>	- A minigame where you "pat" a teddy bear. The more pats you give, the more upgrades you can buy!
>
>   	![PetBearScreenshot](https://github.com/user-attachments/assets/0ef897a3-d1e9-4fd4-9356-2055e6dd9191)


> **Weather Reader** 
> - A simple application that tells you the weather from the OpenWeatherMap.com API...
>
> 	![WeatherDataScreenshot](https://github.com/user-attachments/assets/26f1a9cd-fd44-4b40-bd19-36ad8b34a2ce)
