# it-training
it training and support


# Basic git commands

# Initialize git repository
git init  				# Initialize git in directory

# Staging files
git add file1.js    		#staging a single file
git add file1.js file2.js         #staging multiple files
git add .*js			#staging by pattern
git add .				# Staging all the content of the directory
git ls-files				# View files in the staging area

# Viewing Status
Git status					# Full status
Git status -s    				# Short status

# Committing 
Git commit -m”Mesage”			# Write a one line message

# Central Repository Changes
Git push origin main			# Write code changed to repository
Git pull origin main			# Get code changed from repository

# Ignore files
.gitignore					# Ignore large or unwanted files
