# webbench

webbench is a very simple tool for benchmarking WWW or proxy servers in Linux. It uses fork() for simulating multiple clients to test if your website can handle many clients at once.

##Install

    cmake .
    sudo make
    sudo make install

##Usage


| short PARM   | long PARM             |        Usage        |
| -------------|:---------------------:|:-----------------:|
|-f            |--force                |don't wait for the server response       | 
|-r            |--reload               |send request to reload                   |
|-t            |--time <sec>           |running time, second(s)                  |
|-p            |--proxy <server:port>  |send request via proxy server            |
|-c            |--clients <n>          |create how many clients, default:1       |
|-9            |--http09               |use HTTP/0.9                             |
|-1            |--http10               |use HTTP/1.0                             |
|-2            |--http11               |use HTTP/1.1                             |
|              |--get                  |use GET                                  |
|              |--head                 |use HEAD                                 |
|              |--options              |use OPTIONS                              |
|              |--trace                |use TRACE                                |
|-?/-h         |--help                 |print help info                          |
|-V            |--version              |print version                            |
