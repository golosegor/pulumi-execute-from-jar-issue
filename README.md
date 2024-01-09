# to build jar file

```bash
cd demo/
pulumi up
mvn package
```


# to make repro
```bash
cd repro-folder
pulumi up --logtostderr --logflow -v=11 2> out.txt
```
