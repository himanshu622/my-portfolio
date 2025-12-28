<?php

$method = $_SERVER['REQUEST_METHOD'];
$message = "";
$c = true;

$project_name = "Himanshu Sharma Portfolio";
$admin_email  = "himanshush0055@gmail.com"; // 👈 yaha mail aayega
$form_subject = "Website Form Enquiry";

if ($method === 'POST') {
    foreach ($_POST as $key => $value) {
        if ($value != "") {
            $message .= "
            " . (($c = !$c) ? '<tr>' : '<tr style="background-color:#f8f8f8;">') . "
                <td style='padding:10px;border:1px solid #e9e9e9'><b>$key</b></td>
                <td style='padding:10px;border:1px solid #e9e9e9'>$value</td>
            </tr>";
        }
    }
}

$message = "<table style='width:100%'>$message</table>";

function adopt($text) {
    return '=?UTF-8?B?' . base64_encode($text) . '?=';
}

$headers = "MIME-Version: 1.0\r\n";
$headers .= "Content-Type: text/html; charset=UTF-8\r\n";
$headers .= "From: ".adopt($project_name)." <".$admin_email.">\r\n";
$headers .= "Reply-To: ".$admin_email."\r\n";

mail($admin_email, adopt($form_subject), $message, $headers);