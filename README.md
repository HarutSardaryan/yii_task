1.) Login functionality.
2.) User managment system, added 2 roles "editor" and "admin". Default user is "admin" user with following login/password   ------   admin/admin123. 
3.) Category menu item with add/edit/delete/view/manage functionality.
4.) Article menu item with add/edit/delete/view/manage functionality which is connected to category.
5.) User menu item with add/edit/delete/view/manage functionality for admin.
6.) Profile menu item which allows "editor" user to edit own profile.
7.) "editor" user can see own articles and categories. "Admin" user can access to everything.

Database consist of 3 tables (user, category, article) which reference with each other by foreign keys.
Need to create db user whit host: localhost, user: demo, password demo2015 and db name is yii_test.