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

```
git clone https://github.com/SimonBerens/SubmissionScript
mkdir ~/bin # can fail if exists
echo "cp ${PWD}/SubmissionScript/submit ~/bin; export PATH=${PATH}:~/bin" >> ~/.bashrc
```

After setup, just type `submit` in the github repo you want to submit
