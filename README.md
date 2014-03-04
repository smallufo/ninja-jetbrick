JetBrick template module for Ninja framework.
=====================

JetBrick template engine ( https://github.com/subchen/jetbrick-template ) is a compiled , high-efficiency template engine.
It can be used to replace JSP or Velocity or freemarker .
The performance is said to be 4 or 5 times better than freemarker.

![performance](http://i.imgur.com/jkySEJ2.png)

Usage
=====================

1) Add the ninja-jetbrick-module to your pom.xml:

    <dependency>
      <groupId>org.ninjaframework</groupId>
      <artifactId>ninja-jetbrick-module</artifactId>
      <version>0.1.0</version>
    </dependency>

2) In your conf/Module.java , add:

    install(new NinjaJetbrickModule());


That's all.