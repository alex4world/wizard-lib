# maven2
the repository is mainly to support the maven2 mirror jar library info
use the github repository to maintaince the maven2 library , that as to the a mirror help us

## （1）to append the content pom.xml：
```
<repositories>
    <repository>
        <id>alex-repository</id>
<<<<<<< HEAD
        <url>https://raw.githubusercontent.com/alex-repository/maven2/master/dev/</url>
=======
        <url>https://raw.githubusercontent.com/alex4world/maven2/master/develop/</url>
>>>>>>> 1457b408fd3e1b9b54a44d9ff653cc7202478c71
    </repository>
</repositories>

```
## （2）to append the content settings.xml:

```
<mirrors>  
  <mirror>  
   <id>alex.repository.github</id>  
   <name>alex-repository</name>  
<<<<<<< HEAD
   <url>https://raw.githubusercontent.com/alex-repository/maven2/master/dev/</url>  
=======
   <url>https://raw.githubusercontent.com/alex4world/maven2/master/develop/</url>  
>>>>>>> 1457b408fd3e1b9b54a44d9ff653cc7202478c71
   <mirrorOf>central</mirrorOf>  
  </mirror>
</mirrors>  
```

