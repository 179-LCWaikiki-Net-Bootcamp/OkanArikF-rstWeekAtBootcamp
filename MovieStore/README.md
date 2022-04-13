# Bootcamp birinci hafta örnek webapi projesi

Kullanılanlar : 

- Entity Framework Core 
- Entity Framework Core InMemory
- CustomException Middleware 
- Fluent Validation

![Ekran görüntüsü 2022-04-14 025704](https://user-images.githubusercontent.com/89224500/163282713-d628fd4a-7c2b-468c-928e-a8899b4794b3.png)

- Projemde iki tane controller ım bulunmaktadır Movie ve Actor kontrollerları. Movie deki actor alanı id olarak tutulamktadır ve actor ile arasında primary key , foreign key ilişkisi bulunmaktadır.
- Movie deki director ve genre alanları id olarak tutulmaktadır ve genre ve director enum üzerinde tutularak client e string olarak dönülmektedir.
