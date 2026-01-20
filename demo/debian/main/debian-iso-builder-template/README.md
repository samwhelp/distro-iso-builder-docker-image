

# debian / demo-iso-build-in-docker




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

	$ make master-build

```




## Steps

## Steps / Build

> run to build docker-image

``` sh
make box-build
```

> then run to build rootfs-archive in docker

``` sh
make master-build
```

> check port dir

``` sh
ls -1 port
```
