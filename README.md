###  Hi I’m Mohammadreza Ziadiparast 👋
<div >
  <p>
    I am a creator and developer of backend infrastructure for system and web software. I have been actively involved in development and system administration since 2016, and during this time, my goal has been to implement and develop practical tools for the general public, aiming to address some of their challenges and make tasks easier for them!


My vision is freedom and growth for everyone.
  </p>

<img align="top" src="https://github-readme-stats.vercel.app/api?username=ziadiparast&show_icons=true&theme=radical&hide_rank=true&hide_title=true&rank_icon=github"> 
</div>

<!---
ziadiparast/ziadiparast is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

## ⚡ Tec Stacks

```php

namespace Self\Mind\Skills\Virtual;

use Self\Mind\About;

class TechStacks extend Stack {

  protected string $stack = "tech";
  
  public function getProgrammingLanguages(): array
  {
      return $this->neuron
        ->programmingLanguages()
        ->sortBy('experience')
        ->with('frameworks')
        ->get()
        ->toArray(); // ['PHP' => [ 'frameworks' => [ 'laravel' ] ] , 'JavaScript', 'Python', 'C++', 'GO']
  }

  public function getDatabases(): array
  {
      return $this->neuron
        ->databases()
        ->get()
        ->toArray(); // ['MySQL', 'SQLite', 'MongoDB', 'Redis']
  }

  public function getOther(): array
  {
      return $this->neuron
        ->otherTechs()
        ->get()
        ->toArray(); // [ 'Docker', 'Git', ... ]
  }


  public function suggestTech(): string
  {
    echo "Please Send your suggestion to me in : ".PHP_EOL.About::getSocialPages()->toJson()
  }

}


```

## ⚡ Platforms
```bash
➜  ~ lsb_release -i | cut -d ":" -f 2 | sed 's/\s*//g'
Ubuntu
```
## 📫 Contact Me
```json
{
    "website": "https://ziadiparast.ir",
    "linkedin": "https://ir.linkedin.com/in/ziadiparast",
    "telegram": "https://t.me/mrziadiparast",
    "instagram": "https://instagram.com/ziadiparast"
}
```
I'm always open to interesting conversations, collaboration opportunities, and hearing about exciting new projects.🌱

Let's connect and build amazing things together! 🥰

## 💙 Donate

If you find my work valuable or would like to support me, you can contribute by donating.
Your generosity will go a long way in helping me continue my work and create more useful resources.

- Donate via Bitcoin : `bitcoin:bc1q0xkwr9404ahf7sjpd67q57kvufxnjawcd2tund`
- Donate via Litecoin : `litecoin:ltc1qkv6ndecjpus7d8vnl5le33d95j9l2p2w6uu762`
- Donate via Zarrinpal (IRAN) : [ Donate ](https://zarinp.al/ziadiparast)






