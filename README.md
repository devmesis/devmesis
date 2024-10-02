<!-- Divider -->
<img src="https://raw.githubusercontent.com/Devmesis/Devmesis/main/Assets/Divider.gif">

<!-- Header -->
<div align="center">
    <a href="https://www.devmesis.com">
<img src="https://github.com/Devmesis/Devmesis/blob/main/Assets/devmesis.png?raw=true" align="center" style="width: 25%; margin-bottom: 20px; border-radius: 50%;">
    </a>
</div>

<!-- Name -->
<div align="center">
<h2 align="center">Hey there! 
  <a href="https://www.devmesis.com">
    <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="20px"></h2>
  </a>


  <p> 
I'm a software artist straight out of the Netherlands. 
<br>
<br>
I have a genuine curiosity for the world of tech, which has led me to become a jack of all trades in various domains: Hardware, Software, API, Artificial Intelligence, Security, Gadgets, and a bit of tweaking.
<br>
<br>
But forget about labels; the best way to really get to know me is by reaching out and getting in <a href="https://www.devmesis.com/contact">touch</a>.
  </p>
    <br>
</div>

<!-- Bio -->
<div align="center">
  <br>
  <h2>Bio</h2>
  <br>
</div>

```rust
struct Me {
    name: String,
    username: String,
    skills: Vec<String>,
}

impl Me {
    fn new(name: &str, username: &str, skills: &[&str]) -> Me {
        Me {
            name: name.to_owned(),
            username: username.to_owned(),
            skills: skills.iter().map(|&skill| skill.to_owned()).collect(),
        }
    }

    fn introduction(&self) -> String {
        format!("Hi, i go by the name {}.", self.name)
    }

    fn quote(&self) -> String {
        "Painting is silent poetry, and poetry is painting that speaks.".to_owned()
    }
}

fn main() {
    let devmesis = Me::new("Devmesis", &[
        "Creative", "Fullstack", "Hardware", "Software", "Artificial Intelligence", 
        "Security", "Gadgets", "a bit of tweaking",
    ]);

    println!("{}", devmesis.introduction());
    println!("{:?}", devmesis.skills);
    println!("{}", devmesis.qoute());
}

```
   
<!-- Architecture -->
<div align="center">
  <br>
  <h2>Architecture</h2>
  <br>
</div>

```bash
> fetch

console.log(`
┌───────────┬──────────────────────────────────────────┐
│  OS       │   MacOS                                  │
│  Host     │   MacBook                                │
│  Terminal │   Ghostty                                │
│  Shell    │   Zsh                                    │
│  IDE      │   Zed                                    │
│  Theme    │   Dracula Pro                            │
│  Font     │   Berkeley Mono                          │
└───────────┴──────────────────────────────────────────┘
`);
```

<!-- Bottom -->
<div align="center">
  <br>
  <img src="https://raw.githubusercontent.com/Devmesis/Devmesis/main/Assets/Bottom.svg"/>
  <img src="https://raw.githubusercontent.com/Devmesis/Devmesis/main/Assets/Divider.gif">
  <br>
</div>


<!-- Footer -->
<div align="center">
  <br>
  <p>© 2024 Devmesis All rights reserved.</p>
  <p>Designed and developed by <a href="https://www.devmesis.com">Devmesis</a></p>
  <br>
</div>
