
# Hi, my name is Simen!

---
### 👨‍💻 About me:

I am an aspiring programmer with a great passion for the world of information technology. I am currently 16 years old and I started my exciting journey into the world of programming when I was only 13 years old.

🌱My experience For a year and a half I paid intense attention to the Python language and successfully mastered its basics. My efforts in learning Python allowed me to not only understand the basics of programming, but also to begin solving real-world problems and creating my own programs. I'm currently actively learning C++, expanding my skills and horizons in the world of programming. This language provides me with new opportunities and challenges that I look forward to.

- 🔭 Successfully completed 2 courses on Stepik
- ⚡I really want to master the IT profession and find a job
- 📫 How can you contact me:  [![Telegram Badge](https://img.shields.io/badge/-Cyud-blue?style=flat&logo=Telegram&logoColor=white)](https://t.me/Cyud2023) [![Gmail Badge](https://img.shields.io/badge/-Gmail-red?style=flat&logo=Gmail&logoColor=white)](mailto:cyud.2019@gmail.com)

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

  env:
    # a github token is required to fetch the contribution calendar from github API
    GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
