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

###Flag
* -t [Text to process]
* -s [Number of seconds to wait for server to respond]

# Warning

Liner2Catcher is using simple sleep function inside, without -s flag it's waiting 5 seconds for server to respond, if it's not enough we can use -s flag to specify waiting time by ourself

# Flag usage

bash LinerCatcher.sh -t [text_to_process] -s [number_of_seconds_to wait] > [name_of_the_file].txt

# Liner2Catcher
Simple shell script to process text from Polish NLP library to CCL file

# Requirements
In Terminal type:
xargs brew install < INSTALL.txt
OR
brew install jq

# Usage

In terminal run: 
bash LinerCatcher.sh -t [text_to_process] > [name_of_the_file].txt

# Warning

Liner2Catcher is using simple sleep function inside, without -s flag it's waiting 5 seconds for server to respond, if it's not enough we can use -s flag to specify waiting time by ourself

# Flag usage

bash LinerCatcher.sh -t [text_to_process] -s [number_of_seconds_to wait] > [name_of_the_file].txt
