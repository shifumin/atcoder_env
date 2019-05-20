# AtCoder Env
Ruby execution Docker environment for Atcoder.  

## Stack
- Ruby 2.3.3
- and some gems

## Readying

```shell
$ docker pull ruby:2.3.3-alpine
```

```shell
$ git clone https://github.com/shifumin/atcoder_env
$ cd atcoder_env
```

## Examples

```shell
# Write code
$ vim app.rb

# Execute the above code
$ docker-compose run --rm app ruby app.rb
# or docker-compose run --rm --service-ports app ruby app.rb

# Execute Pry
$ docker-compose run --rm app pry
```
