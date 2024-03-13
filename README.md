# Create an Admin Account on ADUC

![24](https://github.com/melisa-er/Create-an-Admin-Account-on-ADUC/assets/157723219/9bac76d4-5257-4f12-8e71-d22dceca313b)

Right-click the _ADMINS OU → New → User

#
![25](https://github.com/melisa-er/Create-an-Admin-Account-on-ADUC/assets/157723219/47a38d96-fca8-446b-bdbe-678f4525668a)

The new administrator account will have the name Jane Doe and the logon name jane-admin.

#
![26](https://github.com/melisa-er/Create-an-Admin-Account-on-ADUC/assets/157723219/90a6242d-b524-4d81-848a-8e946734bee3)

Give the account a password and uncheck the “User must change password at next logon” option. 

#
![27](https://github.com/melisa-er/Create-an-Admin-Account-on-ADUC/assets/157723219/635ee66f-b7bc-4f87-9251-e51dd5337f63)

The new account can be seen in the _ADMINS OU.

#
<h3>Add jane-admin account to the Domain Admins group</h3>

![28](https://github.com/melisa-er/Create-an-Admin-Account-on-ADUC/assets/157723219/ad0c4be9-6c9d-46ef-86db-e57709077ef6)

Right-click the Jane Doe account → Properties

#
![29](https://github.com/melisa-er/Create-an-Admin-Account-on-ADUC/assets/157723219/94faa478-00e7-4739-b5b4-73f4a1e34c94)

Select Member of → Add... → input  “Domain Admins” → Check Names → OK

![30](https://github.com/melisa-er/Create-an-Admin-Account-on-ADUC/assets/157723219/7a913ecf-a008-468e-b4ff-47df252f20ad)

Select Apply → OK

Jane Doe is now a member of the Domain Admins group, meaning she has full control over mydomain.local.

#
![31](https://github.com/melisa-er/Create-an-Admin-Account-on-ADUC/assets/157723219/c280c99f-0ec7-4a41-8c04-1316dcb2d6ea)

Select Apply → OK

![32](https://github.com/melisa-er/Create-an-Admin-Account-on-ADUC/assets/157723219/e37a6108-cbb4-436e-9ac1-2d385667293d)

Log off and log back into DC-1 using jane-admin.
