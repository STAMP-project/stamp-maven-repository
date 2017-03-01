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
```  
<dependency>
  <groupId>fr.inria.diversify.sosiefier</groupId>
  <artifactId>MODULE</artifactId>
  <version>1.0.0</version>
</dependency>
 ```
