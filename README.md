# LEARN_GIT

- Notes

# SETUP

```

git config --global user.email "you@example.com"
git config --global user.name "Your Name"

CHECK
git config --list
OR
git config user.name
git config user.email

```

# Create your first repository

```

1. Using the graphic interface on the github website, create your first repository.
	
	OR
	
	2.1 (No readme)
	 
	2.2 (With readme)
	
create a new repository on the command line
	echo "# my_first_repository" >> README.md
	git init
	git add README.md
	git commit -m "first commit"
	git branch -M main
	git remote add origin https://github.com/MEBZMasondo/my_first_repository.git
	git push -u origin main

TO PUSH TO MAIN YOU MAY USE : git push
TO PUSH TO BRANCH YOU MAY USE :  

```

# CLONE

```
git clone https://{YOUR_PERSONAL_TOKEN}@github.com/{YOUR_USERNAME}/my_first_repository.git

e.g

git clone https://{YOUR_PERSONAL_TOKEN}@github.com/MEBZMasondo/my_first_repository.git

```

#  push an existing repository from the command line

```

git remote add origin https://github.com/MEBZMasondo/my_first_repository.git
git branch -M main
git push -u origin main

```

# BRANCES
## creacte branch

```

git checkout branch1
git checkout -b subbranch_of_b1 branch1

```


# REFERENCES

- https://kbroman.org/github_tutorial/

