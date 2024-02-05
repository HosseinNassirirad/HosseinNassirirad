# Hey there! 👋 I'm Hossein Nasirirad!

## About Me
- Software Engineer 🚀
- Former QA Engineer at Alibaba Travels Co.
- Currently working on Smartees project 🚀

## Education
- Bachelor's degree: Islamic Azad University Science and Research Branch
- Current: Master's in IT, University of Tehran 📚

## Skills
- C#
- .NET Framework
- Docker
- SQL Server

## Hobbies
- Rock Climbing 🧗
- Fitness 💪
- Illustration 🎨
- Photography 📷

## Find Me Online
- [LinkedIn](https://www.linkedin.com/in/hosseinnasirirad/)
- [Twitter](HosNas)
- [Instagram](HosseinNasirirad)

## Contact Me
- Email: Hossein.Nassirirad@gmail.com
  
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=HosseinNassirirad&hide_progress=true)
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=HosseinNassirirad&show_icons=true&theme=radical)




- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.repository_owner }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:     A preset of color, one of [github, github-dark, github-light]
    #  - color_snake: Color of the snake
    #  - color_dots:  Coma separated list of dots color.
    #                 The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                 Exactly 5 colors are expected.
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9
