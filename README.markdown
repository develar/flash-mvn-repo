# Add repository
    <repositories>
      <repository>
        <id>flash-mvn-repo</id>
        <url>http://develar.github.com/flash-mvn-repo/</url>
      </repository>
    </repositories>

# Install library
    mvn deploy:deploy-file -Durl=file://<path_to_repo>/flash-mvn-repo -Dfile=MinimalComps_0_9_10.swc -DgroupId=com.bit101 -DartifactId=minimalcomps -Dversion=0.9.10 -Dpackaging=swc

    mvn deploy:deploy-file -Durl=file:///Users/develar/flash-mvn-repo -Dfile=/Users/develar/Documents/MinimalComps_0_9_10-sources.jar -DgroupId=com.bit101 -DartifactId=minimalcomps -Dversion=0.9.10 -Dpackaging=jar -Dclassifier=sources
    