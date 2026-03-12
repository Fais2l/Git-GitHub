# GitHub

GitHub is a cloud-based platform where you can store and collaborate on your Git repositories. When working with GitHub, you need to understand the relationship between your local machine and the remote repository.

---

## Upstream and Downstream

### Upstream (Remote Repository)

```
Upstream = GitHub (Remote Server)
```

The **upstream** is your remote repository hosted on GitHub. It's the central location where your code is stored online and shared with other developers.

---

### Downstream (Local Repository)

```
Downstream = Your Computer (Local Machine)
```

The **downstream** is your local repository on your computer. It's where you work, make changes, and commit your code before sending it to GitHub.

---

## Workflow: Local ↔ GitHub

```
Your Computer (Downstream) ←→ GitHub (Upstream)
   Local Repo                  Remote Repo
   (git push)                  (git pull)
```

---

## Creating Files on GitHub

You can create files directly on GitHub's website without using Git commands on your computer.

---

## git push

```git
git push
```

Uploads your local commits from your computer (downstream) to GitHub (upstream).

---

## git pull

```git
git pull
```

Downloads changes from GitHub (upstream) to your computer (downstream) and merges them with your local code.m (Remote Repository)
