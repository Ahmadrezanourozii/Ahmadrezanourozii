# Hi there, I'm Ahmadreza! 👋

```go
package main

import "fmt"

type ahmadrezanourozi struct {
	Role       string
	University string
	Company    string
	GitHub     string
	TechStack  []string
	Interests  []string
}

func NewAhmadreza() *ahmadrezanourozi {
	return &ahmadrezanourozi{
		Role:       "AI Engineer & Researcher",
		University: "FAU Erlangen-Nürnberg (MSc Artificial Intelligence)",
		Company:    "BMW (Working Student)",
		GitHub:     "ahmadrezanourozi",
		TechStack: []string{
			"Python", 
			"C++", 
			"Generative AI", 
			"RAG", 
			"Prompt Engineering",
		},
		Interests: []string{
			"Swing Trading", 
			"Data Visualization",
		},
	}
}

func main() {
	me := NewAhmadreza()
	fmt.Printf("Hello, I'm currently working as an %s at %s.\n", me.Role, me.Company)
}
