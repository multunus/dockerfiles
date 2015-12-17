[![Docker Pulls](https://img.shields.io/docker/pulls/peterlazar1993/react-native-android.svg?style=flat-square)](https://hub.docker.com/r/peterlazar1993/react-native-android/)
[![](https://badge.imagelayers.io/peterlazar1993/react-native-android:latest.svg)](https://imagelayers.io/?images=peterlazar1993/react-native-android:latest 'Get your own badge on imagelayers.io')

# React Native Android
### based on [beevelop/android](https://github.com/beevelop/docker-android)
- Ant 1.9.6
- Maven 3.3.3
- Gradle 2.5 (Groovy 2.4.3)
- Android 24.4.1
    + APIs: android-10,android-15,android-16,android-17,android-18,android-19,android-20,android-21,android-22,android-23
    + Build-Tools: 23.0.2
- nvm 0.29.0
- node 5.2.0
- npm 3.3.12
- react-native-cli 0.1.7

----
### Pull from Docker Hub
```
docker pull peterlazar1993/react-native-android:latest
```

### Run image
```
docker run -it beevelop/android bash
```

### Use as base image
```Dockerfile
FROM beevelop/android:latest
```
