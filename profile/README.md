<p align="center">
  <img src="https://raw.githubusercontent.com/NusaLang/.github/main/profile/hero.svg" width="720" alt="nsl Nusantara" />
</p>

Nusantara (`.ns`) adalah bahasa pemrograman yang keyword-nya Bahasa Indonesia. Dikompilasi native dengan C++17, punya garbage collector, goroutine, dan package manager berbasis git.

```
fungsi fib(n) {
    jika n < 2 { hasil n; }
    hasil fib(n - 1) + fib(n - 2);
}

untuk (buat i = 0; i < 10; i = i + 1) {
    cetak(fib(i));
}
```

## Mulai

```bash
git clone https://github.com/NusaLang/NSL
cd NSL && ./install.sh
nusa run examples/hello.ns
```

## Repo

- [NSL](https://github.com/NusaLang/NSL): bahasanya, berisi compiler, bytecode VM dengan JIT, GC, dan CLI `nusa`
- [Kripto](https://github.com/NusaLang/Kripto): modul kripto
- [axios](https://github.com/NusaLang/axios): pustaka HTTP client
