#Choice of Javascript and Node.js

### Reason why I choose these

Application and Web could be completed with Javascript and Node.js.
I think new developer couldn't know many kinds of computing language.
|Language|Framework|
|--|--|
|Java|Spring boot|
|PHP|Laravel|
|Javascript|Node.js|
|Python|Django|

If you use Javascript and Node.js, you could make application and web between Front-end and Back-end.
It's simple for you to make something **Only 2 Computing Language**.
In addition, many major companies make their application and web using node.js. "Uber, Netflix, and so on".
What these computing languages lead to trend was demontrated by these major companies.
High performance, Easy to access and control in Front-End and Back-End condition are good things.
I hope this decision be opportunity to improve my computing skills.

P.S : Difference between Library and Framework

- Library : I call "Library" when I needed
- Framework : "Framework" call me for good operating following that rules.

**Resolve Failure**

Fatal : The current branch master has no upstream branch.

- Occurred when put in "git push"
- Repository's name is needed when git push
- Countermeasure : `git push --set-upstream Language main`
- To push the current branch and set the remote as upstream, use

Fatal : Exiting because of unfinished merge

- Occurred when put in "git pull"
- Not finished commit of deleted README.md
- I changed the name of README file from README to README_Language on my local folder and git add completed but not finished commit
- Countermeasure : `git commit -m "deleted README.md"`
  `git add README_Language.md`
  `git push`
