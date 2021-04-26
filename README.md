# nanoHUB-StandardTool-template
This is a repository template for creating a standard nanoHUB tool, in other words, a Rappture or XTerm/ X11 tool.

Keep all of the folders and hidden files.  
.keep files are present to force git to track initially empty directories.
Should the directories become populated the .keep file can be removed.

There must be a top level directory named middleware and it must contain a shell script named {{{invoke}}}.  Code that must be compiled should reside in the top level directory named {{{src}}}.  The {{{src}}} should include a {{{Makefile}}} for building the tool.  Products of the build such as binary executables should be placed the top level directory named {{{bin}}}.  Additional top level directories such as {{{data}}} and {{{examples}}} are also typical but optional.

==> What else?

1) Click the green "Use this template" button to create a copy of this repository in your own GitHub account.
* Type in the name of your new repository. You can use your tool's nanoHUB shortname to make life easier.
* Select whether the repo will be public or private. Public is easier.
* Click the green button at the bottom to "create repository from template".

2) Go to your newly created repository and invite nanohub-apps as a collaborator to your repo.

3) Copy the link to clone the repo to nanoHUB (click the code download button).

3a) If your repository is public, you will use the https:// link to set up the connection with nanoHUB.
* Click the clipboard icon to copy the URL to the clipboard.

3b) If your repository is private, there are more steps:
* You will have to have an ssh key in nanoHUB and add the public key to your GitHub account. Instructions are here: https://nanohub.org/kb/tools/sshkeypair
* Use the private ssh:// link to set up the connection with nanoHUB.
==> I Forgot whether we have to wait for something here   * You need to invite nanohub-apps as a collaborator to your repo, in order to get the key to connect to nanoHUB.

4) Go to https://nanohub.org/tools/create to register your nanoHUB tool.
* In the section for Repository host, select "Host Git repository on GitHUB".
* In the section for Git Repository URL, paste in the link copied to the clipboard.
* For publishing option, select Standard Tool.

After you click the button to register your tool, you will be redirected to your tool's status page, and you will also receive an email with a link to the tool's project space in nanoFORGE.

[Include a link here to more complete instructions for building a Standard nanoHUB Tool.]
==> maybe this will be included in the above documentation: Before publishing your tool, you will need to update the invoke script in the middleware folder.
