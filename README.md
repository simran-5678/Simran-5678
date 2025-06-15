## Hi there 👋
# Hi there, I'm Simran 👋

Welcome to my GitHub profile!  
I'm passionate about technology, coding, and continuous learning. 🚀

## 👩‍💻 About Me

- 🎓 Currently pursuing my studies in Computer Science / Engineering / [your field]
- 💻 Passionate about Python, Data Science, Backend Development, and more
- 🌱 Currently learning new technologies and expanding my skills

## 💡 Fun Fact

- I love solving problems, building projects, and exploring new technologies.
- package main

import (
	"fmt"
)

type Bio map[string]string

func main() {
	for k, v := range GetBio() {
		fmt.Printf("%+v: %+v\n", k, v)
	}
}

func GetBio() Bio {
	return Bio{
		"- ⚡ Quick bio:":                    "A kind of metalHead-melomaniac-gearAddict-amateurMusician-traveler-foodLover-gamer-coder-programmer-catLover-sportsAficionado hybrid",
		"- 🔭 I’m currently working on":      "Tredicom as a Senior Software Developer --- UAdeC as a Part Time Teacher",
		"- 🌱 I’m currently learning":        "Golang, MongoDB, RabbitMQ, K8s, GCP (Tech stack from my company) --- Sharpening my Front End Skills for the MERN stack (Personal goal)",
		"- 👯 I’m looking to collaborate on": "Python, Golang and Docker related projects",
		"- 🤔 I’m looking for help with":     "Anything related to what I am currently learning 😅",
		"- 💬 Ask me about":                  "Python, PHP, Laravel, SQL, Software Design & Architecture, Web-Dev and SEO",
		"- 📫 How to reach me:":              "https://github.com/AnhellO#you-can-reach-me-at-alien",
	}
}
