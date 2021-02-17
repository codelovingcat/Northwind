# NorthWind
## Introduction:
Northwind, SQL Server için Microsoft tarafından oluşturulan Database şemasıdır, orijinal NorthWind https://northwinddatabase.codeplex.com/ adresinde depolanmıştır, ancak bu yakında sona erdirilecektir, bu nedenle burada bir yedekleme yapmaya değer.

## Referanslar
1. http://www.bradoncode.com/tutorials/learn-mean-stack-tutorial/ 
2. https://github.com/tmcnab/northwind-mongo
  SQL'den CSV'ye ve ardından mongoDB'ye dönüştürün
3. https://github.com/dalers/mywind <== mysql formatına dönüştürüldü (Benim için çalıştı)
4. 

## DB Schema
   ![Alt](/images/Northwind.png "Title")
   
## https://northwinddatabase.codeplex.com/releases/view/71634
Northwind.bak.zip - Sql Server 2005 ve 2008 için Northwind veritabanı yedeklemesi.
Dosyayı açın / sıkıştırmasını açın, ardından veritabanını geri yüklemek için Sql Server Management Studio 2005 / 2008'den Veritabanını Geri Yükle seçeneğini kullanın

Northwind.sql.zip - - Sql Server 2005 ve 2008 için Northwind veritabanı oluşturma komut dosyası.
Ardından Sql Sunucunuzda northwind adlı bir veritabanı oluşturun.
Dosyayı açın / sıkıştırmasını açın, ardından sql dosyasını Sql Server Management Studio 2005 / 2008'de açın ve F5'e basın.
VEYA
aşağıdaki komutu çalıştırın (örnek)
sqlcmd -S Localhost -d Northwind -i D:\Sql\Northwind.sql
