## Запуск маркетплейса с помощью Docker

1. Скачайте с Google Drive файл app-1-image.tar по ссылке: [<https://drive.google.com/drive/folders/1Lv7sW_-4DovdejO9KlFRD7jGHFHMrUQS?usp=sharing>](https://drive.google.com/file/d/1QhxXeBzOiNRDHlWPcwDsSiHnX8_fnHW0/view?usp=sharing)
2. В терминале из директории, которая содержит файл app-1-image.tar, запустите команду:
   ```docker load --input app-1-image.tar```
  Файл появится в разделе Containers в приложении Docker Desktop.
3. В приложении Docker Desktop откройте терминал и введите команду
   ```docker run -p 3000:3000 app-1-image```

