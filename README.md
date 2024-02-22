<h2> Hi, I'm Leo Batista! <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExbjdsN3J2dHk0N3c0cWs0MjAwOWI0amlhOWIzNzJpcmV0aThlaHZxbyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/G4s3kCibtD4mmtEjmV/giphy.gif" width="50"></h2>
<img align='right' src="https://media.giphy.com/media/ZFiBmGVClrgxt02N9X/giphy.gif" width="230">
<p><em>Computer networks student at <a href="https://www.ifpb.edu.br/">IFPB</a></br>Freelance Developer <a href=""></a><img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" width="30"> 
</em></p>

[![Instagram: leovento2](https://img.shields.io/badge/leobatista-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/leovento2/)
[![Linkedin: leobatista](https://img.shields.io/badge/leo%20batista-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/leo-batista-a3a208206/)
[![GitHub leobatista3](https://img.shields.io/badge/portfolio-000000?style=for-the-badge&logo=About.me&logoColor=white)](https://leobatista3.github.io/)


### <img src="https://media.giphy.com/media/jncITDpcZNg94j74aS/giphy.gif" width="50"> A little about me...  

```C
#include <stdio.h>
typedef struct {
    const char *code[7];
    const char *tools[7];
    const char *architecture[3];
} MyPreferences;
int main() {
    MyPreferences preferences = {
        .code = {"Javascript", "C#", "SQL", "Kotlin", "Ruby", "Python", "Java"},
        .tools = {"React", ".NET", "Node", "PostgreSQL", "Insomnia", "Jest", "Docker"},
        .architecture = {"microservices", "event-driven", "design system pattern"}
    };
    const char *categories[] = {"Code:", "Tools:", "Architecture:"};
    for (int j = 0; j < 3; j++) {
        printf("%s", categories[j]);
        const char **preferenceArray = (j == 0) ? preferences.code : (j == 1) ? preferences.tools : preferences.architecture;
        int preferenceCount = (j == 0 || j == 1) ? 7 : 3;
        for (int i = 0; i < preferenceCount; i++) {
            printf(" %s, ", preferenceArray[i]);
        }
        printf("\n");
    }
    return 0;
}
```

<img src="https://media.giphy.com/media/ixzf0b27REcINaconp/giphy.gif" width="60"> <em><b>Feel free to drop a "hello" if you enjoy connecting with diverse individuals</b><b> —I'd be delighted to get to know you better!so if you want to say</b> :)</em>



---
