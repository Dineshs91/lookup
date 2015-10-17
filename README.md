# Look-up

Get the meaning of a word on your terminal

![demo](look-up-demo.gif "look-up demo")

## Prerequisites

*Click*

```$ pip install click```

*Wordnik*

```$ pip install wordnik```

## Install

```$ pip install look-up```

You need to get an api key from [wordnik](http://developer.wordnik.com/) and set WORDNIK_API_KEY environment variable
to your developer key. That's it.

## Usage

```$ look-up```
This will get the word of the day and its definition.

```$ look-up -w gravity```
This will get the defintion of gravity

## Available options

* -w word 
 
#### Optional arguments
* -e [show example]
* -p [show pronunciation]
* -h [show help]
