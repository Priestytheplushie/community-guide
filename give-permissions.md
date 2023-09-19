# Give Permissions to users

This guide will cover how to give users moderator or custom permissions using pfpmyadmin

1. Open phpMyAdmin and log in
2. Select the database starting with "gdps_"
3. Look for "roles"
4. Open the Insert Tab
5. Fill in these things
      • roleID: The ID of the role
      • priority: the priority the role has over other roles
      • roleName: the name of the role (Note: it will not display im game)
6. setup your pernissions, the table below explains them (NOTE: Set **1** to grant the permission and **0** to revoke them

## Permissions

| Permission  | Description |
| ------------- | ------------- |
| CommandRate  | Allows you to use the !rate command |
| Content Cell  | Content Cell  |