---
type: slides
title: 'module4_03'
---

# Revert your changes

---
# Revert your changes


**reset hard** ✔️
**revert** ⬅️

Notes: We have already learned how to undo changes and delete our project history with **`git reset --hard`**. But what if we want to keep track of the reversion? 
 There is another way to go back in time, and that is to **revert** your changes.

---
#  Revert your changes: Go back to a previous commit (JupyterLab)


<center>

<img src='/module4/vc-revert.png' width="80%" alt="404 image"/>

</center>

Notes:
If you want to revert your changes, you can click the arrow icon in the commit you want to go back to in JupyterLab's "History" tab.
When you revert changes, you don't lose the history of the project. This means that you are going to create a new commit which reflects the fact that some intermediate commits have been reverted.

---

# Revert your changes: move to a previous commit (JupyterLab)


<center>

<img src='/module4/vc-revert-2.png' width="80%" alt="404 image"/>

</center>

Notes:
When you click the arrow, JupyterLab asks you for the commit title and description for that reversion. You can either keep the preloaded name here or find a more meaningful one.

---

# Revert your changes: move to a previous commit (JupyterLab)


<center>

<img src='/module4/vc-revert-3.png' width="80%" alt="404 image"/>

</center>

Notes:
Now you can see that you have a new commit, and your project has travelled back in time! Remember to push your changes if you want to keep your remote updated. This is particularly important if you are working with other collaborators who might be modifying the part that has been deleted!


---

# Revert your changes: move to a previous commit (terminal)

`git revert <commit id>`

<center>

<img src='/module4/vc-revert-t.png' width="80%" alt="404 image"/>

</center>

Notes:
If you want to do this with the terminal you will have to provide the SHA-1 code to identify the commit.

---

# Revert your changes: move to a previous commit (terminal)


<center>

<img src='/module4/vc-revert-t2.png' width="80%" alt="404 image"/>

</center>

Notes:

After running the command, the editor will pop up so you can modify the final commit message. If you close it as it is, the message will be the default one.
You will see that after closing the editor, now you have a new commit updated with the changes.

---

# Let's Practise



