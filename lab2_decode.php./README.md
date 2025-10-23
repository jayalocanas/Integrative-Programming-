<?php
$jsonString = '{"name":"Maria","age":25,"email":"maria@example.com"}';
$phpObject = json_decode($jsonString);
$phpArray = json_decode($jsonString, true); 

echo "Object: " . $phpObject->name . "\n";
echo "Array: " . $phpArray['email'] . "\n";
?>
