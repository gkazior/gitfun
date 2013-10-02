# first commit

        git add command.txt
        git commit -m "added a file command.txt"
        git push origin master


# clone

        mkdir tmp
        cd tmp
        git clone git@github.com:gkazior/gitfun.git
        cd gitfun
        git branch -a

        * master
        remotes/origin/HEAD -> origin/master
        remotes/origin/master

# merge (fetch+merge)

        git fetch

        $ gs
        # On branch master
        # Your branch is behind 'origin/master' by 1 commit, and can be fast-forwarded.
        #

        git merge origin/master
        git push

# merge (pull)

        git pull
        gs

        $ gs
        # On branch master
        nothing to commit (working directory clean)

# git fix

        git branch fix-01
        git checkout fix-01
        # edit this file first commit
        # edit this file second commit

# doc

        http://www.gitguys.com/topics/tracking-branches-and-remote-tracking-branches/
