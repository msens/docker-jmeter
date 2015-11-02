# docker-jmeter

Packages JMeter in a docker container


## 
Example usage

build:
```bash
docker build -t "myname/jmeter:latest" .
```

run:
```bash
docker run -i -t --rm -v $PWD/tests:/tests myname/jmeter bin/jmeter -n -t /tests/test-jmeter.jmx -l /tests/test-jmeter.jtl
```


OLD:

## Example usage

```bash
docker run -i -t --rm -v $(pwd):/root hauptmedia/jmeter bin/jmeter -n -t /root/all_in_one_001.jmx
```
