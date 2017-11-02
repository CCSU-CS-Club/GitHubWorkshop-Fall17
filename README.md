# GitHubWorkshop-Fall17

## Order of events:

1. Set up GitHub accounts and install git and add access to the CS Club organization (~10 minutes)
   * ```git clone```
   * ```git checkout dev```
   * Create a new branch with team name
      1. For people making a new branch:
         * ```git checkout -b *NEW_BRANCH_NAME_WITH_NO_SPACES*```
         * Make a new folder with your Team's Name
         * Modify/Add stuff inside it
         * ```git add .```
         * ```git commit -m "What changed?"```
         * ```git push --set-upstream origin``` (first-time push only, ```git push``` afterwards)
      2. For people switching to their team's branch:
         * ```git checkout *BRANCH_NAME_THAT_IS_ALREADY_SET_UP*```
         * Then modify stuff and commit normally
   * ### Make sure to work on your team's branch. Ensure using ```git branch -r``` and your team name's branch should be highlighted or have a star before the name

2. Adding team names and team member names one-by-one to the ```Readme.md``` file (~15 minutes)
   * ```git pull```
   * ### Make sure to always pull before push whenever working in a collaborative environment
   * Modify readme.md
   * ```git add .```
   * ```git commit -m "Added XYZ name to the Readme file"```

3. Create a java program for asking user for two numbers and display ```x+y```, ```x-y```. ```x*y```, ```x/y``` (integer division), ```x/y``` (double division) (~30 minutes)
   * Define your architecture (number of classes, methods, etc.)
   * Split up responisibility for different parts of the project
   * Code
   * Commit the code at clear checkpoints in the code. For eg, commit after having ```x+y``` working
   * ### Trick to commit is to commit as frequently as possible, but only commit code that works entirely and doesn't break the application. This means don't commit halfway through writing a line of code (LOC)

4. Create pull requests from your branch to the dev branch (~15 minutes)
   * Go to GitHub repo containing this code
   * Click on ```New Pull Request```
   * Set the ```base:``` to ```dev``` and ```compare:``` to ```TEAM_NAME_BRANCH```
   * Set an appropriate Merge Request Title describing what all the commits do, and write a comment if needed.
   * Inform us so we can take a look at the Pull Request, make comments on it, etc.
   * We will merge if everything is correct, otherwise we will suggest modfications that you should do and commit to your team's branch. These modifications will automatically get added to the PR, and then we'll ```merge``` your team's branch to dev.

5. ### If you run into Merge conflicts, which you hopefully should, please talk to one of the mentors to resolve it!

6. ### Talk to us if you want to learn about rollbacks, etc. that are not being discussed here.


## Contributors:

### TEAM NAME

* Tobias Rittgers
* TEAM MEMBER
