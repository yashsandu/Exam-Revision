## Steps to push changes:

### Add a new topic and add questions:

* Add a new topic:
	1. Go to _topics, go to correct module folder
	2. Copy+Paste existing file, rename to name of new topic
	3. Set the number to 1 more than the most recent highest topic number, title name, and the second tag to the name of the file (first tag is module - double check it!)
	4. Save it

* Add a new question:
	1. Go to _data, open questions.yml
	2. Copy and paste 3 existing lines, change topic, question and answer
	3. Save it

### Go to cmd

##### Pull changes
> git fetch upstream

> git merge upstream/master

> git push origin master

##### Push changes
> git add -A

> git commit -m "Added new topic and new questions"

> git push origin master

#### GitHub pull request
1. Go to pull requests on your fork
2. Create new pull request
3. Check base and head forks are correct (base is the original repository, head is your fork)
4. Add a title and description
5. Create pull request

Original owner accepts the request and done!
