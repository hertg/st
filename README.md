# st
My custom build of [st](https://st.suckless.org/).

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
git merge upstream master
```
