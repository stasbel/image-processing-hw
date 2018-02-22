# image-processing-hw

Image processing course homework at SPbAU 8th term

## Installation

### Dev

I use python and [pipenv](https://docs.pipenv.org/) as a primary tools for 
development. See [Pipfile](Pipfile), [Pipfile.lock](Pipfile.lock), 
[requirements-dev.txt](requirements-dev.txt)(if any) and
[requirements.txt](requirements.txt) for full specification of 
platform, python and dependency packages.  
Basically, to reproduce enviroment, you need to run `pip install -r 
requirements.txt` with certain [version of python](Pipfile.lock#L15). However, 
it is recommended to use [virtualenv](https://virtualenv.pypa.io/en/stable/). 

### Makefile

I provide [Makefile](Makefile) for convinient commands implementation.  
Run `make help` to get info on that.

## Usage

`make help`

### Tasks

See particular task for more info on that.

## License

[MIT](LICENSE)