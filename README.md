# LawSum

## Setup on Mac

1. Install Docker https://hub.docker.com/editions/community/docker-ce-desktop-mac
2. Setup SSH on your github account: https://help.github.com/articles/adding-a-new-ssh-key-to-your-github-account/ 
3. Clone the repo: `git@github.com:LawSumAI/LawSum.git`
4. Initialise the submodules: `git submodule init`
5. Update the submodules: `git submodule update`
6. Build everything: `docker-compose build`
7. Launch everything: `docker-compose up`
8. Browse to `localhost` to see the magic!
