# GitRep
Give a shortname for your long-path repositories and then access them easily.

# Instalation
1. Clone the repository 
2. Run: `chmod u+x gitrep`
3. Add alias to your bash.bashrc:
`alias gitrep='. /home/user/utils/GitRep/gitrep'`

Also you can add this alias:
`alias gitgo='. /home/user/utils/GitRep/gitrep go'`

# Usage 
1. Go to your long-path repository
2. Run `gitrep add <shortname>`

Then you can run `gitrep go <shortname>` to change your directory on the attached to shortname.

Or you can print `gitgo <shortname>`, if second alias is added
