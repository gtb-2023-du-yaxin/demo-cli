## Use following commands to generate gif file

```bash
CAST_FILE=demo-01-hello-world
rm -rf ${CAST_FILE}.cast && asciinema rec -i1.5 ${CAST_FILE}.cast
asciicast2gif -S 1 -s 2 ${CAST_FILE}.cast ${CAST_FILE}.gif
```

## Demo

### demo-01-hello-world

![demo-01-hello-world](https://raw.githubusercontent.com/GTB-training/C-cli-demo/master/demo-01-hello-world.gif)

