# This TodoList is a simple example of a TodoList application built with the aflat programming language.

# Installing aflat
Aflat can be installed by running the following command in your terminal:
```bash
$ curl -s https://raw.githubusercontent.com/DeForestt/aflat/master/install.sh | bash
```
As of now, aflat is only available on Linux, and is most stable on Ubuntu. It will also run on WSL2 Ubuntu.
Once installed, you can run the following command for the latest version of aflat:
```bash
aflat update
```
# The aflat VSCode extension
The aflat VSCode extension is in development and can be cloned and built from [aflat-extension](https://github.com/DeForestt/aflat-extention).
I very strongly recommend using the extension, as it provides syntax highlighting and some auto-completion.

# Running The TodoList
After installing aflat, and cloning this repository, you can run the TodoList by running the following command in the root directory of this repository:
```bash
aflat run
```
This will build and run the TodoList application.
If you want to only build the application, you can run the following command:
```bash
aflat build
```

For more information on aflat, please visit [aflat](https://github.com/DeForestt/aflat). As well as the official website [aflat-lang](https://aflat-lang.com) where you can find interactive examples of aflat code.