# Symfony And Docker Makefile + Taskfile

A Makefile and Taskfile to improve the DX of your Symfony projects!

You will find a collection of everyday useful commands in a Symfony project.

Feel free to modify it for your projects.

##  1. <a name='TableofContents'></a>Table of Contents

<!-- vscode-markdown-toc -->
* 1. [Table of Contents](#TableofContents)
* 2. [Makefile](#Makefile)
	* 2.1. [Requirements](#Requirements)
	* 2.2. [Installation](#Installation)
	* 2.3. [Usage/Examples](#UsageExamples)
* 3. [Taskfile](#Taskfile)
	* 3.1. [Requirements](#Requirements-1)
	* 3.2. [Installation](#Installation-1)
	* 3.3. [Usage/Examples](#UsageExamples-1)
* 4. [License](#License)

<!-- vscode-markdown-toc-config
	numbering=true
	autoSave=true
	/vscode-markdown-toc-config -->
<!-- /vscode-markdown-toc -->

##  2. <a name='Makefile'></a>Makefile

###  2.1. <a name='Requirements'></a>Requirements

*This file was created to be used in a Linux environment, some commands should be adapted to your operating system.*


* You must have `make` on your computer.

* You can check if `make` is available with the command:

```bash
make -v
```

###  2.2. <a name='Installation'></a>Installation

You just need to add the file `Makefile` to the root of your Symfony project

```bash
wget https://raw.githubusercontent.com/yoanbernabeu/Symfony-And-Docker-Makefile/main/Makefile
```

###  2.3. <a name='UsageExamples'></a>Usage/Examples

To get help from the file, just run the command:

```bash
make help
```

Then choose your "target" and have fun with it:

```bash
make [target]
```

##  3. <a name='Taskfile'></a>Taskfile

###  3.1. <a name='Requirements-1'></a>Requirements

*This file was created to be used in a Linux environment, some commands should be adapted to your operating system.*

* You must have `task` on your computer.

* You can check if `task` is available with the command:

```bash
task --version
```

###  3.2. <a name='Installation-1'></a>Installation

You just need to add the file `Taskfile.yaml` to the root of your Symfony project

```bash
wget https://raw.githubusercontent.com/yoanbernabeu/Symfony-And-Docker-Makefile/main/Taskfile.yaml
```

###  3.3. <a name='UsageExamples-1'></a>Usage/Examples

To get help from the file, just run the command:

```bash
task help
```

Then choose your "target" and have fun with it:

```bash
task [target]
```

##  4. <a name='License'></a>License

[MIT](LICENSE)