# Setup for personal or work

## 1. Clone repo and init Chezmoi
```
chezmoi init <your-repo-url> --apply
chezmoi set --source-path .chezmoi.yaml --edit
```

## 2. Change machine: work
````
data:
  machine: personal # or "work"
````
