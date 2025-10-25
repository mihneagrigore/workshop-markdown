### Helloworld Programs

---

![Hello World Iamge](./helloworld.png)

We list below Helloworld programs for different programming languages, i.e. programs that print "Hello, World!". Thespecified compiler or interpreter is required for each programming languages.

The table below summarizes the programs:

<!--- Insert html table -->
<table>
  <thead>
    <tr>
      <th>Language</th>
      <th>Language (Spec) Site</th>
      <th>Section</th>
      <th>Build / Run Toolchain</th>
      <th>Debian / Ubuntu Packages</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>C</td>
      <td><a href="#">The Standard - C</a></td>
      <td>C</td>
      <td>GCC</td>
      <td><code>build-essential</code></td>
    </tr>
    <tr>
      <td>C++</td>
      <td><a href="#">The Standard - C++</a></td>
      <td>C++</td>
      <td>GCC / G++</td>
      <td><code>build-essential, g++</code></td>
    </tr>
    <tr>
      <td>Dlang</td>
      <td><a href="#">D Programming Language Home</a></td>
      <td>Dlang</td>
      <td>GCC / GDC</td>
      <td><code>build-essential, gdc</code></td>
    </tr>
    <tr>
      <td>Go</td>
      <td><a href="#">The Go Programming Language</a></td>
      <td>Go</td>
      <td>Go</td>
      <td><code>golang</code></td>
    </tr>
    <tr>
      <td>Rust</td>
      <td><a href="#">Rust Programming Language</a></td>
      <td>Rust</td>
      <td>Rust (Crate)</td>
      <td><code>rustlang</code></td>
    </tr>
    <tr>
      <td>Java</td>
      <td><a href="#">Java Programming Language</a></td>
      <td>Java</td>
      <td>JDK</td>
      <td><code>openjdk-17-jdk</code></td>
    </tr>
    <tr>
      <td>x86_64 assembly</td>
      <td><a href="#">x86 and amd64 instruction reference</a></td>
      <td>x86_64 Assembly</td>
      <td>GCC / GAS</td>
      <td><code>build-essential</code></td>
    </tr>
    <tr>
      <td>ARM64 assembly</td>
      <td><a href="#">Arm A64 Instruction Set Architecture</a></td>
      <td>ARM64 Assembly</td>
      <td>GCC / GAS (AArch64)</td>
      <td><code>build-essential</code></td>
    </tr>
    <tr>
      <td>Bash</td>
      <td><a href="#">Bash Reference Manual</a></td>
      <td>Bash</td>
      <td>Bash</td>
      <td><code>bash</code></td>
    </tr>
    <tr>
      <td>Python</td>
      <td><a href="#">Welcome to Python.org</a></td>
      <td>Python</td>
      <td>Python</td>
      <td><code>python</code></td>
    </tr>
    <tr>
      <td>Ruby</td>
      <td><a href="#">Ruby Programming Language</a></td>
      <td>Ruby</td>
      <td>Ruby</td>
      <td><code>ruby</code></td>
    </tr>
    <tr>
      <td>PHP</td>
      <td><a href="#">PHP: Hypertext Preprocessor</a></td>
      <td>PHP</td>
      <td>PHP</td>
      <td><code>php</code></td>
    </tr>
    <tr>
      <td>Perl</td>
      <td><a href="#">The Perl Programming Language</a></td>
      <td>Perl</td>
      <td>Perl</td>
      <td><code>perl</code></td>
    </tr>
    <tr>
      <td>Lua</td>
      <td><a href="#">The Programming Language Lua</a></td>
      <td>Lua</td>
      <td>Lua</td>
      <td><code>lua</code></td>
    </tr>
  </tbody>
</table>

<br>

### C
```C
#include <stdio.h>
int main(void)
{
    puts("Hello, World!");
    return 0;
}

Build with:
    gcc -Wall -o helloworld helloworld.c
Run with:
    ./helloworld
```

### C++
```C++

#include <iostream>
int main()
{
    std::cout << "Hello, World!" << std::endl;
    return 0;
}

Build with:
    g++ -Wall -o helloworld helloworld.cpp
Run with:
    ./helloworld
```

### Dlang

```d

import std.stdio;
void main()
{
    writeln("Hello, World!");
}


Build with:
    gdc -Wall -o helloworld helloworld.cpp
Run with:
    ./helloworld
```

### Rust

```Rust

fn main() {
    println!("Hello, World");
}

Build with:
    rustc hello.rs
Run with:
    ./helloworld
```

### Java

```Java

public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}

Build with:
    javac HelloWorld.java
Run with:
    java HelloWorld
```

### ARM64 Assembly

```

Build with:
    TODO
Run with:
    ./helloworld
```

### Bash

```bash

echo "Hello, World!"

Run with:
    bash helloworld.sh
```

### Python

```python

print("Hello, World!")

Run with:
    python helloworld.py
```

### Ruby

```ruby

puts "Hello, World!"

Run with:
    ruby helloworld.rb
```

### PHP

```php
<?php
echo "Hello, World!"
?>

Run with:
    ./helloworld
```

### Perl

```perl

print("Hello, World!\n")

Run with:
    perl helloworld.pl
```


### Lua

```lua

print("Hello, World!")

Run with:
    lua helloworld.lua
```