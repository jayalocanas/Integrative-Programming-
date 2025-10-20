<?php
// Declare an associative array with keys: name, age, and course
$student = array(
    "name" => "Maria",
    "age" => 21,
    "course" => "IT"
);
$jsonString = json_encode($student);
echo $jsonString;
?>






