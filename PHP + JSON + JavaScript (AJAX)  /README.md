<?php
header('Content-Type: application/json');
$input = file_get_contents('php://input');
$data = json_decode($input, true);

$username = $data['username'] ?? 'Maria';
$response = array(
        'status' => 'Data Successfully Received',
        'message' => "Welcome, $username!"
);

echo json_encode($response);
?>
