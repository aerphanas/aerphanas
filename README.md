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
Java                     14 hrs 7 mins       ⣿⣿⣿⣿⣿⣿⣿⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   36.66 % 
Other                    12 hrs 44 mins      ⣿⣿⣿⣿⣿⣿⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   33.07 % 
Nim                      7 hrs 15 mins       ⣿⣿⣿⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   18.87 % 
Properties               1 hr 24 mins        ⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   03.66 % 
D                        1 hr 3 mins         ⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   02.75 % 

🔥 Editors: 
VS Code                  25 hrs 26 mins      ⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀   66.06 % 
Bash                     12 hrs 38 mins      ⣿⣿⣿⣿⣿⣿⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   32.84 % 
Emacs                    25 mins             ⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   01.09 % 

🐱‍💻 Projects: 
Volcanix-Edu             14 hrs 16 mins      ⣿⣿⣿⣿⣿⣿⣿⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   37.05 % 
nim-basics               7 hrs 38 mins       ⣿⣿⣿⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   19.84 % 
Terminal                 4 hrs 21 mins       ⣿⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   11.33 % 
Advent-of-Code           3 hrs 32 mins       ⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   09.21 % 
quarkus-reactive-db      3 hrs 32 mins       ⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   09.20 % 

💻 Operating System: 
Linux                    38 hrs 30 mins      ⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿   100.00 % 
```

**I Mostly Code in C** 

```text
C                        6 repos             ⣿⣿⣿⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   18.75 % 
Haskell                  4 repos             ⣿⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   12.50 % 
C++                      3 repos             ⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   09.38 % 
Nim                      2 repos             ⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   06.25 % 
D                        1 repo              ⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   03.12 % 
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

**List of programming languages that I currently enjoy**

* C (Low Level and Fastest Language)
* D (C++ Redesign that i like)
* Haskell (Pure Function, Cool Monad)
* Nim (Good syntax, System Programming, GC King)
* Java (Enterprise $)
* Racket (Good Documentation, Language-Oriented Programming Language)
* Elm (No Runtime Error)

![euler](https://projecteuler.net/profile/aerphanas.png)
