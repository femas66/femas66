# Hello there 👋

![visitors](https://komarev.com/ghpvc/?username=femas66&label=Profile%20views&color=0e75b6&style=flat)

```rust
struct Welcome {
    name: &'static str,
    role: &'static str,
    language_spoken: &'static [&'static str],
    languages: &'static [&'static str],
    frameworks_libraries: &'static [&'static str],
    databases_tools: &'static [&'static str],
    workflow_systems: &'static [&'static str],
}

fn main() {
    let me = Welcome {
        name: "Femas Akbar Faturrohim",
        role: "Student",
        language_spoken: &["id_ID"],
        languages: &["Go", "PHP", "Python", "JavaScript", "TypeScript"],
        frameworks_libraries: &["Fiber", "Laravel", "Astro", "Flutter", "Tailwind CSS"],
        databases_tools: &["PostgreSQL", "MySQL", "Docker", "Git", "Linux"],
        workflow_systems: &["Obsidian", "Notion", "Automated Workflows"],
    };

    println!("Hello! I'm a developer who loves learning new things.");
}
```
