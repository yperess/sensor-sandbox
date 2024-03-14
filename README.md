# Sensor sandbox

```shell
$ git clone --recursive git@github.com:yperess/sensor-sandbox.git
$ source bootstrap.sh
$ west init -l manifest
$ west update
$ west build -p -b native_sim app
$ pw ide sync
```
