# Stashing

## git stash
```bash
git stash
```
**What It Does:**  
Save your work temporarily and change directories to a new, clear working directory.

**Narrative:**  
You can utilize this if you would like to switch to another branch without committing your work.

---

## git stash pop
```bash
git stash pop
```
**What It Does:**  
Applies the last modifications stored, clearing them from the stash list.

**Narrative:**  
Take your work with you once you are ready to resume from where you stopped.

---

## git stash apply
```bash
git stash apply
```
**What It Does:**  
Applies the last (or selected) stash, but leaves the stash in the stash list.

**Narrative:**  
Convenient if having to repeat the changes or keep them handy as a backup.

---

## git stash save "message"
```bash
git stash save "message"
```
**What It Does:**  
Save your file with a special message to use at short notice.

**Narrative:**  
Mark cache so that you can recall what you are doing.