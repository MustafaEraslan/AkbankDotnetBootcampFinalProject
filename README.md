# AkbankDotnetBootcampFinalProject

Kurulum:

git clone https://github.com/omerbilalusta/VB-Bootcamp.git

Veritabanını kurulumunu tamamlamak:
.\VB-Bootcamp\API> dotnet ef database update --project  "./Vb-Data" --startup-project "./Vb-Api"

Projeyi çalıştırmakiçin:
.\VB-Bootcamp\API\Vb-Api> dotnet run
"dotnet restore" komutu ile paketlerin kurulumu garanti edilmelidir.
5082 portuyla http://localhost:5082 üzerinden API çalışmaktadır.
