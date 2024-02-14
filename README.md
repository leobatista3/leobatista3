<h2> Hi, I'm Leo Batista! <img src="https://img.freepik.com/psd-gratuitas/tridimensional-imagem-de-computador_53876-1610.jpg?w=740&t=st=1707942431~exp=1707943031~hmac=d816b061afd6d0bcb784a3f704d008258da69d8e9fe325da7bc5a3e0b70d4a28" width="50"></h2>
<img align='right' src="https://media.giphy.com/media/ZFiBmGVClrgxt02N9X/giphy.gif" width="230">
<p><em>Computer networks student at <a href="https://www.ifpb.edu.br/">IFPB</a><img src="https://media.giphy.com/media/fYSnHlufseco8Fh93Z/giphy.gif" width="30"></br>Freelance Developer <a href=""></a><img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" width="30"> 
</em></p>

[![Instagram: leovento2](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/leovento2/)
[![Linkedin: leobatista](https://img.shields.io/badge/-leo%20batista-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/leo-batista-a3a208206/)](https://www.linkedin.com/in/leo-batista-a3a208206/)
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
