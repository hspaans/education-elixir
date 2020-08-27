# Learning Elixir

## Introduction

Check if and which version of Elixir is installed.

```shell
$ elixir --version
Erlang/OTP 22 [erts-10.7.2.3] [source] [64-bit] [smp:4:4] [ds:4:4:10] [async-threads:1] [hipe]

Elixir 1.10.4 (compiled with Erlang/OTP 22)
```

With `iex` you enter the interactive shell and with pressing `Ctrl-C` twice you exit it.

```shell
$ iex
Erlang/OTP 22 [erts-10.7.2.3] [source] [64-bit] [smp:4:4] [ds:4:4:10] [async-threads:1] [hipe]

Interactive Elixir (1.10.4) - press Ctrl+C to exit (type h() ENTER for help)
iex(1)> 40 + 2 
42
iex(2)> "Hello" <> " world"
"Hello world"
iex(3)>
```

We can also run *Hello world* from script.

```elixir
IO.puts "Hello world from Elixir"
```

And we run it from the command line we get the *Hello world*

```shell
$ elixir src/ex101/ex101.exs 
Hello world from Elixir
```
