# Documentation
Projects documentation

Please check the [wiki](https://github.com/maurodelazeri/Documentation/wiki)

`conan install . -s build_type=Debug --install-folder=cmake-build-debug --build missing`

### Virtual desktop

* Clean image
```
docker run -p 6080:6080 -v /opt/zinnion/:/home/mauro/zinnion -v /root/.ssh/:/root/.ssh/ zinnion-desktop-dev
```
