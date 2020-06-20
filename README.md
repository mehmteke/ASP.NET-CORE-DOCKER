# ASP.NET-CORE-DOCKER

docker build -t consoleapp . (DockerFile dosyasını kullanarak image oluşturuldu)
docker create --name consoleapp-container consoleapp (Oluşan consoleapp image ını kullanarak container oluşturuyoruz.)
docker start consoleapp-container (Komutu ile container çalıştırıyoruz.)
docker attach consoleapp-container ile console çıktısını görebilirsiniz.
