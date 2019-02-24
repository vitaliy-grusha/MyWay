# MyWay
Give a shortname for your long-path directories and then access them easily.

# Instalation
1. Clone the repository 
2. Run: `chmod u+x gitrep`
3. Add alias to your .bashrc:
`alias gitrep='. /home/user/utils/GitRep/gitrep'`

Also you can add this alias:
`alias gitgo='. /home/user/utils/GitRep/gitrep go'`

# Usage 
1. Go to your long-path directory
2. Run `gitrep add <shortname>`

To change your directory on the attached to shortname, run `gitrep go <shortname>`.

if second alias is added, run `gitgo <shortname>`.

To see help, run `gitrep` or `gitrep help`.
