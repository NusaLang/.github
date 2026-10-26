<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1f2937,100:dc2626&height=190&section=header&text=Nusa%20Lang&fontColor=ffffff&fontSize=56&fontAlignY=38&desc=Bahasa%20pemrograman%20berkeyword%20Bahasa%20Indonesia&descSize=17&descAlignY=62&animation=fadeIn" width="100%" alt="Nusa Lang" />

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=19&duration=3200&pause=900&color=DC2626&center=true&vCenter=true&width=560&lines=jika+n+%3C+2+%7B+hasil+n%3B+%7D;Native+C%2B%2B17%2C+satu+binary;Goroutine%2C+channel%2C+dan+GC+sendiri" alt="Nusantara" />

</div>

<br/>

Kami membuat **Nusantara** (`.ns`): bahasa pemrograman yang keyword-nya Bahasa Indonesia tapi tidak terasa seperti mainan. Dikompilasi native, punya garbage collector, goroutine, dan package manager berbasis git.

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

| Repo | Isinya |
| --- | --- |
| [**NSL**](https://github.com/NusaLang/NSL) | Bahasanya: compiler, bytecode VM dengan JIT, GC, dan CLI `nusa` |
| [Kripto](https://github.com/NusaLang/Kripto) | Modul kripto |
| [axios](https://github.com/NusaLang/axios) | Pustaka HTTP client |

Paket cuma repo git biasa, ambil dengan `nusa get github.com/user/repo`.

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:dc2626,100:1f2937&height=80&section=footer" width="100%" alt="" />

</div>
