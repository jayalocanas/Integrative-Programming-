<?php
$json = '{"username":"admin",
"password":"1234"}';
$data = json_decode($json, true);

echo "Username: " . 
$data['username'] ; 
"<br>";
echo "
Password: " . $data['password'];
 ?>
