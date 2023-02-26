*version: 0.0.1*

An implementation of the halo system for actuarial in SATySFi.

保険数理における halo system (添字記法)の SATySFi 実装です.

# Installation

```sh
opam install satysfi-actuarial
satyrographos install
```

```tex
@require: actuarial/actuarial
```

# Usage

```tex
+math(${
    A \ac-ind-n![ itop ${x}; ibot ${y}; [${z}] ] {n}
});
```

For more details, see [doc/manual.pdf](doc/manual.pdf).

詳細については [doc/manual.pdf](doc/manual.pdf) を参照してください.

# TODO

- [ ] Enhance commands / コマンドの充実
- [ ] Adopt macro notation / マクロ記法の導入

# License

**MIT**
