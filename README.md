## Коротко обо мне
```Меня зовут Александр Койков.```   
```Увлекаюсь изучением технологий веб-разработки, разработки десктопных приложений, игр. ```  
```Буду рад получить обратную связь по любым вопросам.```

### Уровень образования
```В 2011 году окончил обучение в Вятском колледже управления и новых технологий```  
```по специальности Программное обеспечение вычислительной техники и автоматизированных систем.```

### Мой стек технологий 
![Static Badge](https://img.shields.io/badge/CSS-%232F323A?style=for-the-badge)
![Static Badge](https://img.shields.io/badge/HTML5-%232F323A?style=for-the-badge&logo=html5&logoColor=%23E34F26)
![Static Badge](https://img.shields.io/badge/GIT-%232F323A?style=for-the-badge&logo=git&logoColor=%23F05032)

### Обратная связь
[![Static Badge](https://img.shields.io/badge/telegram-%2326A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/alexkoykov)
[![Static Badge](https://img.shields.io/badge/send%20e--mail-%2326A5E4?style=for-the-badge&logo=maildotru&logoColor=white)](mailto:alexkoykov@inbox.ru)
[![Static Badge](https://img.shields.io/badge/GIThub-%2326A5E4?style=for-the-badge&logo=github&logoColor=white)](https://github.com/alexkoykov)

### Карта проектов


<!--
### Статистика на GitHub
![GitHub stats](https://github-readme-stats.vercel.app/api?username=alexkoykov&show_icons=true&hide=prs,issues,contribs&theme=dark)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=alexkoykov&layout=compact&theme=dark)
-->

```mermaid
%% START SCRIPT
graph TD
%% DEFINE

  ROOT@{shape: processes, label: "**SELF SKILL**"}
  
  git@{shape: div-rect, label: "Git"}
  github@{shape: div-rect, label: "GitHub"}

  lesson_01@{shape: rect, label: "Lesson 01"}
  lesson_02@{shape: rect, label: "Lesson 02"}

  html@{shape: div-rect, label: "HTML5"}
  css@{shape: div-rect, label: "CSS"}
  js@{shape: div-rect, label: "JavaScript"}

%% END DEFINE
%% LINKS

  click lesson_01 "https://youtu.be/0Y-fneoUIO8"
  click lesson_02 "https://youtu.be/O00FTZDxD0o"

%% END LINKS
%% LOGICS

  ROOT ==> CTR_VER
    subgraph CTR_VER [*CONTROL VERSION*]
      git --> github 
      github --> git
    end

  CTR_VER --> CTR_VER_SRC
    subgraph CTR_VER_SRC [*HELPFUL TOOLS*]
      lesson_01
      lesson_02
    end  

%% END LOGICS
%% END SCRIPT
```
