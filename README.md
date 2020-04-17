# st
My custom build of [st](https://st.suckless.org/).

# Patches
- [xresources](https://st.suckless.org/patches/xresources/)

# Build
```sh
make clean install
```

# Sync with upstream
```sh
git remote add upstream https://git.suckless.org/st
git fetch upstream
git checkout master
git merge upstream master
```
