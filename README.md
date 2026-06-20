# Hello there 👋

![visitors](https://komarev.com/ghpvc/?username=femas66&label=Profile%20views&color=0e75b6&style=flat)

```rust
struct Welcome {
    name: String,
    role: String,
    language_spoken: Vec<String>,
}

impl Welcome {
    fn new() -> Self {
        Welcome {
            name: String::from("Femas Akbar Faturrohim"),
            role: String::from("Student"),
            language_spoken: vec![String::from("id_ID")],
        }
    }
    fn say_hi(&self) {
        println!("Hello! I'm a developer who loves learning new things.");
    }
}

fn main() {
    let me = Welcome::new();
    me.say_hi();
}
```
## 🔧 Technologies & Tools

- **Languages:** Go, PHP, Python, JavaScript, TypeScript
- **Frameworks & Libraries:** Fiber, Laravel, Astro, Flutter, Tailwind CSS
- **Databases & Tools:** PostgreSQL, MySQL, Docker, Git, Linux
- **Workflow & Systems:** Obsidian, Notion, Automated Workflows
