# learn-git
started out as files used while learning git but included files/pages for other applications under the same structure.

# .gitignore
*.zip
images/
explore_california/
first_git_project/
lynda_version/*.zip
images/
explore_california/
first_git_project/
lynda_version/
demo_repo/
collaborator_demo_repo/
*.diff
patches/

# .git/config
[core]
        repositoryformatversion = 0
        filemode = false
        bare = false
        logallrefupdates = true
        symlinks = false
        ignorecase = true
[remote "origin"]
        url = https://github.com/Wishn4Fishn/learn-git.git
        fetch = +refs/heads/*:refs/remotes/origin/*
[branch "master"]
        remote = origin
        merge = refs/heads/master
[user]
        email = curt.weaver@gmail.com

# ~/.gitconfig
[gui]
        recentrepo = C:/workspace/qa/cm
[user]
        name = curt weaver
        email = curt.weaver@concur.com
[color]
        ui = true
[core]
        editor = notepad.exe
[alias]
        br = branch
        co = checkout
        ci = commit
        df = diff
        dfs = diff --staged
        logg = log --graph --decorate --oneline --all
        log1 = log --oneline
        st = status
