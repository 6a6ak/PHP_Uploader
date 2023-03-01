# PHP_Uploader
Upload bash file to the server 
______________________________
You can save this code as a PHP file and place it in your web server's directory. When a user browses to this file, they will see a form that allows them to select a bash file from their computer and upload it to the server.

When the user submits the form, the PHP script will validate the uploaded file to ensure that it is a bash file, and then move it to the specified directory on the server (/var/www/html/ in this example).

Note that you may need to adjust the file upload size limit in your PHP configuration file (php.ini) if the files you want to upload are larger than the default limit.
