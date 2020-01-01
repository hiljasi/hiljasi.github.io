---
layout: default
---

## KIK-LG219

Command line tools for linguists (KIK-LG219) was my second language technology related course in HY. I decided to attend the course with some of my friends because we were interested in how linguists can utilize command line tools. This section will provide a small overview of what my experience with the course was like.

### Week 1

During this week, we learned to set up our command-line environments and got used to some of the basic commands used on the command line. I found this week to be quite easy and had no issues with anything. It was really interesting to get to know more about the command-line as I've never before worked with it. Some really useful commands we learned the first week were, for example, `ls`, `pwd` and `cd`.

### Week 2

On Week 2, we learn to work with directories and used emacs. We also learnt how to use the commands `gzip` and `tar` to compress files and directories as well as `chmod` for changing permissions for a file. For instance, the command below would give the user, the group and others all the permissions for the file.

```
chmod ugo+rwx file.txt
```

This week I had some issues with the remote server because my username for the server was not the one I thought it was but once I was able to remember the correct username, I was all set.

### Week 3

During this week, we learned about encoding systems, used grep and got to work with some text from which we compiled lists and such files. My favourite command from this week was `sort` because I found it to be very powerful and useful. I really liked text processing but working with the formatted text files was quite difficult for me.

### Week 4

On week 4, we learned more about text processing and, more importantly, about piping commands. Piping commands made everything much easier since each step didin't have to be applied separately. Instead, we learnt that you can have many commands on the same line by using pipes, for example,

```
cat file.txt | tr -s '\n\t\r''\n' | sort | uniq -c | sort -nr
```

We also learned the `sed` command. I remember having some issues with this week but, in retrospect, it was a very important week.

### Week 5

During this week, we learned to write simple scripts. I was really excited for this week because writing scripts has always seemed so cool. We also learned conditional execution by the `if` command. For example, the one below would make it so that the script works only when there is one (and only one) command line argument accompanying the command.

```
if [ $# -ne 1]
then
	echo "Error: One command line argument required!"
	exit 1
fi
```

We also leart how to edit the .bashrc/.bash_profile file which allowed me to chane the colours of my command line for brighter ones that made it easier for me to work on command line.

### Week 6

This week we learned about installing software and python packages with `sudo` and `apt-get`. For instance, the command below updates the already downloaded things.

```
sudo apt-get update
```


I found week 6 to be a bit difficult, since we learnt so many new things, but I was able to push through with the support of my friends and knowing that there wouldn't be many weeks left before the course would end.

### Week 7

During the final week of the course, we learnt to use GitHub and version control. GitHub is s still quite a new tool/environment for me, since we only used it for a week on the course, but I can already see how useful it could be for someone who has a lot of LT projects going on. There are quite many commands that we learnt this week that are needed when using GitHub, for example

| `git branch`	 | to check which branch you are using	     |
| `git push` 	 | to push things to GitHub   	  	     |
| `git pull`	 | to pull things from GitHub		     |
| `git clone`	 | to clone a directory from GitHub locally  |

