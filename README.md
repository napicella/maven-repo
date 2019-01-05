# maven-repo
Repo used as a super simple and cheap maven repo

See link for a step by step guide: https://dzone.com/articles/using-github-as-maven-repository

__Note__: 
The guide contains an error about the url to use for the repo. 
The url of the repo is for this repo: https://raw.github.com/napicella/maven-repo/artifacts/master  

Also, it is necessary to add to ~/.m2/settings.xml

```
<!-- NOTE: MAKE SURE THAT settings.xml IS NOT WORLD READABLE! -->
<settings>
  <servers>
    <server>
      <id>github</id>
      <username>YOUR-USERNAME</username>
      <password>YOUR-PASSWORD</password>
    </server>
  </servers>
</settings>
```

