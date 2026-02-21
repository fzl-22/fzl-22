<!-- 
# Hello there 👋
-->

```golang
package main

import (
	"fmt"
	"strings"
)

type Profile struct {
	Name         string
	Role         string
	Technologies []string
}

func NewProfile(name string, role string, technologies []string) *Profile {
	return &Profile{
		Name:         name,
		Role:         role,
		Technologies: technologies,
	}
}

func (p *Profile) formatLanguages() string {
	return strings.Join(p.Technologies, ", ")
}

func (p *Profile) SayHi() {
	fmt.Println("Hi! Here is a bit about me:")
	fmt.Println()
	fmt.Printf("  Name			: %s\n", p.Name)
	fmt.Printf("  Role			: %s\n", p.Role)
	fmt.Printf("  Technologies	: %s\n", strings.Join(p.Technologies, ", "))
	fmt.Println()
	fmt.Println("I hope you find something interesting here!")
}

func main() {
	me := NewProfile("Ahmad Faisal", "Software Engineer", []string{
		"Go",
		"Fiber",
		"Node.js (TypeScript and JavaScript)",
		"Express.js",
		"Nest.js",
		"Swagger",
		"Bash",
		"PostgreSQL",
		"MySQL",
		"Linux",
		"Git",
		"Bash",
		"AWS",
		"Kubernetes",
		"Docker",
		"Terraform",
		"Jenkins",
		"GitHub Actions",
		"Firebase",
		"Dart",
		"Flutter",
		"React Native",
		"TestFlight",
	})
	me.SayHi()
}
```

<!--
## 🔧 Technologies & Tools

![](https://img.shields.io/badge/OS-Arch_Linux-informational?style=flat&logo=arch-linux&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/Editor-Neovim-informational?style=flat&logo=neovim&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/Editor-VS_Code-informational?style=flat&logo=visual-studio-code&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/Code-Go-informational?style=flat&logo=go&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/Code-NestJS-informational?style=flat&logo=nestjs&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/Code-Express-informational?style=flat&logo=express&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/Code-GraphQL-informational?style=flat&logo=graphql&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/Code-Flutter-informational?style=flat&logo=flutter&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/Code-NodeJS-informational?style=flat&logo=nodedotjs&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/Code-TypeScript-informational?style=flat&logo=typescript&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/Code-JavaScript-informational?style=flat&logo=javascript&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/Code-Dart-informational?style=flat&logo=dart&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/Code-Python-informational?style=flat&logo=python&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/Shell-Bash-informational?style=flat&logo=gnu-bash&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/Shell-Fish-informational?style=flat&logo=fish-shell&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/Tools-MongoDB-informational?style=flat&logo=mongodb&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/Tools-PostgreSQL-informational?style=flat&logo=postgresql&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/Tools-MySQL-informational?style=flat&logo=mysql&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/Tools-Docker-informational?style=flat&logo=docker&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/Tools-Git-informational?style=flat&logo=git&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/Tools-Vagrant-informational?style=flat&logo=vagrant&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/Tools-AWS-informational?style=flat&logo=amazon-web-services&logoColor=white&color=6aa6f8)

-->

<!--
## 💻 Most Used Languages

![My most used languages](https://github-readme-stats.vercel.app/api/top-langs/?username=fzl-22&hide=Jupyter%20Notebook)

-->

<!-- ## &#x1f4c8; GitHub Stats

<a href="https://github.com/Zhenye-Na/Zhenye-Na">
  <img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=zhenye-na&hide=c%2B%2B,c,matlab,assembly&title_color=6aa6f8&text_color=8a919a&icon_color=6aa6f8&bg_color=22272e" alt="Zhenye's GitHub Stats" />
</a>

<a href="https://github.com/Zhenye-Na/Zhenye-Na">
  <img align="center" src="https://github-readme-stats.vercel.app/api?username=zhenye-na&show_icons=true&line_height=27&count_private=true&title_color=6aa6f8&text_color=8a919a&icon_color=6aa6f8&bg_color=22272e" alt="Zhenye's GitHub Stats" />
</a> -->

<!--
## 🏆 GitHub Trophies

[![trophy](https://github-profile-trophy.vercel.app/?username=fzl-22&theme=nord&column=7)](https://github.com/ryo-ma/github-profile-trophy)
-->

<!--
## 🗂️ Highlight Projects

<a href="https://github.com/Zhenye-Na/DA-RNN">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=zhenye-na&repo=DA-RNN&show_icons=true&line_height=27&title_color=6aa6f8&text_color=8a919a&icon_color=6aa6f8&bg_color=22272e" alt="DA-RNN" />
</a>

<a href="https://github.com/Zhenye-Na/crnn-pytorch">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=zhenye-na&repo=crnn-pytorch&show_icons=true&line_height=27&title_color=6aa6f8&text_color=8a919a&icon_color=6aa6f8&bg_color=22272e" alt="crnn-pytorch" />
</a>
-->

<!-- ## 👨‍💻 This week, I spent my time on:

[![zhenye's wakatime stats](https://github-readme-stats.vercel.app/api/wakatime?username=nazhenye&line_height=27&title_color=6aa6f8&text_color=8a919a&icon_color=6aa6f8&bg_color=22272e)](https://github.com/anuraghazra/github-readme-stats) -->
