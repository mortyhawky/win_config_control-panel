#### Create Repo from pwsh

```ps1
git init
echo "`n#### Create Repo from pwsh" >> Create-Repo.md
git add -Av
git commit -m "$(date)"
```

```ps1
gh auth status
gh auth login
```

```ps1
gh repo create "win_config_control-panel" --public --source=. --remote=origin
git push -u origin main
```
