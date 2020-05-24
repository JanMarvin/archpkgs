add to '/etc/pacman.conf' and hope no one came up with a better name

```{R}
[archpkgs]
SigLevel = Optional TrustedOnly
Server = https://janmarvin.github.io/archpkgs/$arch
```

Note to self:
```{sh}
cd x86_64
cp what/ever/pkg .
repo-add archpkgs.db.tar.xz *.pkg.tar.xz
```

