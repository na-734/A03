# Branching & Merging

## git branch
```bash
git branch
```
**What It Does:**  
Lists all the local branches in your project and highlights the one you're on.

**Narrative:**  
Helps you stay organized by seeing which branches exist and which one you're currently using.

---

## git branch <branch-name>
```bash
git branch <branch-name>
```
**What It Does:**  
Makes a new branch off of the current one.

**Narrative:**  
Useful when you're starting new features or experiments — lets you branch off without breaking main code.

---

## git checkout <branch-name>
```bash
git checkout <branch-name>
```
**What It Does:**  
Switches to another existing branch.

**Narrative:**  
Lets you jump into a different workspace — whether you're reviewing code or fixing bugs.

---

## git switch <branch-name>
```bash
git switch <branch-name>
```
**What It Does:**  
A newer and cleaner way to switch branches.

**Narrative:**  
Does the same thing as `checkout`, but feels less old-school. Great for getting around more easily.

---

## git merge <branch-name>
```bash
git merge <branch-name>
```
**What It Does:**  
Combines another branch into the one you're currently on.

**Narrative:**  
Once your feature or fix is done, use this to bring everything back together.