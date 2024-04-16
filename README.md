

<h1 align="center">Hi, I'm Pablo 👨‍💻</h1>

![me](https://user-images.githubusercontent.com/80485682/215364549-dff0f41e-c250-4add-903b-b615e7536b4e.png)
___

<br>

* [Go to my portfolio ](https://pablocigoy.com/ "My portfolio") 🖥️





<br>

### Languages and Technologies

~~~ kotlin

class Developer(
    val name: String,
    val description: String,
    val codeSkills: List<String>,
    val frontEndTechnologies: Map<String, List<String>>,
    val backEndTechnologies: Map<String, List<String>>,
    val mobileTechnologies: Map<String, List<String>>,
    val databases: List<String>,
    val designTools: List<String>
) {
    fun printInfo() {
        println("Name: $name")
        println("Description: $description")
        println("Code Skills: ${codeSkills.joinToString(", ")}")
        println("Frontend Technologies: ${frontEndTechnologies.keys.joinToString(", ")}")
        println("Backend Technologies: ${backEndTechnologies.keys.joinToString(", ")}")
        println("Mobile Technologies: ${mobileTechnologies.keys.joinToString(", ")}")
        println("Databases: ${databases.joinToString(", ")}")
        println("Design Tools: ${designTools.joinToString(", ")}")
    }
}

fun main() {
    val pablo = Developer(
        name = "Pablo",
        description = "I am always looking for new challenges and opportunities to learn and grow. " +
                "I am a sociable person who thrives in team environments and is committed to constantly improving.",
        codeSkills = listOf("JavaScript", "TypeScript", "HTML5", "CSS3", "SQL", "Kotlin"),
        frontEndTechnologies = mapOf(
            "JavaScript" to listOf("React", "P5", "Handlebars"),
            "Python" to listOf("Tkinter"),
            "CSS" to listOf("Bootstrap", "Tailwind")
        ),
        backEndTechnologies = mapOf(
            "JavaScript" to listOf("Express", "NodeJs"),
            "Python" to listOf("Flask")
        ),
        mobileTechnologies = mapOf(
            "Android" to listOf("Kotlin")
        ),
        databases = listOf("MySQL", "MongoDB"),
        designTools = listOf("Figma")
    )

    println("This is me:")
    pablo.printInfo()
}


~~~

</br>



<br>


## some of my projects

* [Recipes website](https://be-chef.netlify.app/ "A website created in React where you can login, create, read, upload and delete recipes.")

* [A guide of Latin Restaurants in Berlin](https://sabor-latino.cyclic.app/ "You can login create new restaurants and descriptions, also you can see all the restaurants in the city")

* [Game - Save Oliver](https://pablo-mdz.github.io/Game-P5-Shooting/ "On this game you have to save Oliver from the spiders and mouses")

* [Truco, counter game](https://dulcet-pudding-105e47.netlify.app/ "A simple counter for the Truco game")

* [Whatsapp Clone](https://github.com/Pablo-Mdz/WhatsSyntax/ "A Clone of Whatsapp with some implementations")

* [Game - Game of thrones](https://github.com/Pablo-Mdz/GOT-Game-kotlin/ "A game based in Game of thrones serie to play in console")


<br>





