# TeX Live

```
> tlmgr update --list
```

Check the repository list.
```
> tlmgr repository list
List of repositories (with tags if set):
        https://mirror.ctan.org/systems/texlive/tlnet (main)
```

Add the Naver CTAN mirror site to the repository list, whereas `naver` is tag name.
```
> tlmgr repository add https://mirror.navercorp.com/CTAN/systems/texlive/tlnet/ naver
> tlmgr repository list
List of repositories (with tags if set):
        https://mirror.ctan.org/systems/texlive/tlnet (main)
        https://mirror.navercorp.com/CTAN/systems/texlive/tlnet (naver)
```

Update `tlmgr` itself.
```
> tlmgr update --self
```

List the packages that would be updated.
```
> tlmgr update --list
```

tlmgr update --all
