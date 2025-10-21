<?php
// 2. Declare a JSON string with name, age, and email
$jsonString = '{"name":"Maria","age":25,"email":"maria@example.com"}';
// 3. Use json_decode() to convert it into a PHP object and a PHP associative array
$phpObject = json_decode($jsonString);  // Converts to object
$phpArray = json_decode($jsonString, true);  // Converts to associative array
// 4. Display individual values (e.g., name and email) in both formats
echo "Object: " . $phpObject->name . "\n";
echo "Array: " . $phpArray['email'] . "\n";
?>
