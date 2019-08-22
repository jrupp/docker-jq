# Dockerized jq

Using [jq](https://stedolan.github.io/jq/) 1.6, on scratch.  Less than 4MB.

Usage:

```shell
docker run -i --rm jrupp/jq <options>
```

For example:

```shell
echo '{"a": 3, "b": 6}' | docker run --rm -i jrupp/jq '.a'
```
