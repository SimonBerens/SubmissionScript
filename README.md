# SubmissionScript
Script that automatically submits your project to for Systems or Graphics

## How to use
##### READ THE DIRECTIONS AT THE TOP OF THE FILE
Edit the variables above the "Do not modify!" appropriately

For one time use:
```
cd ~
mkdir bin
cp <wherever you cloned it>/SubmissionScript/submit ~/bin
export PATH=$PATH:~/bin
```
For access at all times:

Append 
```
cp <wherever you cloned it>/SubmissionScript/submit ~/bin # (for if you decide to git pull)
export PATH=$PATH:~/bin
```
to your ~/.bashrc

After setup, just type `submit` in the github repo you want to submit
