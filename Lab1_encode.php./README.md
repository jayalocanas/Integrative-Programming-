<?php
// Declare a PHP assiociative array with keys: name, age, and course
$array = array(
    "name" => "Maria",
    "age" => 21,
    "course" => "IT"
    );
    
    // Use json_encode() to convert the array to a JSON string
    $jsonString = json_encode($array);
    
    // Output the Json string in the browser
    echo $jsonString;
?>
