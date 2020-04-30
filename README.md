# bob
### An easy to use command line tool to create and manage projects
#### What is Bob
well bob is a command line tool that can be used to create and manage projects, it uses yaml for storing data, which is well known for its human readabiity,<br>currently bob possesses two commands 
- build
  creates a project repository and initializes it with an attributes.yaml and src directory **requires an argument**
- list
  lists all projects created with this tool, it also has an optional argument to list the attributes.yaml of the file
#### How to install
simple execute `install.sh` with line
```bash
sh install.sh
```
if this does not work then type
```bash
alias bob="~/.bob/bob"
```
