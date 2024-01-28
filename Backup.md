 - name: Install Git-Repo
      run: |
        mkdir ~/bin
        curl https://storage.googleapis.com/git-repo-downloads/repo > ~/bin/repo
        chmod a+x ~/bin/repo
        sudo ln -sf ~/bin/repo /usr/bin/repo

