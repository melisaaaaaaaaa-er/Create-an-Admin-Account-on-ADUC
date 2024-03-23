# Create an Admin Account on ADUC

<img src="https://raw.githubusercontent.com/melisaaaaaaaaa-er/ADDS-images/main/24.png"/>

Right-click the _ADMINS OU → New → User

#
<img src="https://raw.githubusercontent.com/melisaaaaaaaaa-er/ADDS-images/main/25.png"/>

The new administrator account will have the name Jane Doe and the logon name jane-admin.

#
<img src="https://raw.githubusercontent.com/melisaaaaaaaaa-er/ADDS-images/main/26.png"/>

Give the account a password and uncheck the “User must change password at next logon” option. 

#
<img src="https://raw.githubusercontent.com/melisaaaaaaaaa-er/ADDS-images/main/27.png"/>

The new account can be seen in the _ADMINS OU.

#
<h3>Add jane-admin account to the Domain Admins group</h3>

<img src="https://raw.githubusercontent.com/melisaaaaaaaaa-er/ADDS-images/main/28.png"/>

Right-click the Jane Doe account → Properties

#
<img src="https://raw.githubusercontent.com/melisaaaaaaaaa-er/ADDS-images/main/29.png"/>

Select Member of → Add... → input  “Domain Admins” → Check Names → OK

<img src="https://raw.githubusercontent.com/melisaaaaaaaaa-er/ADDS-images/main/30.png"/>

Select Apply → OK

Jane Doe is now a member of the Domain Admins group, meaning she has full control over mydomain.local.

#
<img src="https://raw.githubusercontent.com/melisaaaaaaaaa-er/ADDS-images/main/31.png"/>

Select Apply → OK

<img src="https://raw.githubusercontent.com/melisaaaaaaaaa-er/ADDS-images/main/32.png"/>

Log off and log back into DC-1 using jane-admin.
