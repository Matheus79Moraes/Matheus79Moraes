<p align="left">TECHS</p>

<div align="left">
  <img src="https://skillicons.dev/icons?i=vscode" height="40" alt="vscode logo" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=js" height="40" alt="javascript logo" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=java" height="40" alt="java logo" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=spring" height="40" alt="spring logo" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=intellij" height="40" alt="intellij logo" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=git" height="40" alt="git logo" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=github" height="40" alt="github logo" />
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
