# Criar repo
```zsh
git init
```

# Trackear arquivos
git add .
git add filename

# Commit 
```zsh
git commit 
```

# Diff
```zsh
git diff --cached   # Verifica modificações que ainda não foram commitadas nos arquivos trackeados 
```

# Git log
```zsh
git log
git log -p          # Mostra o diff de cada arquivo
git log --stat --summary  # Apresentação do log de uma forma mais interessante
```

# Git branch/checkout
```zsh
git branch <nome>   # Cria uma nova branch
git branch          # Lista todas branchs
git checkout <nome> # Vai para a branch <nome>
```

# Workflow
```zsh
git branch experimental
git checkout experimental 
git commit -ma "comentário" # na branch experimental
git checkout master
git merget experimental
git branch -d experimental # deleta a branch experimental
```

# OBS: Em caso de conflitos execute
```zsh
git diff 
```
