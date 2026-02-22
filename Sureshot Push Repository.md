
```bash
# Push Step 1 
rm -rf .git

# 2. Naya git initialize karein
git init

# 3. Saari files add karein (Ye wala step aapne poocha tha)
git add .

# 4. Commit karein
git commit -m "Initial commit"

# 5. Branch ka naam 'main' karein
git branch -M main
```

```bash
# Push Step 2
git remote remove origin
git add .
git remote add origin https://github.com/MrAnujBabu/Import-.git
git push -u origin main --force
```
