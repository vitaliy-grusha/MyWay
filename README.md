# MyWay
Give a shortname for your long-path directories and then access them easily.

# Instalation
1. Clone the repository 
2. Run: `chmod u+x myway`
3. Add alias to your .bashrc:
`alias myway='. /home/user/utils/MyWay/myway'`

Also you can add this alias:
`alias waygo='. /home/user/utils/MyWay/myway go'`

# Usage 
1. Go to your long-path directory
2. Run `myway add <shortname>`

To change your directory on the attached to shortname, run `myway go <shortname>`.

if second alias is added, run `waygo <shortname>`.

To see help, run `myway` or `myway help`.
