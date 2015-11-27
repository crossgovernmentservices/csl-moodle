# moodlecsl

Pre-install of moodle based on centos 6.6

# usage

Providing you have docker toolkit installed (mac/windows)? 

Just run this compose command from a docker quick terminal.

```
docker-compose up -d
```

Alternatively you could run this container the old fashion way:

```
docker run -d -p 80:80 moodlecsl /usr/sbin/apachectl -D FOREGROUND
```

Now use your browser or commandline to hit the endpoint

[moodle web install](http://localhost)

or

```
curl -L localhost
```
