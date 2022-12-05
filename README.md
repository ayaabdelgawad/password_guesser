# Password Guesser

The meaning of "Secure Password" to a lot of Administrators / users is not to use a dictionary password. However, passwords are often set with a pattern like "Usern@m3@12345". Now, it is really hard to manually guess these kinds of passwords during a penetration testing.

Password Guesser accepts a set of keywords, generate a few possible weak passwords and create a wordlist. This can be used as a custom wordlist for cracking online passwords or offline hash cracking.

Blogpost describing the importance of password guessing: https://medium.com/@ayman.abdul.kareem/the-art-of-password-guessing-19725a17afc2?sk=e23723ae4c959e09fc672b5f15fd112a

<b>Usages:</b><br/>

The expected call takes the format 

`python password_guesser.py [output file name] [list of keywords]`

See list below for examples

<ul>
	<li>python password_guesser.py password_wordlist.txt mysql<br /></li>
	<li>python password_guesser.py password_wordlist.txt mysql admin john<br /></li>
	<li>python password_guesser.py password_wordlist.txt mysql "tomcat admin" "jboss admin" backup_user<br /></li>
</ul>
	
![Image description](https://github.com/imnkrm/password_guesser/blob/master/1.png)<br />
![Image description](https://github.com/imnkrm/password_guesser/blob/master/2.png)<br />
![Image description](https://github.com/imnkrm/password_guesser/blob/master/3.png)<br />

Note, images shown above do not include output file's name since they are from an earlier version.
