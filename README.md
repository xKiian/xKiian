<p align="center">
  <img src="https://wakatime.com/badge/user/839267df-3912-44c6-97f4-9e3f0425b716.svg" alt="Total time coded since Feb 28 2023" />
</p>

<p align="center">
  <img height="25" src="https://api.visitorbadge.io/api/VisitorHit?user=xkiian&countColor=%234a12ba" alt="Profile Views"/>
  <img height="25" src="https://img.shields.io/github/followers/xkiian?color=4a12ba&style=for-the-badge&logo=github&label=Follow" alt="Followers"/>
  <img height="25" src="https://img.shields.io/github/stars/xkiian?color=4a12ba&style=for-the-badge&logo=github&label=Stars" alt="Stars"/>
</p>

<p align="center"> 
    <img src="https://github-readme-streak-stats-eta-three.vercel.app?user=xkiian&theme=tokyonight&hide_border=true" alt="GitHub Streak" width="60%">
</p>

```go
package xkian

import "fmt"

type Profile interface {
	Contact() string
	Languages() []string
	Coding() CodingProfile
}

type CodingProfile struct {
	Editors      []string
	Specialities []string
	Languages    map[string][]string
}

type XKian struct{}

func (XKian) Contact() string {
	return ".xkian"
}

func (XKian) Languages() []string {
	return []string{"German", "English"}
}

func (XKian) Coding() CodingProfile {
	return CodingProfile{
		Editors:      []string{"GoLand", "PyCharm", "VS Code"},
		Specialities: []string{"Reverse Engineering", "Automation"},
		Languages: map[string][]string{
			"pro":          {"Go", "Python"},
			"intermediate": {"C++"},
			"learning":     {"WebAssembly"},
		},
	}
}

func main() {
	var me Profile = XKian{}

	fmt.Println("discord:", me.Contact())
	fmt.Println("languages:", me.Languages())

	c := me.Coding()
	fmt.Println("editors:", c.Editors)
	fmt.Println("specialities:", c.Specialities)
	fmt.Println("coding languages:", c.Languages)
}

```

