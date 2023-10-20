<!DOCTYPE html>
<html>
<head>
    <title>PDF File Upload</title>
</head>
<body>
    <h1>Upload a PDF File</h1>
    <form action="upload.php" method="post" enctype="multipart/form-data">
        <input type="file" name="pdfFile" accept=".pdf" />
        <input type="submit" value="Upload PDF" />
    </form>
</body>
</html>
