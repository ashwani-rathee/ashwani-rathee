### Hi there 👋

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
    years::Int = 19
    website::String = "None"
    current_projects::Vector{String}
end

Base.summary(d::AshwaniRathee) = "Some $(d.years) year old $(d.job)"
workson(d::AshwaniRathee) = d.current_projects 
hobbies(::AshwaniRathee) = ("Taekwondo","Music", "programming")
favorite_project(::AshwaniRathee) = "Enigma.jl"

# Begin my description
me = AshwaniRathee(current_projects = [
  "Enigma.jl", 
  "MusicProcessing.jl",
  "Learning-Julia.jl",
])

println(summary(me))
println("works on: $(join(me.current_projects, ", "))")
println("has hobbies: $(join(hobbies(me), ", "))")
```
![AshwaniRathee's github stats](https://github-readme-stats.vercel.app/api?username=ashwani-rathee&show_icons=true&hide=["issues"])

 Poster for design competition : [here](https://drive.google.com/file/d/1VRMRe-9_A8dY3VDy0fMQB996ajTzoeCq/view?usp=sharing)
 Deep Learning by Ian GoodFellow : [here](https://drive.google.com/drive/folders/1w4OGfhNP-5KpFJxyJGpUCEpSeYpF44m2?usp=sharing)
