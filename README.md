# visual subnets
Visual subnet calculator as seen at http://www.davidc.net/sites/default/subnets/subnets.html and from https://github.com/davidc/subnets

# Run with docker

# Enhanced to enable naming of subnets and additional features such as wildcard masks.

```
cd <project folder>
docker build . -t subnets
docker run -d -p 5001:80 --name subnets subnets
```
