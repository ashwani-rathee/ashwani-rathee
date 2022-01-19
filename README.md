####  Hi there <img src="https://github.com/TheDudeThatCode/TheDudeThatCode/blob/master/Assets/Hi.gif" width="29px"> You can call me [Ash][website]. I enjoy writing, solving problems and automating stuff. I'm a developer with experience in Flutter, Julia, Python, Nodejs with focus in Image/Audio signal processing, RL.
<!--
**ashwani-rathee/ashwani-rathee** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
```julia
Base.@kwdef struct AshwaniRathee
    job::String = "Undergrad Student"
    years::Int = 20
    website::String = "None"
    current_projects::Vector{String}
end

Base.summary(d::AshwaniRathee) = "Some $(d.years) year old $(d.job)"
workson(d::AshwaniRathee) = d.current_projects 
hobbies(::AshwaniRathee) = ("Taekwondo","Music", "programming")
favorite_project(::AshwaniRathee) = "MusicProcessing.jl"

# Begin my description
me = AshwaniRathee(current_projects = [
  "JoySpring.jl", 
  "MusicProcessing.jl",
  "JuliaImages Projects",
])

println(summary(me))
println("works on: $(join(me.current_projects, ", "))")
println("has hobbies: $(join(hobbies(me), ", "))")
```
[<img align="left" alt="Website" src="https://img.shields.io/website?down_color=red&down_message=offline&style=for-the-badge&up_message=online&url=https%3A%2F%2Fsreekaransrinath.github.io"/>][website]
[<img align="left" alt="Discord" src="https://img.shields.io/discord/384024830988648450?color=blue&label=Discord&logo=discord&style=for-the-badge"/>][discord]
[<img align="left" alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>][linkedin]
[<img align="left" alt="Medium" src="https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white"/>][medium]

[website]: https://ashwani-rathee.github.io
[twitter]: https://twitter.com/ashwani_rathee_
[linkedin]: https://www.linkedin.com/in/ashwani-rathee-0b7594192/
[medium]: https://medium.com/@ashwanirathee
[discord]: https://discord.gg/f2qmJnj2Vk

[<img align="left" alt="visitors" src="https://visitor-badge.glitch.me/badge?page_id=ashwani-rathee.ashwani-rathee"/>][website]
