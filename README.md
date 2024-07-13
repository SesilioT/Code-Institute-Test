<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Music Upload</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Nice Boyz</h1>
    </header>
    <main>
        <section class="upload-section">
            <form action="/upload" method="post" enctype="multipart/form-data">
                <label for="musicUpload">Choose a music file:</label>
                <input type="file" id="musicUpload" name="musicFile" accept="audio/*" required>
                <button type="submit">Upload</button>
            </form>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Music Uploader</p>
    </footer>
</body>
</html>

