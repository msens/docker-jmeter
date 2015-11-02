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
docker run -i -t --rm -v $(pwd)/tests:/opt/jmeter myname/jmeter bin/jmeter -n -t /opt/jmeter/tests/test-jmeter.jmx -l /opt/jmeter/test-jmeter.jtl
```


docker run -i -t --rm -v $(pwd)/tests:/root /bin/bash jmeter.sh -n -t test-jmeter.jmx -l test-jmeter-results.jtl



OLD:

## Example usage

```bash
docker run -i -t --rm -v $(pwd):/root hauptmedia/jmeter bin/jmeter -n -t /root/all_in_one_001.jmx
```
