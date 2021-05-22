# Error_page

$Error got run from jenkins server
Got permission denied while trying to connect to the Docker daemon socket at unix:///var/run/docker.sock: Post http://%2Fvar%2Frun%2Fdocker.sock/v1.40/build?buildargs=%7B%7D&cachefrom=%5B%5D&cgroupparent=&cpuperiod=0&cpuquota=0&cpusetcpus=&cpusetmems=&cpushares=0&dockerfile=Dockerfile&labels=%7B%7D&memory=0&memswap=0&networkmode=default&rm=1&session=w4yh71w41ng5pgo6f23wk1qqp&shmsize=0&t=bijuvinoth%2Fjavawebappapp&target=&ulimits=null&version=1: dial unix /var/run/docker.sock: connect: permission denied

resolve: sudo chmod 666 /var/run/docker.sock

