# MDB Angular Boilerplate

Free, responsive CRUD application starter with NgRx state management, Firebase backend and material design. Built with the newest Bootstrap 4, Angular 8 and MDBootstrap - powerful and free UI Kit, containing **400+** material UI elements, **600+** material icons, **74** CSS animations, SASS files, templates, tutorials and many more.

________

# Live Preview:
## https://ng-boilerplate.mdbootstrap.com/

# Technologies used

* Angular 8
* Bootstrap 4
* MDBootstrap Angular
* NgRx
* Firebase

# Most important features

* NgRx state management
* Real time updates with Firebase real time database
* Admin panel - manage user content
* Responsive design


# Installation:

**Firebase configuration:**
http://mdbootstrap.com/docs/angular/getting-started/boilerplate-installation

**Install:**
npm i

**Run:**
ng serve -o

**Test:**
ng test

**Production Build:**
ng build --prod


# FAQ
http://mdbootstrap.com/angular/faq/

# Documentation
https://mdbootstrap.com/docs/angular/

# Support:
http://mdbootstrap.com/forums/forum/support/


# Useful Links:

Getting started: https://mdbootstrap.com/angular/angular-bootstrap-getting-started/

5 min quick start: https://mdbootstrap.com/angular/mdb-quick-start/

Material Design + Bootstrap Tutorial: https://mdbootstrap.com/bootstrap-tutorial/

Material Design + WordPress Tutorial: https://mdbootstrap.com/wordpress-tutorial/

Other Freebies: https://mdbootstrap.com/freebies/

Premium Templates: https://mdbootstrap.com/templates/


# Social Media:

Twitter: https://twitter.com/MDBootstrap

Facebook: https://www.facebook.com/mdbootstrap

Pinterest: https://pl.pinterest.com/mdbootstrap

Google+: https://plus.google.com/u/0/b/107863090883699620484/+Mdbootstrap/posts

Dribbble: https://dribbble.com/mdbootstrap

LinkedIn: https://www.linkedin.com/company/material-design-for-bootstrap

# Visit our website: https://mdbootstrap.com/

# Get access to application admin panel

In our starter app, we added admin panel, in which you can manage users and their content. Admin panel is only visible to the users with special access.

In order to add admin access to your account, run our starter app with ng-serve command, go to Register section and create new account.

Then open your Firebase console, and from the sidenav menu select Database

Click on the plus icon to expand users list and copy user unique id to clipboard (you can expand user properties to make sure this is the account that should have access to admin panel)

Copy user id
Hover over project name and click on the plus icon to add new category. Add "admins" string to the name field and leave value field empty. Then click on the plus icon on the right to add new admin user. In name field paste the user unique id you copied from the users list, set value field to true and click add.

Add admin
When you open the starter application again, you should see "Admin panel" link in the navbar. You can now manage users content and add or remove admin privileges.
