# wallhaven-cli

Browse [wallhaven](https://wallhaven.cc/) using `nsxiv`



## Usage
```
waldl "query"
```
- Select wallpapers by marking them using `m` in `sxiv`.
- Quit `nsxiv` using `q`.

Selected images would be downloaded. The default download directory is

	~/.local/share/wallhaven

Defaults can be changed by changing the user variables, in the start of the
script.


## Dependencies

* nsxiv
* curl
