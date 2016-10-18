Configuring AWS Code Commit (Git) locally
---

```
Goto your HOME directory
Unzip the given 'ssh.zip'

// If Linux/Mac instance perform this
chmod 600 .ssh/config
chmod 600 .ssh/codecommit_rsa
```

Now lets test to verify it works by running this command in 'Git Bash'.

```
ssh git-codecommit.us-east-1.amazonaws.com
```

You should see.
---
You have successfully authenticated over SSH. You can use Git to interact with AWS CodeCommit. Interactive shells are not supported.Connection to git-codecommit.us-east-1.amazonaws.com closed by remote host.
