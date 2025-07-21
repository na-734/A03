# Staging & Committing

## git status
```bash
git status
```
**What It Does:**  
Displays the status of your working directory and your staging area.

**Narrative:**  
Utilize this frequently to discover what files are being added, modified, or that need to be committed.

---

## git add
```bash
git add <file>
```
**What It Does:**  
Prepares a given file for commit.

**Narrative:**  
These can be used to create only special changes to your next commit – helpful for fine-tuning what you commit.

---

## git add .
```bash
git add .
```
**What It Does:**  
Stage all the added and modified files in the present working directory for commit.

**Narrative:**  
Handy if you wish to commit everything that has changed in a single operation without naming every file.

---

## git commit -m
```bash
git commit -m "Your message"
```
**What It Does:**  
Updates the changed items with a brief description of the change.

**Narrative:**  
After staging, use this to commit your changes. Save your changes permanently using clear messages that describe what was changed.

---

## git commit -am
```bash
git commit -am "Your message"
```
**What It Does:**  
Adds tracked files at the same time. Commits.

**Narrative:**  
Use standard implementations of Git by default at high speed.

---

## git log
```bash
git log
```
**What It Does:**  
Shows a commit list with metadata.

**Narrative:**  
You can use that to see commit history, see who made the changes, and when they happened.