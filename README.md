## Use following commands to generate gif file

```bash
CAST_FILE=demo-01-hello-world
rm -rf ${CAST_FILE}.cast && asciinema rec -i1.5 ${CAST_FILE}.cast
asciicast2gif -S 1 -s 2 ${CAST_FILE}.cast ${CAST_FILE}.gif
```

## Demo

### demo-01-hello-world

![demo-01-hello-world](demo-01-hello-world.gif)

### demo-02-custom-name

![demo-02-custom-name](demo-02-custom-name.gif)

### demo-03-timestamp

![demo-03-timestamp](demo-03-timestamp.gif)

### demo-04-nickname

![demo-04-nickname](demo-04-nickname.gif)

### demo-05-redirection

![demo-05-redirection](demo-05-redirection.gif)

### demo-06-piping-ps

![demo-06-piping-ps](demo-06-piping-ps.gif)

### demo-06-piping-history

![demo-06-piping-history](demo-06-piping-history.gif)

