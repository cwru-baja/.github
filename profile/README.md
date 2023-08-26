# CWRU Motorsports

Hi! Welcome to the CWRU Motorsports Github Organization. This readme serves as a guide to get started with a few things.

## Git Configuration

On CWRU Motorsports, we entirely use SSH cloning for our repositories.
This makes managing access to our repositories, tracking users, and keeping our private data private easy.

To get started with SSH cloning, we recommend you follow [this guide.](https://docs.github.com/en/authentication/connecting-to-github-with-ssh)

In addition to this, we recommend that you reconfigure your git client to rebase instead of merging. We also recommend you prune on every fetch.
You can do this with the following shell command on macOS or Linux:

```console
$ git config --global pull.rebase true
$ git config --global fetch.prune true
```

Finally, don't forget to set your name and email address. We recommend using your name on your Google account or Discord, and the email address associated with your Github account.
The commands to do this are as follows:

```console
$ git config --global user.name "<firstname> <lastname>"
$ git config --global user.email "<github account email>"
```

