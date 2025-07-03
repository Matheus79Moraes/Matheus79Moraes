<p align="left">TECHS</p>

<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" height="40" alt="git logo" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=github" height="40" alt="github logo" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" height="40" alt="java logo" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg" height="40" alt="spring logo" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/intellij/intellij-original.svg" height="40" alt="intellij logo" />
</div>

<h1 align="center">About Me</h1>

```go
package matheusmoraes

func getProfile() (Contact, Life, Coding) {
    contact := Contact{
        Email:   "matheus66moraes@gmail.com",
        
    }

    life := Life{
        Name:    "Matheus Moraes",
        Alias:   "matheus",
        Langs:   []string{"portuguese"},
        Country: "br",
        Age:     22,
    }

    coding := Coding{
        Langs: map[string][]string{
            "core":          {"java", "javascript"},
            "hasExperience": {"html", "css"},
        },
        Specialties: []string{"web", "apis", "automations"},
        Ide:         []string{"vscode", "intellij"},
        Frameworks:  []string{"spring"},
    }

    return contact, life, coding
} 
