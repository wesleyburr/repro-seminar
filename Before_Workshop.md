---
output:
  word_document: default
  html_document: default
  pdf_document: default
---
## Seminar on Reproducibility

### Local Installation

Before the workshop, if you want to work on your own computer and your
own file system, you should complete the following steps.

1.  Update your version of R locally to at least 4.0, preferably
    [4.2.0](https://cran.r-project.org/) or later.
2.  Update your version of RStudio locally to at least 2022.02, to match
    the flow we will show.
3.  Install Git locally ([Windows](https://git-for-windows.github.io/);
    [Mac](https://ubc-mds.github.io/resources_pages/install_ds_stack_mac/#git/) - note that
    all you need to do are the first 3 steps).
4.  Register for a GitHub account. This is intended as a
    **professional** account, so consider [reading this
    guide](https://happygitwithr.com/github-acct.html) to help with
    account name selection and details on account types.

![GitHub signup](img/github_signup.png?raw=true "GitHub Signup")

5.  Set up a SSH public/private key pair. Keys provide a more secure way
    of communicating / connecting across the internet than using
    passwords, and are **required** for GitHub use.

Because this key creation can vary so much across different platforms,
we suggest you use RStudio's built-in utility to do it. Go to Tools \>
Global Options...\> Git/SVN \> Create RSA Key.

![RStudio Create RSA
Key](img/create_RSA.png?raw=true "RStudio RSA Key Creations")

RStudio prompts you for a passphrase: if you're completely new at all
this, skip the passphrase. Click "Create"" and RStudio will generate an
SSH key pair, stored in the files \~/.ssh/id_rsa and \~/.ssh/id_rsa.pub.
The \~ is a "home" directory, which varies by architecture, but is
universal and can simply be used.

Then, RStudio should have an option in that same screen (under Git/SVN),
to "View Public Key". Do that, and accept the offer to copy to your
clipboard.

Go back to GitHub, where you created your account. Click on your profile
pic in upper right corner and go to Settings \> SSH and GPG keys. Click
"New SSH key". Paste your public key in the "Key" box. Set a title, then
click "Add SSH key". This will let your computer (or account on the
server) communicate seamlessly with GitHub, and will be necessary for
each account you want to use on each computer.

## And Now You're Ready

You've updated RStudio and R (or are using the server), have a GitHub
account and SSH key, and you're ready for us to help you set up the
later stages.

If you want to check to see that everything is installed, try this:

1.  In RStudio, click File \> New Project. Do you see an option to
    create from Version Control? If yes, good.
2.  Select New Directory \> Empty Project. Do you see a checkbox "Create
    a git repository"? If yes, good, CHECK IT.

If these aren't correct, please feel free to reach out for help!
