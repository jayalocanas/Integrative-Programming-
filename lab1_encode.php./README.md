<?php
// Declare an associative array with keys: name, age, and course
$student = array(
    "name" => "Maria",
    "age" => 21,
    "course" => "IT"
);

// Use json_encode() to convert the array to a JSON string
$jsonString = json_encode($student);

// Output the JSON string in the browser
echo $jsonString;
?>






