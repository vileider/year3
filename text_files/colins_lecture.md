31.1.2024

# What are the advantages of full disk encryption? What are the disadvantages - if any?
- storing keys somewhere
- improve protection
- limit acces
- what happend if I lost a key
# Should it be used for laptops?
- why not?

## guest lecture by itself:
MFA is aone of authenication type
-QR codes
- autheticator on phone

Zero trust
- Assume firewall breached
- userid and password escaped
- Never trust, always verify
- implement least privilege
- Continuous verification
- Keep systems up to date

* Give someone the acces they need - and no more
- Can only update /etc/tcpip not /etc/pam
- Default should be no acces
* DB2 userid1 can acces data, userid2 can change table structure, but not read the data
* No superuser/administrator

# Making changes
* May need to have approval for sensitive changes
* No acces to the system
- update GITHUB
- request gets approved
- Github triggers process wchich cheks everything

# Updating Sensitive data
* Ask for MFA
- lasts for n minutes
* File is encrypted on disk
- Does your userid have acces to decription key?

# Acces to files
* Am I able to acces the files from outside database
* does a userid have superuser authority
* File is encripted

How to store data
* by numerical it will keep consitence of table

It is much better to use vairable name when sending a query to db

How to prevend bad SQL statements
- collect for 1 minute during random times of teh day
- check the statements

# Deeper into giving acces to db
* better to give groups acces 

# How do roles work
* More than just a group
* if logon userid USER1
* and from IP address
* and using TLS
* then get role HRROLE1

# How to protect a pdf file
* one department encripts pd using symetric key
* encrypt this key using department public key 
* end user runs program, uses private key to decript symetric key, decripts PDF, and displays it