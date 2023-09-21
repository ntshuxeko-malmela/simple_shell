cmake_minimum_required(VERSION 3.26)
project(simple_shell C)

set(CMAKE_C_STANDARD 11)

include_directories(.)

add_executable(simple_shell
        _atoi.c
        builtin.c
        builtin1.c
        environ.c
        errors.c
        errors1.c
        exits.c
        getenv.c
        getinfo.c
        getLine.c
        history.c
        lists.c
        lists1.c
        main.c
        memory.c
        parser.c
        realloc.c
        shell.h
        shell_loop.c
        string.c
        string1.c
        tokenizer.c
        vars.c)
