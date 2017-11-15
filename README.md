# stamp-maven-repository

## Add repository to your maven project

```maven
<repositories>
  <repository>
    <id>stamp-maven-repository-mvn-repo</id>
    <url>https://stamp-project.github.io/stamp-maven-repository/</url>
    <snapshots>
        <enabled>true</enabled>
      <updatePolicy>always</updatePolicy>
    </snapshots>
  </repository>
</repositories>
```


## Deployed project:
  * [sosiefier](https://github.com/DIVERSIFY-project/sosiefier)
```xml
<dependency>
  <groupId>fr.inria.diversify.sosiefier</groupId>
  <artifactId>MODULE</artifactId>
  <version>1.0.0</version>
</dependency>
 ```

  * [pitest-descartes](https://github.com/STAMP-project/pitest-descartes)
```xml
<dependency>
  <groupId>fr.inria.stamp</groupId>
  <artifactId>descartes</artifactId>
  <version>0.1-SNAPSHOT</version>
</dependency>
```

 * [dspot](https://github.com/STAMP-project/dspot)
```xml
<dependency>
  <groupId>fr.inria.stamp</groupId>
  <artifactId>dspot</artifactId>
  <version>1.0.0</version>
</dependency>
 ```
