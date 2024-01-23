# Wagtail Tutorial Code Starters
I created this repository so I could break the Wagtail tutorials down into steps that can be checked out using git.

To use this code, [clone this repository into a local directory](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository). You might want to run `git fetch --all` to make sure all the remote branches are downloaded.

 Then use `git checkout` to check out the repository branch you want to start with. For example, if you wanted to start on Step-3-blogindexpage, you would type:

 ```
 git checkout Step-3-blogindexpage
 ```

Follow the steps in the [Wagtail Getting Started tutorial](https://docs.wagtail.org/en/latest/getting_started/tutorial.html) to create a virtual environment and to install Wagtail in your local directory. You will also want to follow the steps for creating a super user.

When you run `python manage.py migrate` for the first time, a `db.sqlite3` file should be created and all the migrations from the step you checked out shoud be added to the database.