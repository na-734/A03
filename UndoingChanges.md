# Undoing Changes

## git reset --soft HEAD~1
```bash
git reset --soft HEAD~1
```
**What It Does:**  
Unrolls the previous commit to staging but does not change your files.

**Narrative:**  
Useful if your commit message has turned out to be incorrect but still need the changes.

---

## git reset --mixed HEAD~1
```bash
git reset --mixed HEAD~1
```
**What It Does:**  
Undoes the files of the last commit and stores the changes in your working directory.

**Narrative:**  
Good for reversing what needs to be written without losing changes.

---

## git reset --hard HEAD~1
```bash
git reset --hard HEAD~1
```
**What It Does:**  
Completely undoes the last commit and all the changes.

**Narrative:**  
Do that slowly! It will erase your work – do that only if you are sure.

---

## git checkout -- <file>
```bash
git checkout -- <file>
```
**What It Does:**  
Overwrites local modifications by undoing the earlier commit's file.

**Narrative:**  
Convenient to reverse unintended modifications of a file prior to staging.

---

## git restore <file>
```bash
git restore <file>
```
**What It Does:**  
Reconstructs contents of files from the commit or the index.

**Narrative:**  
Another contemporary way of disposing of modifications implemented in a document.