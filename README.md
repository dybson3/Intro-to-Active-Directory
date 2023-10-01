# Intro-to-Active-Directory
I guided project implemented on HackTheBox Academy.

It wasn't possible to show everything I done in lab so it's a summary of what I have done.

**Task 1 - Manage Users**

I had to manage following users:

![image](1.png)

![image](2.png)

![image](3.png)

So I started adding users:

![image](4.png)

I used a Windows PowerShell to add first user.

Next users I added using Active Directory GUI:

![image](5.png)

![image](6.png)

![image](7.png)

I changed the settings that users have to change their passwords at next logon.

Now I am gonna remove users using GUI:

![image](8.png)

By clicking "Delete" I will delete user "Paul Valencia".

![image](9.png)

Next I will reset Adam's password:

![image](10.png)

Using "reset password" I was able to reset Adam's password.

I also unlocked his account:

![image](11.png)

**Task 2 - Manage Groups and Other Organizational Units**

Ss of my task:

![image](12.png)

Let's get to creating new Organization Unit (OU):

![image](13.png)

I am choosing "Organization Unit".

Then I clicked New -> Group and created new group. I chose a "Domain local" scope for this group and clicked "Security group".

![image](14.png)

After this I added previously added workers to this group:

![image](15.png)

**Task 3 - Manage Group Policy Objects**

![image](16.png)

I got to Group Policy Management Editor:

![image](17.png)

Then I changed Removable Storage Access settings:

![image](18.png)

I configured "Deny all access" for all Removable Storage Classes.

After this I enabled all setting for Interactive Logon.

Using following command I connected Group Policy Object to the group created before.

![image](19.png)

**Task 4 - Add Computer to the Domain**

It was a short task. Using Control Panel I added my computer to the domain "INLANEFREIGHT.LOCAL":

![image](20.png)

That's everything. This guided labs were only part of the module on HackTheBox Academy. It was preceded by a lot of theory.

Thank you for following to the end! :D
