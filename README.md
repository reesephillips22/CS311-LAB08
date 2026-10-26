# CS311 Lab 8: The Tree Walkers

The lab is due Wednesday, October 21, 2026, at 11:59 PM Central under the approved course schedule amendment. Check Blackboard for the live assignment setting. Read `Lab_08_The_Tree_Walkers.md` for the graded requirements.

## Start

Use **Use this template** to make a repository under your own GitHub account, then clone your repository. If the instructor repository is not a template, clone it and change the remotes before pushing:

```sh
git clone https://github.com/cwillpinto/cs311-lab08-tree-walkers.git
cd cs311-lab08-tree-walkers
git remote rename origin upstream
git remote add origin <your-repository-url>
git remote -v
git push -u origin <your-branch>
```

Confirm `origin` points to your own repository. Do not push to the instructor starter.

## Build and check

Complete `search`, `inorder`, `preorder`, `postorder`, and `to_json` in `serialize_tree.py`. Keep `TreeNode`, `insert`, and the verification suite unchanged. Run `python serialize_tree.py` from the repository root with Python 3.11 or newer. The starter intentionally stops at `NotImplementedError` until you complete it.

## Submit in Blackboard

Follow the published Lab 8 submission contract: `Lab8_Theory.pdf` or `.md`, your completed `serialize_tree.py`, and the success token from your run. Keep your completed code in your own repository; Blackboard still requires the completed code file for this lab.
