# HelloWorld
Write Hello World program in programming languages

![HelloWorld Image](helloworld.jpg)

## How to Contribute
- Fork this repository

- Clone your forked repository on your system
> `git clone https://github.com/your-username/HelloWorld.git`

- Add your program in any programming language

- Push your changes to the master branch
> `git push origin master`

- Create a pull request

## Steps to rebase your forked repository with original repository
1. Add the remote and call it upstream
> `git remote add upstream https://github.com/mukulgoyal793/HelloWorld.git`

2. Fetch all the branches of that remote into remote-tracking branches
> `git fetch upstream`

3. Make sure that you're on your master branch
> `git checkout master`

4. Rewrite your master branch so that any commits of yours that aren't already in upstream/master are replayed on top of that other branch
> `git rebase upstream/master`

5. Finally push your changes to master branch
> `git push origin master`
