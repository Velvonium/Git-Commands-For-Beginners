<h1 align="center">🐱 Git Commands For Beginners 🪝</h1>
<p align="center">
<img alt="Number of Forks" src="https://img.shields.io/github/forks/Velvonium/Git-Commands-For-Beginners?color=green&label=Forks">
<img alt="Number of Stars" src="https://img.shields.io/github/stars/Velvonium/Git-Commands-For-Beginners?color=yellow&label=Stars">
</p>
<h3 align="center">All the basic git commands that you must know as beginners and how to use them.</h3>
<h3 align="center">⭐ Please Star This Repository ⭐</h3>
<br>


------

<br>

## 1️⃣ How To Upload Your Code From Your Computer To Your Github Repository?
1. Go to repository tab in your github account and create a new repository, give it a name, set visibilty to public or private and do not add a deafault README.md file.
2. Make sure that you have GitBash installed and connected to your Github account. You can find many YouTube videos on how to do this.
3. Go to your local folder where the code is stored and right click, you will find an option "Open GitBash Here".
4. `git init` use this command to initialize your repository.
5. `git add .` use this command to add your files into git.
6. `git commit -m "put a comment here"` this command will add a comment so that you later know what was the commit about.
7. `git branch -M main` This command will set the branch to main.
8. `git remote add origin https://yourgithubrepo.git` This will add your github repo link to remote and thus link it to your local repo.
9. `git push -u origin main` This is final command to push all the files online inside the repo.
10. Once this is done, you just need to do 4th, 5th and 8th command in order everytime to update the online repository with any changes in local repo.
<br>

-----------------------------------

<br>

## 2️⃣ How to collaborate on someone else's repo?
1. Fork the repo that you wish to collaborate on.
2. Clone this forked repo into your local computer using GitBash command `git clone forkedrepolink.git`
3. Then connect your local repo to main repo using: `git remote add upstream mainrepolink.git`
4. `git fetch upstream` use this command and `git rebase upstream/main` this one to sync main repo and local repo.
5. Make changes into local repo --> Push changes into forked repo --> Send Pull Request to main repo

## 🔥Join Our Discord For More Such Repositories!
[Discord Link](https://discord.com/invite/99m7y3MSEa)
