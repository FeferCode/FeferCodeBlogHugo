# FeferCodeBlogHugo
#### Repo with main code for **FeferCodeBlog** 


Blog is based on **HUGO** static side generator. 
Theme used in blog:
1. [m10c-github.com](https://github.com/vaga/hugo-theme-m10c) 
2. [themes.gohugo.io](https://themes.gohugo.io/themes/hugo-theme-m10c/)

#### Submodule 
There is second repo in the project used to deploy generated website. 
All files are generated and stored in **public** folder. 
Commits created there are related to [fefercode.github.io](https://github.com/FeferCode/fefercode.github.io) repo.
From this repo [FeferCodeBlog](https://fefercode.github.io) is deployed to github pages.
```
git submodule add -b main git@github.com:FeferCode/fefercode.github.io.git public
```

#### Usefull **HUGO** commands:
```
hugo server  //starts local server
hugo new posts/HelloWorld.md  //generates new post
hugo -t hugo-theme-m10c  // generates static website to deploy

```

###### ToDo 
Add information about old app 

[AppStore DPI Calculator](https://apps.apple.com/pl/app/dpi-calculator-by-fefercode/id1451443420?l=pl)