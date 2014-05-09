# grunt-init-csharpsolution

> Quickly scaffold a C# 4.5 solution with [grunt-init][], including NUnit unit tests. Adapt to suit your own needs.

![screenshot](https://raw.githubusercontent.com/nosami/nosami.github.io/master/grunt-init-csharpsolution.gif)

[grunt-init]: http://gruntjs.com/project-scaffolding

## Installation
If you haven't already done so, install node and [grunt-init][].

Once grunt-init is installed, place this template in your `~/.grunt-init/` directory. It's recommended that you use git to clone this template into that directory, as follows:

```
git clone https://github.com/nosami/grunt-init-csharpsolution.git ~/.grunt-init/csharpsolution
```

_(Windows users, see [the documentation][grunt-init] for the correct destination directory path)_

This 
## Usage

At the command-line, cd into an empty directory, run this command and follow the prompts.

```
grunt-init csharpsolution
```

Install nuget packages.

```
nuget restore
```

_Note that this template will generate files in the current directory, so be sure to change to a new directory first if you don't want to overwrite existing files._
