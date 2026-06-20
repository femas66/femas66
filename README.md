# Hello there 👋

![visitors](https://komarev.com/ghpvc/?username=femas66&label=Profile%20views&color=0e75b6&style=flat)

```rust
struct Welcome {
    name: String,
    role: String,
    language_spoken: Vec<String>,
    languages: Vec<String>,
    frameworks_libraries: Vec<String>,
    databases_tools: Vec<String>,
    workflow_systems: Vec<String>,
}

impl Welcome {
    fn new() -> Self {
        Welcome {
            name: String::from("Femas Akbar Faturrohim"),
            role: String::from("Student"),
            language_spoken: vec![String::from("id_ID")],
            languages: vec![
                "Go", "PHP", "Python", "JavaScript", "TypeScript"
            ].iter().map(|&s| s.to_string()).collect(),
            frameworks_libraries: vec![
                "Fiber", "Laravel", "Astro", "Flutter", "Tailwind CSS"
            ].iter().map(|&s| s.to_string()).collect(),
            databases_tools: vec![
                "PostgreSQL", "MySQL", "Docker", "Git", "Linux"
            ].iter().map(|&s| s.to_string()).collect(),
            workflow_systems: vec![
                "Obsidian", "Notion", "Automated Workflows"
            ].iter().map(|&s| s.to_string()).collect(),
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
