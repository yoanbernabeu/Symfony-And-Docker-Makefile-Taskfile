# Symfony And Docker Makefile (+Taskfile)

A Makefile (and Taskfile) to improve the DX of your Symfony projects!

You will find a collection of everyday useful commands in a Symfony project.

Feel free to modify it for your projects.


## Requirements

*This file was created to be used in a Linux environment, some commands should be adapted to your operating system.*

### Makefile Version

* You must have `make` on your computer.

* You can check if `make` is available with the command:

```bash
make -v
```

### Taskfile Version

* You must have `task` on your computer.

* You can check if `task` is available with the command:

```bash
task --version
```

## Installation

### Makefile Version

You just need to add the file `Makefile` to the root of your Symfony project

```bash
wget https://raw.githubusercontent.com/yoanbernabeu/Symfony-And-Docker-Makefile/main/Makefile
```

### Taskfile Version

You just need to add the file `Taskfile.yaml` to the root of your Symfony project

```bash
wget https://raw.githubusercontent.com/yoanbernabeu/Symfony-And-Docker-Makefile/main/Taskfile.yaml
```

## Usage/Examples

### Makefile Version

To get help from the file, just run the command:

```bash
make help
```

Then choose your "target" and have fun with it:

```bash
make [target]
```

### Taskfile Version

To get help from the file, just run the command:

```bash
task help
```

Then choose your "target" and have fun with it:

```bash
task [target]
```

## License

[MIT](LICENSE)