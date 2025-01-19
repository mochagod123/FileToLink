# FileToLink
ファイルをURL化するためのライブラリ

使い方<br>
```
with open("filename.png", 'rb') as file:
    file_bytes = io.BytesIO(file.read())
    url = UploadFileIO(file_bytes "filename.png")
    print(url)
```
