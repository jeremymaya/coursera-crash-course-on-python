# Branching and merging 

1. When we merge two branches, one of two algorithms is used. If the branches have diverged, which algorithm is used?

* three-way merge

---

3. What command would we use to throw away a merge, and start over?

* git merge --abort

---

4. How do we display a summarized view of the commit history for a repo, showing one line per commit?

* git log --graph --oneline

---

5. The following script contains the result of a merge conflict. Edit the code to fix the conflict, so that both versions are included.


```python
def main():
       print("Start of program>>>>>>>")
       
       print("End of program!")
main()
```