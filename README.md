# konf
basic configuration

```shell
$ mv konf/tmux.conf ~/.tmux.conf
```

```shell
// check color for tmux config
for i in {0..255} ; do
	printf "\x1b[38;5;${i}mcolour${i}\n"
done
```
