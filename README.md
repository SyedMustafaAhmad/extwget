# Entended WGET (extwget)
A simple shell script to extend the functionality of wget.
This functionality is mainly for longer downloads and/or a list of downloads.

## Dependencies
- wget
- curl (optional)

## How to use
1) Use git to clone repository as follows:
```console
git clone https://github.com/SyedMustafaAhmad/extwget
```
Or download zip of the repository.

2) Change directory
```console
cd extwget
```

3) Make shell script executable
```console
chmod +x extwget.sh
```

4) Run shell script just like wget
For example,
```console
./extwget url
```
Or,
```console
./extwget url-1 url-2 url-3
```
Or,
```console
./extwget url-list.txt
```
Where urllist.txt is the file that has links one after the other with line breaks.
For example,
```console
url-1
url-2
url-3
```
