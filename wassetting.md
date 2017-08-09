## spring source 빌드
 
### github 에서 소스가져오기
 
```
git clone http://github.com/jinnayoung/springboots.git
git clone https://github.com/slipp/my-slipp.git
```

```
cd my-slipp
./mvnw clean package 
git branch -a
git checkout -b iteration1_static_html origin/iteration1_static_html 
```

### maven 빌드

``` 
./mvnw clean package 
```

### web 실행

``` 
cd target 
java -jar my-slipp-1.0.jar
```

### open port 변경해서 web 실행

``` 
java -Dserver.port=80 -jar my-slipp-1.0.jar &
```

### 사용중인 port 확인

```
sudo netstat -tpln

java -jar -Dserver.port=80 -Djava.net.preferIPv4Stack=true my-slipp-1.0.jar
```


