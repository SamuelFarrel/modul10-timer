# Modul 9 - High Level Networking
**Samuel Farrel Bagasputra - 2206826614 - Adpro C**
<br><br>

## Experiment 1.2: Understanding how it works
- What happenned when you run the program ? <br><br>
<img src="images/12.png">
`hey hey` diprint terlebih dahulu dibandingkan pesan yang lain.
<br><br>
- Hal ini terjadi karena `println!("Samuel's Computer: hey hey")` berada diluar asynchronus task yang akan dieksekusi ketika `executor.run()` dijalankan. Jadi ketika `main` dijalankan, `println!("Samuel's Computer: hey hey")` akan dijalankan terlebih dahulu sebelum task asynchronus dijalankan.
