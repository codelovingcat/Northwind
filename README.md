![image](https://user-images.githubusercontent.com/36550960/108276675-dc420980-7180-11eb-9519-d6d0a1432388.png)
# Northwind <img src="https://user-images.githubusercontent.com/36550960/108275775-80c34c00-717f-11eb-9fc2-6f768118c808.png?raw=true"  width="40" height="40  image"/>
## Introduction:
Northwind, SQL Server için Microsoft tarafından oluşturulan database şemasıdır, orijinal Northwind https://northwinddatabase.codeplex.com/ adresinde depolanmıştır, ancak bu yakında sona erdirilecektir, bu nedenle burada bir yedekleme yapmaya değer.

## Referanslar 
1. http://www.bradoncode.com/tutorials/learn-mean-stack-tutorial/ 
2. https://github.com/tmcnab/northwind-mongo
  SQL'den CSV'ye ve ardından mongoDB'ye dönüştürün
3. https://github.com/dalers/mywind  mysql formatına dönüştürüldü (Benim için çalıştı)


## Database Schema
  ![Northwind](https://user-images.githubusercontent.com/36550960/108241138-2f519780-7154-11eb-9bd4-010e6972155a.png)
   
## https://northwinddatabase.codeplex.com/releases/view/71634
Northwind.bak.zip - Sql Server 2005 ve 2008 için Northwind veritabanı yedeklemesi.
Dosyayı açın / sıkıştırmasını açın, ardından veritabanını geri yüklemek için Sql Server Management Studio 2005 / 2008'den Veritabanını Geri Yükle seçeneğini kullanın

Northwind.sql.zip - - Sql Server 2005 ve 2008 için Northwind veritabanı oluşturma komut dosyası.
Ardından Sql Sunucunuzda northwind adlı bir veritabanı oluşturun.
Dosyayı açın / sıkıştırmasını açın, ardından sql dosyasını Sql Server Management Studio 2005 / 2008'de açın ve F5'e basın.
VEYA aşağıdaki komutu çalıştırın (örnek)

sqlcmd -S Localhost -d Northwind -i D:\Sql\Northwind.sql
<p align="center">
  <img src="https://user-images.githubusercontent.com/36550960/108242951-34174b00-7156-11eb-8d08-851cb10ff56c.gif?raw=true"  width="400" height="400  image"/> 
</p>
