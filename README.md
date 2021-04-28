![GitHub Workflow Status](https://img.shields.io/github/workflow/status/buluma/docker-android/Docker%20Image?style=for-the-badge)
![Docker Pulls](https://img.shields.io/docker/pulls/buluma/android.svg?style=for-the-badge)
![Docker Stars](https://img.shields.io/docker/stars/buluma/android?style=for-the-badge)
![Docker Image Size (tag)](https://img.shields.io/docker/image-size/buluma/android/latest?style=for-the-badge)
![License](https://img.shields.io/github/license/buluma/docker-android?style=for-the-badge)
[![GitHub release](https://img.shields.io/github/release/buluma/docker-android.svg?style=for-the-badge)](https://github.com/buluma/docker-android/releases)
![GitHub Release Date](https://img.shields.io/github/release-date/buluma/docker-android?style=for-the-badge)

# Android 11.0
### based on [beevelop/java](https://github.com/beevelop/docker-java)
- Java 8
- Gradle 4.4.1 (Groovy: 2.4.16)
- Apache Maven 3.6.3
- Ant 1.10.7

### Pull from Docker Hub
```
docker pull beevelop/android:latest
```

### Build from GitHub
```
docker build -t beevelop/android github.com/beevelop/docker-android
```

### Run image
```
docker run -it beevelop/android bash
```

### Use as base image
```Dockerfile
FROM beevelop/android:latest
```

----

![One does not simply use latest](https://i.imgflip.com/1fgwxr.jpg)
