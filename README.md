# Liner2Catcher
Simple shell script to process text from Polish NLP library to CCL file

## Installation

```bash
xargs brew install < INSTALL.txt
```
OR
```bash
brew install jq
```
## Usage/Examples
```sh
bash Liner2Catcher.sh -t ala ma kota > name_of_the_file.txt
```
```sh
bash Liner2Catcher.sh -t ala ma kota -s 10 > name_of_the_file.txt
```

### Flag
* -t [Text to process]
* -s [Number of seconds to wait for server to respond]

# Warning

Liner2Catcher is using simple sleep function inside, without -s flag it's waiting 5 seconds for server to respond, if it's not enough we can use -s flag to specify waiting time by ourself
