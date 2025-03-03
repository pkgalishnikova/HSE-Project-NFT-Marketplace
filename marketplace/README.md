## Запуск маркетплейса с помощью Docker

1. Скачайте с Google Drive файл nft_marketplace_1.tar по ссылке:
   <https://drive.google.com/file/d/1DzJOymX7_dT2sKEsTW0s944y6vlsRJD_/view?usp=sharing>
2. В терминале из директории, которая содержит файл marketplace14transfer.tar, запустите команду:
   ```docker load --input nft_marketplace_1.tar```
  Файл появится в разделе Containers в приложении Docker Desktop.
4. В приложении Docker Desktop откройте терминал и введите команду
   ```docker run -p 3000:3000 nft_marketplace_1```

