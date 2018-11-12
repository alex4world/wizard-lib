# wizard-lib
the repository is mainly to support the maven2 mirror jar library info
use the github repository to maintaince the maven2 library , that as to the a mirror help us

## （1）to append the content pom.xml：
```
<repositories>
    <repository>
        <id>alex-repository</id>
        <url>https://raw.githubusercontent.com/alex4world/wizard-lib/master/dev</url>
    </repository>
</repositories>

```
## （2）to append the content settings.xml:

```
<mirrors>  
  <mirror>  
   <id>alex.repository.github</id>  
   <name>alex-repository</name>  
   <url>https://raw.githubusercontent.com/alex4world/wizard-lib/master/dev</url>  
   <mirrorOf>central</mirrorOf>  
  </mirror>
</mirrors>  
```

