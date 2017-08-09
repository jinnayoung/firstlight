## 1. Cloud Default Server Setting (Google Cloud) 

## 서버에 Java 설정 
### JDK 다운로드 
```
wget --header "Cookie: oraclelicense=accept-securebackup-cookie" http://download.oracle.com/otn-pub/java/jdk/8u144-b01/090f390dda5b47b9b721c7dfaa008135/jdk-8u144-linux-x64.tar.gz
```

### 압축 해제
 
```
tar -xvf jdk-8u144-linux-x64.tar.gz
```

### link directory 등록

``` 
ln -s jdk1.8.0_144/ java 
```

### vi .bash_profile

``` 
PATH=$PATH:~/java/bin
``` 

### bash profile 적용

```  
source .bash_profile
``` 

### Git 설치 확인

``` 
git --version 
``` 

### 설치필요하면 Git 설치

```  
sudo apt-get update
sudo apt-get install git
``` 
