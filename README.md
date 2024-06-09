<h1 align="center">pak</h1>
<h4 align="center">Command line tool for managing custom scripts</h4>
<p align="center"> 
<img src="https://github.com/tburnam/pak/blob/master/usage.gif">
</p>
<br>

## Purpose
pak is meant to make scripting easier. currently, it supports quick bash script creation with Atom, but the idea is to make scripting easier. paks today are great for build scripts, it's a snappy commmandline tool to glue together a simple workflow. future development will be towards a core API with various language wrappers (starting with js). the end goal is a highly-intuitive UX towards building powerful, complex, and shareable automation

## Install instructions
```bash
cd [path/to/pak/]
sudo ./pakBuild
```

## Usage
```
pak               | lists your paks
pak -b <pak name> | builds a new pak and puts it in your path
pak -r <pak name> | removes a pak
pak -o <pak name> | opens an existing pak in vim
pak -l            | lists your paks
pak -h            | pak help page
```

## PRs welcome!
