# halostatue/fish-nix

A quick plugin for [fish shell] to ensure that [nix] is properly hooked
into fish configuration.

If [replay], bax (an older version of replay), or [bass] are installed, the
profile will be configured from `$HOME/.nix-profile/etc/profile/nix.sh` using
those functions, otherwise it will be configured with a translated version of
`nix.sh`.

## Installation

Install with [Fisher] (recommended):

```fish
# Fisher 4.0+
fisher install halostatue/fish-nix@1.x
```

<details>
<summary>Not using a package manager?</summary>

---

Copy `conf.d/*.fish` to your fish configuration directory preserving the
directory structure.
</details>

### System Requirements

- [fish] 3.0+
- [direnv]

## License

[MIT](LICENCE.md)

[fish shell]: https://fishshell.com "friendly interactive shell"
[nix]: https://nixos.org
[Fisher]: https://github.com/jorgebucaran/fisher
[fish]: https://github.com/fish-shell/fish-shell
[bass]: https://github.com/edc/bass
[replay]: https://github.com/jorgebucaran/replay.fish
