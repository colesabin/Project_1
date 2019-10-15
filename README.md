# Project 1
A scanner for the Quack language.

## To build
After downloading the repo use the following command to create a docker image:

`docker build --tag=proj1 .`

Then to run the image:

`docker run -it proj1`

## To run
Once in the docker image use the binary lexer in bin to scan a text file and
return the tokens.
For example using the sample bad_break.qk file:

`bin/lexer samples/bad_break.qk`
