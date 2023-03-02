# springbootstarter - Demo App 1
(Jesvin: baseBranch/issue testing)  
Small Spring app with Maven to test Mend GHE features

## Add vulnerability
To introduce vulnerability, run the below command in terminal. This replaces `pom.xml` introducing a vulnerable dependency.
```
cp pom.xml.vulnerable pom.xml; git commit -am "Add vulnerable dependency"; git push
```

## Remove vulnerability
To remove the vulnerability, run the below command in terminal. This replaces `pom.xml` removing a vulnerable dependency.
```
cp pom.xml.not-vulnerable pom.xml; git commit -am "Remove vulnerable dependency"; git push
```
