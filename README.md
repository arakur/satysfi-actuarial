*version: 0.0.1*

保険数理における halo system (添字記法)の SATySFi 実装です.
仕様は安定していないため, 今後大きく変更される可能性があります.

# インストール

```sh
opam install satysfi-actuarial
satyrographos install
```

```tex
@require: actuarial/actuarial
```

# 使い方

```tex
+math(${
    A \ac-ind-n![ itop ${x}; ibot ${y}; [${z}] ] {n}
});
```

詳細については [doc/manual.pdf](doc/manual.pdf) を参照してください.

# TODO

- [ ] コマンドの充実
- [ ] マクロ記法の導入

# ライセンス

**MIT**
