

# Install Python & AWS CLI
sudo apt-get update && sudo apt-get install -y python-dev python3-dev && sudo pip install awscli

# Configure AWS
aws configure


# Adding auto completer to your bash file:

which aws_completer
complete -C '/usr/local/bin/aws_completer' aws

echo "complete -C '/usr/local/bin/aws_completer' aws" >> ~/.bashrc


# Add additional AWS config settings via:
aws configure --profile <some_name>

Will add the new profile as a stanza to your ~/.aws/config and ~/.aws/credentials

(See: https://docs.aws.amazon.com/cli/latest/userguide/cli-multiple-profiles.html)

# Before you use git push, you might need to switch to using ssh vs using https.
(previously: url = https://github.com/qwkhyena/AWS-Pipeline-cfn-with-multiple-source-repos.git)
git remote set-url origin git@github.com:username/repo.git