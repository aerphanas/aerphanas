<!--```javascript
🐧                                           GitTerm - aerphanas:master                                     ─ ■ X 
```
```haskell
~ λ █ gitfetch --description=full --syle=fashionable --user=aerphanas --password=***************

  ┌─────────────────────────────────────────┐  
  │                                         │  
  │                                         │  
  │                                         │  
  │                                         │  
  │      _______\)%%%%%%%%._                │  
  │     `''''-'-;   % % % % %'-._           │  
  │             :b) \            '-.        │  
  │             : :__)'    .'    .'         │  
  │             :.::/  '.'   .'             │  
  │             o_i/   :    ;               │  
  │                    :   .'               │  
  │                     ''`                 │  
  │                                         │  
  │            MAGICAL  CREATURE            │  
  │                                         │  
  └─────────────────────────────────────────┘  
`````
```racket
;     mm                                  mm     mm           
;   @@*           ⢀⣤⣤⣤⣤⣀⠀⠀⠀⠀⠀⠀⠀⠀⠀    @@*       *@@     
;  @@          ⠀⠀⢸⣿⣿⣿⣿⣿⣷⡀⠀⠀⠀⠀⠀⠀⠀    @@           @@    
; @@*          ⠀⠀⠘⠉⠉⠙⣿⣿⣿⣷⠀⠀⠀⠀⠀⠀⠀   @@*           *@@   
; @@           ⠀⠀⠀⠀⠀⠀⢸⣿⣿⣿⣧⠀⠀⠀⠀⠀⠀   @@             @@   
; @@           ⠀⠀⠀⠀⠀⠀⣼⣿⣿⣿⣿⣆⠀⠀⠀⠀⠀   @@             @@   
;!@m           ⠀⠀⠀⠀⠀⣼⣿⣿⣿⣿⣿⣿⡀⠀⠀⠀⠀  !@m             !@   
; !@           ⠀⠀⠀⠀⣴⣿⣿⣿⠟⣿⣿⣿⣷⠀⠀⠀⠀   !@             !!   
; !!!          ⠀⠀⠀⣰⣿⣿⣿⡏⠀⠸⣿⣿⣿⣇⠀⠀⠀   !!!           !!!   
;  :           ⠀⠀⢠⣿⣿⣿⡟⠀⠀⠀⢻⣿⣿⣿⡆⠀⠀     :           :     
;  :::         ⠀⢠⣿⣿⣿⡿⠀⠀⠀⠀⠀⢿⣿⣿⣷⣤⡄     :::       :::      
;    :::       ⢀⣾⣿⣿⣿⠁⠀⠀⠀⠀⠀⠈⠿⣿⣿⣿⡇       :::     :        
;                                                                                         
#|                       ╔═════════════════════════════════════════════════════════════════════════╗     mm     |#
#|                       ║ |# (define name "Muhammad Aviv Burhanudin")                          #| ║      *@@   |#
#|                       ║ |# (define twitter "@aerphanas")                                     #| ║        @@  |#
#|                       ║ |# (define email "muhamadaviv14@gmail.com")                          #| ║        *@@ |#
#|                       ║ |# (define gender "Male")                                            #| ║         @@ |#
#|                       ║ |# (printf "Hi My Name is ~a, a Σ~a, if you need me you" name gender)#| ║         @@ |#
#|                       ║ |# (printf "can contact me via email : ~v" email)                    #| ║         !@ |#
#|                       ║ |# (printf "or dm me on twitter : ~v \n" twitter)                    #| ║         !! |#
#|                       ║ |# (printf "When there’s a will to fail, obstacles can be found.")   #| ║        !!! |#
#|                       ╚═════════════════════════════════════════════════════════════════════════╝        :   |#
#|                                                                                                        :::   |# 
#|                                                                                                        :     |#
```
-->

```c
#include <stdio.h>
#include <string.h>

struct
People
{
    char name[50];
    char twitter[20];
    char email[30];
    char gender[2];
};

int
main()
{
    struct People myself = {0};
    strncpy(myself.name, "Muhammad Aviv Burhanudin", sizeof(myself.name) - 1);
    strncpy(myself.email, "muhamadaviv14@gmail.com", sizeof(myself.email) - 1);
    strncpy(myself.twitter, "aerphanas", sizeof(myself.twitter) - 1);
    strncpy(myself.gender, "M", sizeof(myself.gender) - 1);

    if (strchr(myself.email, '@') == NULL || strchr(myself.email, '.') == NULL)
    {
        printf("Invalid email format!\n");
        return 1;
    }

    printf("Name: %s\n", myself.name);
    printf("Email: %s\n", myself.email);
    printf("Twitter: %s\n", myself.twitter);
    printf("Gender: %s\n", myself.gender);

    return 0;
}
```

<!--START_SECTION:waka-->
📊 **This Week I Spent My Time On** 

```text
💬 Programming Languages: 
Other                    13 hrs 27 mins      ⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   41.50 % 
Java                     10 hrs 19 mins      ⣿⣿⣿⣿⣿⣿⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   31.82 % 
Org                      3 hrs 52 mins       ⣿⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   11.97 % 
Properties               1 hr 40 mins        ⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   05.14 % 
Markdown                 1 hr 22 mins        ⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   04.25 % 

🔥 Editors: 
VS Code                  15 hrs 38 mins      ⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   48.23 % 
Bash                     13 hrs              ⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   40.11 % 
Emacs                    3 hrs 46 mins       ⣿⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   11.66 % 

🐱‍💻 Projects: 
Volcanix-Edu             12 hrs 40 mins      ⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   39.07 % 
Terminal                 6 hrs 13 mins       ⣿⣿⣿⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   19.22 % 
quarkus-reactive-db      3 hrs 32 mins       ⣿⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   10.92 % 
aerphanas.github.io      2 hrs 11 mins       ⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   06.76 % 
Unknown Project          2 hrs 9 mins        ⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   06.64 % 

💻 Operating System: 
Linux                    32 hrs 25 mins      ⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿   100.00 % 
```

**I Mostly Code in C** 

```text
C                        6 repos             ⣿⣿⣿⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   20.69 % 
Haskell                  4 repos             ⣿⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   13.79 % 
Java                     4 repos             ⣿⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   13.79 % 
C++                      3 repos             ⣿⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   10.34 % 
Racket                   2 repos             ⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   06.90 % 
```




<!--END_SECTION:waka-->

**Blog Posts**

<!--START_SECTION:feed-->
* [Foreign function Interface](https:&#x2F;&#x2F;aerphanas.github.io&#x2F;posts&#x2F;2023-02-24-Foreign_Function_Interface.html)
* [Install Software dari AUR](https:&#x2F;&#x2F;aerphanas.github.io&#x2F;posts&#x2F;2023-02-15-Install_Software_dari_AUR.html)
* [Alternatif Docker - Podman Pod](https:&#x2F;&#x2F;aerphanas.github.io&#x2F;posts&#x2F;2023-02-05-Alternatif_Docker_-_Podman_Pod.html)
* [Perkenalan Dengan Git VCS](https:&#x2F;&#x2F;aerphanas.github.io&#x2F;posts&#x2F;2023-01-29-Perkenalan-Dengan-Git-VCS.html)
* [Linux Chroot](https:&#x2F;&#x2F;aerphanas.github.io&#x2F;posts&#x2F;2023-01-22-Linux_Chroot.html)
<!--END_SECTION:feed-->

![euler](https://projecteuler.net/profile/aerphanas.png)
