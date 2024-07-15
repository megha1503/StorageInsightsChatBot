# Adding storage systems

Before you begin, ensure that you have the Administrator role in IBM Storage Insights. 

## Adding a user

To add a single user, complete the following steps:

1.  In the menu bar, hover over your user name and click **Manage Users**.
2.  On the My IBM website, click **Manage** for IBM Storage Insights.
3.  Click **Manage users**.
4.  Click **Add new user**.
5.  Provide a first name, last name, and email address or IBM ID. Typically, the email address and IBM ID are identical.
6.  Assign the **Subscription administrator** or **License user** role to determine their level of access in IBM Storage Insights.

##   

## Adding multiple users

To add multiple users at the same time, complete the following steps:

1.  In the menu bar, hover over your user name and click **Manage Users**.
2.  On the My IBM website, click **Manage** for IBM Storage Insights.
3.  Click **Manage users**.
4.  Click **Add multiple users**.
5.  Download the CSV (comma-separated values) sample file.
6.  In the CSV file, include information about the users that you want to add. For each user, you must provide a first name, last name, and email address or IBM ID. Typically, the email address and IBM ID are identical. You must also assign the Subscription administrator or License user role to determine their level of access in IBM Storage Insights.

*   If you're viewing the CSV file as a spreadsheet, enter information about each user in the appropriate columns. To assign the Subscription administrator role, type x in the **Admin** column for the user; to assign the License user role, type x in the **User** column.
*   If you're viewing the CSV as a text file, include information about each user on separate lines. Use the following format: "First\_name","Last\_name","Email or IBMid", User, Admin, Status
*   Where:
*   `User` represents a License user.
*   `Admin` represents a Subscription administrator.
*   `Status` is set to Active or Inactive.

For example, to add Jane Doe with the Subscription administrator role and John Doe with the License user role, include the following information:

*   "Jane","Doe","username@example.com",,x,Active
*   "John","Doe","username2@example.com",x,,Active

7.  To upload the updated CSV file, click **Select file** and follow the prompts.
8.  Click **Submit**.

## Removing users and assigning roles

*   To remove a user, expand the user information and select the remove action. When users are removed, they will no longer have access to IBM Storage Insights.
*   To change the role of a user, you must first remove the user. Then, re-add the user and assign the new role. You can also open a support case at [https://www.ibm.com/mysupport/](https://www.ibm.com/mysupport/) to request a role change.
*   **Roles and access rights**
*   Users in IBM Storage Insights are assigned roles. Roles determine the level of access that users have to product features. There are two roles in IBM Storage Insights: Administrator (Subscription administrator) and Monitor (License user)

