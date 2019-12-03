# Fish shell - Repeat a command

## Repeat forever

```fish
while true
    echo 'Repeat'
end
```

## Repeat set number of times

```fish
for x in (seq 5)
    echo "Repeat $x"
end
```