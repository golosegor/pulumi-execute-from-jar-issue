# to build jar file
```bash
mkdir -p demo && pulumi new java --dir demo
```
accept everything default


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
