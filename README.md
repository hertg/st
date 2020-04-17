# st
My custom build of [st](https://st.suckless.org/).

## Patches
The following patches have been applied.

| Patch | diff |
| --- | --- |
| [xresources](https://st.suckless.org/patches/xresources/) | [st-xresources-20190105-3be4cf1.diff](https://st.suckless.org/patches/xresources/st-xresources-20190105-3be4cf1.diff) |

## Install
```sh
make clean install
```

## Uninstall
```sh
make clean uninstall
```

## Sync with upstream
```sh
git remote add upstream https://git.suckless.org/st
git fetch upstream
git checkout master
git merge upstream/master master
```
