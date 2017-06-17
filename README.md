<h1 align="center">pak</h1>
<h4 align="center">Command line tool for everything</h4>
<p align="center"> 
<img src="https://github.com/tburnam/pak/blob/master/usage.gif">
</p>
<br>

## Purpose
pak is a way of organizing paks, or executable scripts. Using pak, you can create, modify, and share scripts that perform various tasks. paks can trigger complex build scripts, and work is being done to provide an API to various languages to supercharge building paks. I have been developing pak for several months and have used it extensively in personal projects - it's very helpful for complex projects.

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
