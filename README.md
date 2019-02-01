# SubmissionScript
Script that automatically submits your project to for Systems or Graphics

## How to use
##### READ THE DIRECTIONS AT THE TOP OF THE FILE
Edit the variables above the "Do not modify!" appropriately

For one time use:
```
git clone https://github.com/SimonBerens/SubmissionScript
mkdir ~/bin # can fail if exists
cp SubmissionScript/submit ~/bin
export PATH=$PATH:~/bin
```
For access at all times:

Append 
```
cp <root path>/submit ~/bin # (for if you decide to git pull)
export PATH=$PATH:~/bin
```
to your ~/.bashrc

After setup, just type `submit` in the github repo you want to submit
