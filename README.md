# multiline-search

multiline-search is the library and command line utility to that helps you to find count of occurences of multiline templates in files

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes or for using as a command line utility.

### Installing

```
go get github.com/lonja/multiline-search
```

After installing, we can invoke the sqlboiler command line utility.
```
usage: multiline-search <command> [<args>] 
        count    Count all occurences of template in file

Usage of count:
  count -tmpl <template_file> -file <file_to_process>
Flags:
  -file string
        File to find and count templates (default "./landscape.txt")
  -tmpl string
        Template file search templates in (default "./tmpl.txt")

```