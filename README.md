# bashrc

```bash
alias csvcol='awk -F, '\''{ printf "\033[1;34m%-3s\033[0m", NR; for (i = 1; i <= NF; i++) { printf " | \033[1;3%dm%-10s\033[0m", (i % 6) + 1, $i; } printf "\n"; }'\'
```
