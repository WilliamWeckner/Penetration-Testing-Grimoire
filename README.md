# OSCP-tools
Custom Tools, Cheat Sheets, and Notes from my OSCP PWK experience. A lot of the OSCP training is left up to the user. The video and PDF materials are just enough to whet the pentester's appetite to want to learn more. During my studies and labs, I decided to start making notes of these since I won't be using them on a daily basis.

## Recon Tools
These are custiom scripts or tools that I whipped up during the lab training. 
* *Robots.txt.test.sh* - This tool will grab the robots.txt file and run through each entry to display the HTTP status of the file.
  * Run with `chmod +x robots.txt.test.sh && ./robots.txt.test.sh`
* *ntlm-bf.sh* - This tool will loop through a text file and try every password with the username of "admin"
  * Run with `chmod +x bf.sh && ./bf.sh (URI) (PATH TO WORD LIST) (UID)`

## Cheat Sheets
These sheets should be used for quick reference during the exam. 
* [*msdos-post-exploitation.md*](https://github.com/weaknetlabs/OSCP-tools/blob/master/msdos-post-exploitation.md) - This cheat sheet contains all post-exploitation processes used during my penetration tests
