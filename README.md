# Setup for personal or work)
chezmoi init <your-repo-url> --apply
chezmoi set --source-path .chezmoi.yaml --edit
# Change machine: work

````
data:
  machine: personal # or "work"
````
