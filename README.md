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
