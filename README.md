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

<h2 align="center">Skills</h2> <p align="center"> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" height="40" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg" height="40" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="40" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="40" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="40" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" height="40" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/intellij/intellij-original.svg" height="40" /> </p> ```

