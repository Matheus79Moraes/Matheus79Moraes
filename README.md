 <p align="left"> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" title="Java" width="40" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg" title="Spring" width="40" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" title="JavaScript" width="40" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" title="HTML5" width="40" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" title="CSS3" width="40" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" title="VSCode" width="40" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/intellij/intellij-original.svg" title="IntelliJ" width="40" /> </p> ```

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
