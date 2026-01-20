

# ubuntu / demo-iso-build-in-docker




## Usage

### help

run

``` sh
make help
```

show

```
Usage:
	$ make [action]

Example:
	$ make
	$ make help

	$ make box-build

	$ make box-run
	$ make box-run-portal

```




## Steps

## Steps / Build

> run to build docker-image

``` sh
make box-build
```

> then run to build iso-file in docker

``` sh
make box-run-portal
```

> check port dir

``` sh
ls -1 port
```
