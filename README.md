# jokeapp

Test Go APP

Go Cli Command line tool to get next jokes

# go run main.go

A cli tool for get next jokes

Usage:
jokeapp [command]

Available Commands:
help Help about any command
next Get a next dad joke

Flags:
--config string config file (default is $HOME/.jokeapp.yaml)
-h, --help help for jokeapp
-t, --toggle Help message for toggle

Use "jokeapp [command] --help" for more information about a command.

# example

go run main.go next
go run main.go next --term=army
