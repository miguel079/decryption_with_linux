<h1>Decryption with Linux Lab</h1>

<h2>Description</h2>
In this lab we're going to walk through some cryptographic activities using Linux commands to decrypt files and reveal hidden messages.

<br/>


<h2>Languages and Utilities Used</h2>

- <b>Linux</b> 

<h2>Environments Used </h2>

- <b>Google Qwiklabs</b>

<h2>Program walk-through:</h2>

<p align="center">

Use the ls command to list the files in the current working directory:  <br/>
<img src="https://i.imgur.com/jmERNtE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

Use the cat command to list the contents of the README.txt file: <br/>
<img src="https://i.imgur.com/vabYE3O.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

Using the cd command to change to the caesar subdirectory of your home directory and listing all files (including hidden ones): <br/>
<img src="https://i.imgur.com/JC2fTTD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

Using the cat command to list the contents of the .leftShift3 file: <br/>
<img src="https://i.imgur.com/2Yq5YyI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

Decrypting the .leftShift3 file with the command tr "d-za-cD-ZA-C" "a-zA-Z", which translates all the lowercase and uppercase letters in the alphabet back to their original position. The first character set, indicated by "d-za-cD-ZA-C", is translated to the second character set, which is "a-zA-Z": <br/>
<img src="https://i.imgur.com/PDOay4l.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

Back in the home directory, using the command revealed in the previous task to decrypt the encrypted file: <br/>
<img src="https://i.imgur.com/6q45756.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

Using the ls command to list the contents of your current working directory again.
The new file Q1.recovered in the directory listing is the decrypted file and contains a message: <br/>
<img src="https://i.imgur.com/4OxZE1g.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
