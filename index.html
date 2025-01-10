<?php
// URL API
$apiUrl = "https://www.unisbank.ac.id/ojs/index.php/fti1/api/v1/submissions/9889";

// Ambil data JSON dari API
$jsonData = file_get_contents($apiUrl);

// Dekode JSON menjadi array
$data = json_decode($jsonData, true);

// Pastikan data berhasil diambil
if ($data) {
    // Validasi data
    $title = isset($data['title']['id_ID']) && $data['title']['id_ID'] !== '' ? $data['title']['id_ID'] : "No title available";
    $authors = isset($data['authorString']) && $data['authorString'] !== '' ? $data['authorString'] : "No authors available";
    $datePublished = isset($data['datePublished']) && $data['datePublished'] !== '' ? $data['datePublished'] : "No published date available";
    $articleUrl = isset($data['urlPublished']) && $data['urlPublished'] !== '' ? $data['urlPublished'] : "#";

    // Tampilkan dalam format HTML
    echo "<!DOCTYPE html>
    <html lang='en'>
    <head>
        <meta charset='UTF-8'>
        <meta name='viewport' content='width=device-width, initial-scale=1.0'>
        <title>Article Details</title>
        <style>
            body {
                font-family: Arial, sans-serif;
                line-height: 1.6;
                margin: 20px;
            }
            .article {
                border: 1px solid #ddd;
                padding: 15px;
                border-radius: 5px;
                box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            }
            .article h2 {
                color: #333;
            }
            .article a {
                color: #007BFF;
                text-decoration: none;
            }
            .article a:hover {
                text-decoration: underline;
            }
        </style>
    </head>
    <body>
        <div class='article'>
            <h2>$title</h2>
            <p><strong>Authors:</strong> $authors</p>
            <p><strong>Published Date:</strong> $datePublished</p>
            <p><a href='$articleUrl' target='_blank'>Read Full Article</a></p>
        </div>
    </body>
    </html>";
} else {
    // Jika data gagal diambil, tampilkan pesan kesalahan
    echo "Failed to fetch data from API.";
}
?>
