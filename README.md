# runphp
 It is a tool that can easily test the operation of php with docker

# required
https://docs.docker.com/docker-for-mac/install/

# How to install
Clone repository from github
```
$ git clone https://github.com/okenak/runphp.git ~/.runphp
```
Add path to environment variable
```
$ echo 'export PATH="$HOME/.runphp/bin:$PATH"' >> ~/.bash_profile
```
Reload bash_profile
```
$ source ~/.bash_profile
```

# Usage
```
$ runphp

runphp is a tool for ...

Usage:
    runphp [option] [<command>]

Options:
    version    print runphp version
    cli        run php-script         (example: run-php cli main.php)
    composer   run composer           (example: run-php composer install)
    server     run build in webserver (example: runphp server)
```
