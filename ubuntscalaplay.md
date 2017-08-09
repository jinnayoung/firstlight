## jdk + scala + play 
### java8-runtime-headless setting
 
```
sudo add-apt-repository ppa:openjdk-r/ppa
sudo apt-get update
sudo apt-get -f install
```
 
### Install Scala
 
``` 
sudo apt-get remove scala-library scala
wget http://www.scala-lang.org/files/archive/scala-2.12.3.deb
sudo dpkg -i scala-2.12.3.deb
sudo apt-get update
sudo apt-get install scala
```

### 우분투(Ubuntu)에 sbt설치하기
 
``` 
wget http://scalasbt.artifactoryonline.com/scalasbt/sbt-native-packages/org/scala-sbt/sbt/0.12.4/sbt.deb
sudo dpkg -i sbt.deb
sudo apt-get update
sudo apt-get install sbt
```
```
wget https://cocl.us/sbt01316zip
unzip sbt01316zip
sudo apt-get update
export PATH=$PATH:~/sbt/bin
```

### Giter8 설치

``` 
curl https://raw.githubusercontent.com/foundweekends/conscript/master/setup.sh | sh
(‘/home/soolbe/.conscript/foundweekends/conscript/cs/launchconfig’) 
```

### Download and Install Play (the folder should have permission to write)

```
sudo apt-get install unzip 
cd /opt
chmod 777 /opt 
wget http://downloads.typesafe.com/typesafe-activator/1.3.2/typesafe-activator-1.3.2-minimal.zip
unzip typesafe-activator-1.3.2-minimal.zip
mv activator-1.3.2-minimal activator
```
```
wget http://downloads.typesafe.com/typesafe-activator/1.3.6/typesafe-activator-1.3.6-minimal.zip
unzip typesafe-activator-1.3.6-minimal.zip
mv activator-1.3.6-minimal activator
```

### Add the activator script to your PATH and execute Activator

```
cd /opt/activator
export PATH=$PATH:~/activator
source ~/.bashrc
chmod a+x activator
./activator
```

### play 설치
```
wget http://downloads.typesafe.com/play/2.3.6/play-2.3.6.zip
```

```
wget https://example.lightbend.com/v1/download/play-scala-rest-api-example
unzip play-scala-rest-api-example
```

### SBT 

```
sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv 2EE0EA64E40A89B84B2DF73499E82A75642AC823
sudo apt-get update
sudo apt-get install sbt
```

```
object Hello {
def main(args: Array[String]) = println("Hello Jin World!")
}
```

### SBT + Ubuntu 

```
wget https://cocl.us/sbt01316tgz
tar -xvf sbt01316tgz
```

### SBT로 프로젝트 생성 (http://www.scala-sbt.org/release/docs/Directories.html)

```
sbt new sbt/scala-seed.g8
```
```
wget https://example.lightbend.com/v1/download/play-scala-rest-api-example
unzip play-scala-rest-api-example
```