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
Java                     16 hrs 1 min        ⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   42.71 % 
Other                    10 hrs 33 mins      ⣿⣿⣿⣿⣿⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   28.14 % 
Org                      3 hrs 57 mins       ⣿⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   10.54 % 
Nim                      3 hrs 8 mins        ⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   08.36 % 
Properties               1 hr 29 mins        ⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   03.97 % 

🔥 Editors: 
VS Code                  23 hrs 18 mins      ⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀   62.13 % 
Bash                     10 hrs 22 mins      ⣿⣿⣿⣿⣿⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   27.64 % 
Emacs                    3 hrs 50 mins       ⣿⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   10.23 % 

🐱‍💻 Projects: 
Volcanix-Edu             15 hrs 45 mins      ⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   42.01 % 
Terminal                 4 hrs 44 mins       ⣿⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   12.63 % 
nim-basics               4 hrs 10 mins       ⣿⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   11.12 % 
quarkus-reactive-db      3 hrs 32 mins       ⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   09.44 % 
Unknown Project          2 hrs 9 mins        ⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   05.74 % 

💻 Operating System: 
Linux                    37 hrs 31 mins      ⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿   100.00 % 
```

**I Mostly Code in C** 

```text
C                        6 repos             ⣿⣿⣿⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   19.35 % 
Haskell                  4 repos             ⣿⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   12.90 % 
C++                      3 repos             ⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   09.68 % 
Nim                      1 repo              ⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   03.23 % 
D                        1 repo              ⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   03.23 % 
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
