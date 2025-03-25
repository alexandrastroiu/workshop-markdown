# Helloworld Programs
![Hello World](helloworld.png)
We list below Helloworld programs for different programming languages, i.e. programs that print "Hello, World!". The specified compiler or interpreter is required for each programming languages.

The table below summarizes the programs:

| Language | Language (Spec) Site | Section |Build / RunToolchain | Debian / UbuntuPackages |
| -------- | -------------------- | ------- | --------------------| ----------------------  |
| C        | The Standard - C     | C       | GCC                 | build-essential         |
| C++      | The Standard - C++   | C++     | GCC / G++           | build-essential ,  g++  |  
| Dlang    | D Programming Language:Home | Dlang | GCC / GDC | build-essential ,  gdc       |
| Go       | The Go Programming Language | Go | Go | golang |
| Rust | Rust Programming Language | Rust | Rust (Crate) | rustlang |
| Java | Java Programming Language | Java | JDK |openjdk-17-jdk |
| x86_64 assembly | x86 and amd64 instruction reference | x86_64 |Assembly | GCC / GAS | build-essential |
| ARM64 assembly | Arm A64 Instruction Set Architecture | ARM64 Assembly | GCC / GAS(AArch64) | build-essentials |
| Bash | Bash Reference Manual | Bash | Bash | bash |
| Python | Welcome to Python.org | Python | Python | python |
| Ruby | Ruby Programming Language | Ruby | Ruby | ruby |
| PHP | PHP: Hypertext Preprocessor | PHP | PHP | php |
| Perl | The Perl Programming Language | Perl | Perl | perl |
| Lua The Programming Language | Lua | Lua | Lua | lua |

## C
```
#include <stdio.h>

int main(void)
{        puts("Hello, World!");
         return 0;
}
```
Build with: 
```
gcc -Wall -o helloworld helloworld.c
```
Run with:
```
./helloworld
```
## C++
```
#include <iostream>

int main()
{        std::cout << "Hello, World!" << std::endl;
         return 0;
}
```
Build with:
```
g++ -Wall -o helloworld helloworld.cpp
```
Run with:
```
./helloworld
```

Dlang
import std.stdio;void main(){    writeln("Hello, World!");}
gdc -Wall -o helloworld helloworld.cpp
./helloworld
10/26/24, 10:32 AM workshop-markdown/helloworld.md at solution · rosedu/workshop-markdown
https://github.com/rosedu/workshop-markdown/blob/solution/helloworld.md 4/9
Build and run with:Build with:Run with:
Go
package mainimport "fmt"func main() {    fmt.Println("Hello, World!")}
go run helloworld.go
Rust
fn main() {    println!("Hello, World");}
rustc hello.rs
./helloworld
10/26/24, 10:32 AM workshop-markdown/helloworld.md at solution · rosedu/workshop-markdown
https://github.com/rosedu/workshop-markdown/blob/solution/helloworld.md 5/9
Build with:Run with:Build with:Run with:
Java
public class HelloWorld {    public static void main(String[] args) {        System.out.println("Hello, World!");    }}
javac HelloWorld.java
java HelloWorld
x86_64 Assembly
TODO
10/26/24, 10:32 AM workshop-markdown/helloworld.md at solution · rosedu/workshop-markdown
https://github.com/rosedu/workshop-markdown/blob/solution/helloworld.md 6/9
TODOBuild with:Run with:Run with:
./helloworld
ARM64 Assembly
TODO
./helloworld
Bash
echo "Hello, World!"
bash helloworld.sh
10/26/24, 10:32 AM workshop-markdown/helloworld.md at solution · rosedu/workshop-markdown
https://github.com/rosedu/workshop-markdown/blob/solution/helloworld.md 7/9
Run with:Run with:Run with:
Python
print("Hello, World!")
python helloworld.py
Ruby
puts "Hello, World!"
ruby helloworld.rb
PHP
<?phpecho "Hello, World!"?>
./helloworld
10/26/24, 10:32 AM workshop-markdown/helloworld.md at solution · rosedu/workshop-markdown
https://github.com/rosedu/workshop-markdown/blob/solution/helloworld.md 8/9
Run with:Run with:
Perl
print("Hello, World!\n")
perl helloworld.pl
Lua
print("Hello, World!")
lua helloworld.lua
10/26/24, 10:32 AM workshop-markdown/helloworld.md at solution · rosedu/workshop-markdown

