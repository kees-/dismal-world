## Client

Install 1.20.1 forge 47.3.7
Set pre-launch command to 

```sh
"$INST_JAVA" -jar packwiz-installer-bootstrap.jar https://raw.githubusercontent.com/kees-/dismal-world/refs/heads/main/pack.toml
```

## Server

Use packwiz to manage

Append to startup:

```sh
java \
  -jar $FORGE/packwiz-installer-bootstrap.jar \
  -g -s server $PACKWIZ/pack.toml
```
