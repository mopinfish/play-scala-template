## Preparation

### update java package for mac
http://qiita.com/yanap/items/186d5bd1118f68f725d8

### install mysql for mac
http://qiita.com/hkusu/items/cda3e8461e7a46ecf25d

### install activator for mac 
http://qiita.com/MasahiroSakoda/items/9bc68a7e4a4ce5268445

```
$ brew install typesafe-activator
```

### setup and run application
```
cd [your workspace]
git clone git@github.com:mopinfish/play-scala-template.git
```

run application

```
$ cd play-scala-template
$ ./activator run -Dhttp.port=9000
```

----

## commands 

### create new scala application by activator

```
$ activator new my-app play-scala
```

### run application

```
$ cd [project_root]
$ ./activator run -Dhttp.port=9000
```

## execute User API

```
$ curl -XGET http://localhost:9000/json/list
```
