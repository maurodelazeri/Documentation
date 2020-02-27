# Documentation
Projects documentation

Please check the [wiki](https://github.com/maurodelazeri/Documentation/wiki)

`conan install . -s build_type=Debug --install-folder=cmake-build-debug --build missing`

### Virtual desktop

* Clean image
```
docker run -p 6080:6080 zinnionlcc/zinnion-desktop
```

* DEV image
```
docker run -p 6080:6080 -p 3000:3000 -p 50050:50050 -p 50051:50051 -p 50052:50052 -p 50053:50053 -p 50054:50054 -v /opt/zinnion/:/home/mauro/zinnion -v /root/.ssh/:/root/.ssh/ zinnionlcc/zinnion-desktop-dev
```
