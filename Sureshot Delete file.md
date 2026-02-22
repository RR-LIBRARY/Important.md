```bash
# Delete step 1
git clone https://github.com/MrAnujBabu/remix-of-lovable-slides.git

# 2. Enter the folder (Note: Folder name matches the repo name)
cd Prj5.git 

# 3. Delete the specific file
git rm filename.txt

# 4. Commit the change
git commit -m "Removed file"

# 5. Push changes to GitHub
git push origin main
```

**Step 2** 
```bash
# Delete step 2 
find . -path ./.git -prune -o -exec rm -rf {} + 2>/dev/null || true

# 2. Check to confirm folder is empty
ls -la

# 3. Stage the deletions
git add -A

# 4. Commit the changes
git commit -m "Delete all files"

# 5. Push to GitHub
git push origin main
```
---
************************

<mark style="background: #FFB8EBA6;">Part 2</mark>

1.  **Git se saari files remove karein:**
    ```bash
    git rm -r .
    ```
2.  **Commit aur Push karein:**
    ```bash
    git commit -m "Delete complete project files"
    git push origin main
    ```
3.  **Bachi hui files (local) delete karein:**
    ```bash
    rm -rf *
    ```

---


```bash
cd ``
ls -a
```

