# Documentation
Projects documentation

Please check the [wiki](https://github.com/maurodelazeri/Documentation/wiki)

`conan install . -s build_type=Debug --install-folder=cmake-build-debug --build missing`

### Virtual desktop

* Clean image
```
docker run -p 443:443 -e SSL_PORT=443 -e HTTP_PASSWORD=Br@sa154 -v /opt/ssl:/etc/nginx/ssl -v /opt/zinnion/:/home/mauro/zinnion -v /root/.ssh/:/root/.ssh/ -v /dev/shm:/dev/shm zinnionlcc/zinnion-desktop-dev
```
