# Saving Contacts App

This is a Swift app that demonstrates sending of data from the application to a web server. It is a personal contact list app, where the user can make new entries with details about one's telephone contacts.

## Details of the application
The user can send 2 kinds of data : Name & Phone numbers (as String/text) and contact images (binary data). The uploaded image is saved in a folder on the server. The database, also on server, saves contact name, phone number and the corresponding image file path location.

![app](https://github.com/d-misra/Swift-Apps/blob/master/Project%203%20-%20Image%20%26%20data%20to%20Server/Thumbnail.png)

## Topics covered
- Making HTTP request in Swift with [URLRequest](https://developer.apple.com/documentation/foundation/urlrequest)
- Sending Swift data as JSON objects [JSONSerialization](https://developer.apple.com/documentation/foundation/jsonserialization)
- Server side database handling & storage using PHP (code included above)

## Database view

![db](https://github.com/d-misra/Swift-Apps/blob/master/Project%203%20-%20Image%20%26%20data%20to%20Server/Db.png)

## Help

- PHP [documentation](https://www.php.net/)
- Insert data in mysql database using PHP [link](https://www.w3schools.com/php/php_mysql_insert.asp)