<?php
$json = file_get_contents('php://input');
$data = json_decode($json, true);
echo "Username: admin" . $data['username'] ; 
"<br>";
echo "Password: 1234" . $data['password'];
 ?>
