Drop-in replacement for [minlog](http://code.google.com/p/minlog), forked from http://minlog.googlecode.com/svn using `git svn`.

* Logs through slf4j instead of printing directly to stdout
* Suppresses no log levels at compile time so you can control them in your logging config instead

```xml
<dependency>
  <groupId>com.esotericsoftware.minlog</groupId>
  <artifactId>minlog</artifactId>
  <version>1.2-slf4j-jdanbrown-0</version>
</dependency>

...

<repository>
  <id>premise</id>
  <url>http://premise.artifactoryonline.com/premise/public</url>
</repository>
```
