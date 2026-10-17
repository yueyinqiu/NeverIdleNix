# NeverIdle-Nix

Nix packaging for [NeverIdle](https://github.com/layou233/NeverIdle) — periodically waste CPU, memory and network resources to keep servers alive.

## Adding as a flake input

```nix
{
  inputs = {
    neveridle.url = "github:yueyinqiu/NeverIdleNix";
  };
}
```

## Package

The binary is exposed as `NeverIdle`:

```nix
neveridle.packages.${system}.neveridle
```

Or try it directly from the CLI:

```console
$ nix shell github:yueyinqiu/NeverIdleNix
```

---

All documentation and `description` fields in this repository are AI-generated.
