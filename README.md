# About

I'm learning about [BOSH](http://docs.cloudfoundry.com/docs/running/bosh/) :D.
This project documents the steps I'm taking to develop and deploy a very basic BOSH release.
My current aim is to get the following "package" installed and running via BOSH:

```bash
#!/bin/bash
while :
do
	echo "I <3 BOSH"
	sleep 1
done
```

I'm using [bosh-lite](https://github.com/cloudfoundry/bosh-lite) and [bosh-gen](https://github.com/cloudfoundry-community/bosh-gen) to help achieve this. I'm documenting the steps I'm taking and writing notes in the [wiki](https://github.com/teddyking/hellobosh-boshrelease/wiki).
