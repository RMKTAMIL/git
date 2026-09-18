# git

To Clone repo


run  inside the directory


cd ~/projects
git clone https://github.com/USERNAME/REPOSITORY.git


In Linux:

Yes. On Linux, you can clone any **public GitHub repository** into a directory you choose.

 ### 1\. Go to your custom directory

 For example, if you want repositories stored in `~/projects`:

```
mkdir -p ~/projects
cd ~/projects
```

 ### 2\. Clone the repository

```
git clone https://github.com/USERNAME/REPOSITORY.git
```

 For example:

```
git clone https://github.com/facebook/react.git
```

 This creates:

```
~/projects/react/
```

 ### 3\. Clone it into a specific directory name

 If you want a custom folder name:

```
git clone https://github.com/facebook/react.git my-react
```

 It will be stored as:

```
~/projects/my-react/
```

 ### 4\. Clone directly to an absolute path

 You can also specify the complete destination:

```
git clone https://github.com/USERNAME/REPOSITORY.git /home/yourname/my-project
```

 For example:

```
git clone https://github.com/facebook/react.git /home/yourname/code/react
```

 ### Useful commands afterward

```
cd /home/yourname/code/react
```

 Check the repository:

```
git status
```

 See the remote GitHub URL:

```
git remote -v
```

 Pull the latest changes later:

```
git pull
```

 **In short:**

```
git clone <github-repo-url> <your-custom-directory>
```

 If you give me the **GitHub repo URL** and the **Linux directory where you want it stored**, I can give you the exact command.
