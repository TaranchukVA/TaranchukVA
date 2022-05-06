Welcome to my profile!
```csharp
public const string GIT = @"https://github.com/TaranchukVA"; 
public const string TG = @"https://t.me/ItIsMeVladimir";
public const string RESUME = @"https://disk.yandex.ru/i/P5sl1ekIZwgTCA";
public List<Language> myLanguages = new List<Language>() {CSharp, JS, Cpp, SQL, Python};
public List<Interest> myInterests = new List<Interest>() {WebDev, BackEnd, FrontEnd};
public sting aboutMe = "Good guy and gifted programmer";
    
public Profile TaranchukVA = new Profile(){
	gitLink =  GIT,
	telegramLink = TG,
	resume = RESUME,
	languages = myLanguages,
	interests = myInterests,
	about = aboutMe
	};
	
public IActionResult VisitMe(Guest you)
{
	you.CheckProfile(TaranchukVA);

	if ( you.IsInterested || you.HaveAVacanсy || you.HaveAProject)
		you.SendResponce(TaranchukVA);
	
	you.ShareProfile(TaranchukVA);
		
	return Ok("Thank You!") ;
}

```





<!--
**TaranchukVA/TaranchukVA** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
