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
-->

```nim
type People = object
  name: string
  email: string
  twitter: string
  gender: char

var aerphanas: People = People()
aerphanas.name = "Muhammad Aviv Burhanudin"
aerphanas.email = "muhamadaviv14@gmail.com"
aerphanas.twitter = "aerphanas"
aerphanas.gender = 'M'

echo aerphanas
```

<!--START_SECTION:waka-->
📊 **This Week I Spent My Time On** 

```text
💬 Programming Languages: 
Rust                     17 hrs 55 mins      ⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   45.35 % 
Java                     8 hrs 57 mins       ⣿⣿⣿⣿⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   22.67 % 
Other                    7 hrs 56 mins       ⣿⣿⣿⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   20.11 % 
Markdown                 1 hr 27 mins        ⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   03.67 % 
Nim                      1 hr 11 mins        ⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   03.02 % 

🔥 Editors: 
VS Code                  32 hrs 31 mins      ⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣀⣀⣀⣀   82.27 % 
Bash                     5 hrs 58 mins       ⣿⣿⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   15.12 % 
Chrome                   52 mins             ⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   02.21 % 
Emacs                    9 mins              ⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   00.39 % 

🐱‍💻 Projects: 
bassicrust               13 hrs 13 mins      ⣿⣿⣿⣿⣿⣿⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   33.45 % 
Volcanix-Edu             11 hrs 48 mins      ⣿⣿⣿⣿⣿⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   29.89 % 
minigrep                 3 hrs 3 mins        ⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   07.75 % 
Terminal                 2 hrs 36 mins       ⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   06.58 % 
aerphanas.github.io      2 hrs 2 mins        ⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   05.18 % 

💻 Operating System: 
Linux                    39 hrs 31 mins      ⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿   100.00 % 
```

**I Mostly Code in Haskell** 

```text
Haskell                  7 repos             ⣿⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   12.73 % 
Rust                     3 repos             ⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   05.45 % 
Nim                      3 repos             ⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   05.45 % 
C++                      3 repos             ⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   05.45 % 
D                        1 repo              ⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   01.82 % 
```




<!--END_SECTION:waka-->

**Blog Posts**

<!--START_SECTION:feed-->
* [Apa itu Monad](https:&#x2F;&#x2F;aerphanas.github.io&#x2F;posts&#x2F;2023-03-12-Apa_Itu_Monad.html)
* [Foreign function Interface](https:&#x2F;&#x2F;aerphanas.github.io&#x2F;posts&#x2F;2023-02-24-Foreign_Function_Interface.html)
* [Install Software dari AUR](https:&#x2F;&#x2F;aerphanas.github.io&#x2F;posts&#x2F;2023-02-15-Install_Software_dari_AUR.html)
* [Alternatif Docker - Podman Pod](https:&#x2F;&#x2F;aerphanas.github.io&#x2F;posts&#x2F;2023-02-05-Alternatif_Docker_-_Podman_Pod.html)
* [Perkenalan Dengan Git VCS](https:&#x2F;&#x2F;aerphanas.github.io&#x2F;posts&#x2F;2023-01-29-Perkenalan-Dengan-Git-VCS.html)
<!--END_SECTION:feed-->

**List of programming languages that I currently enjoy**

* C (Low Level and Fastest Language)
* D (C++ Redesign that i like)
* Haskell (Pure Function, Cool Monad)
* Nim (Good syntax, System Programming, GC King)
* Java (Enterprise $)
* Racket (Good Documentation, Language-Oriented Programming Language)
* Rust (Fast & Safe)
* Elm (No Runtime Error)

![euler](https://projecteuler.net/profile/aerphanas.png)
