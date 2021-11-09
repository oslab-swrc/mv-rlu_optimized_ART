# mv-rlu_optimized_ART

This repository provide the algorithm of ART to which MV-RLU is applied.

It is provided under the terms of Apache 2.0 License

## How to use

- Fetch the MV-RLU from github and build
```
#> git clone https://github.com/cosmoss-vt/mv-rlu.git
#> cd mv-rlu
#/mv-rlu> make ordo
#/mv-rlu> make
```
- Clone this repository and check the files for the ART: 'art.h' 'art.c'
```
#> git clone <this repo> 
```
- Put the files in your application, and including it before using it with MV-RLU
- Don't forget to define ``IS_MVRLU`` or ```rlu.h``` will be used.
```
#define IS_MVRLU
#include "art.h"
```
- You can handle ART structure through following APIs
```
art_tree_init()
art_tree_destroy()
art_size()
art_insert()
art_delete()
art_search()
art_minimum()
art_maximum()
art_iter()
art_iter_prefix()
```
