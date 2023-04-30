# Minigrep

Minigrep rust project, a project similar to grep that does a basic search of a word in a file, and output the the line that contains the query.

use the following command to search in a text in a file
``` 
$ cargo run -- <text> <file_name> 
``` 


set the following environment variable to make the text ignore the case.
```
$ IGNORE_CASE=1 cargo run -- to poem.txt
```

this repo contains `poem.txt` and `output.txt` a file which contains sample text and  output of the follwoing command respectively:

```
$ cargo run -- to poem.txt > output.txt
```

