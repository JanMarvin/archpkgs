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

The sources for the packages are

* [rstudio-desktop-git](https://github.com/JanMarvin/rstudio-archlinuxpkg/tree/main/rstudio)
* [soci](https://github.com/JanMarvin/rstudio-archlinuxpkg/tree/main/soci)
* [pandoc-deb](https://github.com/JanMarvin/rstudio-archlinuxpkg/tree/main/pandoc)
* [v8-r](https://github.com/JanMarvin/v8-R)

