# Начните сначала

...

## Инсталляция

...

### Зависимости

...

#### Тулчейн

  - Clang (v.15 или позже)
  - CMake (v.3.13.4 или позже)
  - Ninja (v.1.12.1 или позже)

...

#### Библиотеки

  - LLVM (v.15 или позже)
  - [Immer](https://github.com/arximboldi/immer) (v.0.8.1 или позже)

...

### Linux

Ubuntu ...

```console
# apt install git cmake ninja-build
# apt install clang libimmer-dev
```


### Windows

MSYS2/MINGW64 ...

```console
$ pacman -S mingw-w64-x86_64-git
$ pacman -S mingw-w64-x86_64-cmake
$ pacman -S mingw-w64-x86_64-clang
$ pacman -S mingw-w64-x86_64-llvm
$ pacman -S mingw-w64-x86_64-immer
```


### Компиляция

...

```console
$ git clone {{voidc_repo}}.git
$ cd voidc
$ ./mk_config
$ ./mk_build
$ time build/voidc compiler/test/try_fruits.void -T
```



...


## Использование


...




