# vertx-graalvm-native
vertx-graalvm-native的代码示例
启动非常的简单
```shell
 mvn clean package -DskipTests;
```

给出我使用的graalvm版本
```shell
openjdk version "20.0.1" 2023-04-18
OpenJDK Runtime Environment (build 20.0.1+9-29)
OpenJDK 64-Bit Server VM (build 20.0.1+9-29, mixed mode, sharing)
```
和
```shell
java version "17.0.7" 2023-04-18 LTS
Java(TM) SE Runtime Environment GraalVM EE 22.3.2 (build 17.0.7+8-LTS-jvmci-22.3-b15)
Java HotSpot(TM) 64-Bit Server VM GraalVM EE 22.3.2 (build 17.0.7+8-LTS-jvmci-22.3-b15, mixed mode, sharing)
```
测试磁盘占用：
```
-rwxr-xr-x  1 dreamlike dreamlike  34M May  4 17:52 demo-ce-epilson
-rwxr-xr-x  1 dreamlike dreamlike  37M May  4 17:54 demo-ce-serial
-rwxr-xr-x  1 dreamlike dreamlike  37M May  4 17:49 demo-ee-epilson
-rwxr-xr-x  1 dreamlike dreamlike  53M May  4 17:40 demo-ee-g1
-rwxr-xr-x  1 dreamlike dreamlike  41M May  4 17:45 demo-ee-serial
-rwxr-xr-x  1 dreamlike dreamlike  53M May  4 20:02 demo-ee-static-g1
-rwxr-xr-x  1 dreamlike dreamlike  41M May  4 18:59 demo-ee-static-serial
```
