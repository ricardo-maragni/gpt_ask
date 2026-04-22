# Atualizar

```terminal
git add .
git commit -m "Atualização"
git push -u origin main
```

# Resetar

```terminal
git checkout --orphan clean-main
git add .
git commit -m "Initial clean commit"
git branch -M main
git push --force-with-lease origin main
```