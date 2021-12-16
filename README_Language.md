# Choice of Javascript and Node.js

### Reason why I choose Javescript and Node.js

Not only Application but also Web could be designed completely with Javascript and Node.js.
Javascript is one of language and Node.js is one of framework.
Framework means main structure of architecture that should be complied rules for good operating.
I think new developer couldn't know many kinds of computing language.
Please refer below languages and frameworks for good understanding.
|Language|Framework|
|--|--|
|Java|Spring boot|
|PHP|Laravel|
|Javascript|Node.js|
|Python|Django|

If you use Javascript and Node.js, you could make application or web regardless of thread sequences, because they use non-blocking IO with single thread and send response when each request is finished in parallel.
It's simple for you to make application or web if you use javascript and node.js compared to other languages and frameworks. you could use **only one language and only one framework** for application or web. You may use several languages and framework that suit certain condition or purpose except for javascript and node.js.
In addition, many major companies make their application and web using node.js. "Uber, Netflix, and so on".
It was demonstrated what these computing language and framework lead to trend by these major companies.
These has good things such as high performance, easy to access and easy to execute complicated system.
I hope this choice be opportunity to improve my computing skills.

P.S : Difference between Library and Framework

- Library : main loop call "Library" when he needed.
- Framework : "Framework" call inputs for good operating following that rules.

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
- When error : error: failed to push some refs to URL, you use `git pull` and then `git push` once again to move to source from remote to local and connection
