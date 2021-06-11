# Experimenting with GitHub Actions

Makes automated commits from Github actions & using cron make it work.

## Using this 
Click on the `Use this template` to import the repository to your GitHub, you can modify the following lines in [commit.yml](https://github.com/Mleng89/commit-test/blob/main/.github/workflows/commit.yml)

- Line 9: `- cron: '0 7-11 * * *'` Change this to alter the frequency of commits. [Cron syntax](https://crontab.guru/)
- Line 27: `git config --local user.email "YOUR-GITHUB-EMAIL"` 
- Line 29: `git config --local user.name "YOUR-GITHUB-USERNAME"`

### Turning it off
Go into the repository's settings tab and select Actions, then check off `Disable Actions`  
