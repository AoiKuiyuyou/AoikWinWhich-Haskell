[:var_set('', """
#/ Compile command
aoikdyndocdsl -s README.src.md -n aoikdyndocdsl.ext.all::nto -g README.md
""")]\
[:var_set('source_file_name', 'aoikwinwhich.hs')]\
[:var_set('source_file_url', '/src/aoikwinwhich/aoikwinwhich.hs')]\
[:var_set('program_file_url', 'src/aoikwinwhich/aoikwinwhich.exe')]\
[:HDLR('heading', 'heading')]\
# AoikWinWhich
[AoikWinWhich](https://github.com/AoiKuiyuyou/AoikWinWhich) written in Haskell.

Tested working with:
- Haskell Platform 2014.2.0.0
- Windows 8.1
- Windows earlier versions should work but not tested

## Table of Contents
[:toc(beg='next', indent=-1)]

## Setup
Clone this git repository to local:
```
git clone https://github.com/AoiKuiyuyou/AoiWinWhich-Haskell
```

In the local repository directory, the source file is
[[:var('source_file_name')]]([:var('source_file_url')]).

Use program **runhaskell** to run without compiling:
```
runhaskell src/aoikwinwhich/aoikwinwhich.hs
```

Use program **ghc** to compile:
```
ghc src/aoikwinwhich/aoikwinwhich.hs
```
- The generated program file is **[:var('program_file_url')]**.

## Usage
See [usage](https://github.com/AoiKuiyuyou/AoikWinWhich#how-to-use) in the
general project [AoikWinWhich](https://github.com/AoiKuiyuyou/AoikWinWhich).
