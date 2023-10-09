# bfasm.py

Naive [Brainfuck](https://en.wikipedia.org/wiki/Brainfuck) to Linux x86 ASM
compiler. Requires [nasm](https://www.nasm.us/).

Try it out:

```sh
$ python bfasm.py ./examples/hello.bf hello
$ ./hello
Hello, world!
```

```sh
$ python bfasm.py ./examples/rot13.bf rot13
$ ./hello | ./rot13
Uryyb Jbeyq!
$ ./hello | ./rot13 | ./rot13
Hello, world!
```
