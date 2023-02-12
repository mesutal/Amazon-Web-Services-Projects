# Özgür Öztürk Udemy AWS Bitirme Projesi
## Proje kapsamında yapılanlar:

* **VPC** servisi kullanılarak 3 adet public subnet'ten oluşan bir ağ oluşturuldu.
* **S3** servisi kullanılarak; İlki resimleri saklayan, ikincisi Lambda fonksiyonuyla resimlerin küçük boyutlarını saklayacak olan 2 adet Bucket oluşturuldu.
* **IAM** servisinde gerekli olan Role ve Policy'ler oluşturuldu.
* **Lambda** servisi kullanılarak birinci S3 Bucket'ına gönderilen resimlerin 100x100 ebaatına küçültürülerek ikinci S3 Bucket'ına atılmasını sağlayan fonksiyon oluşturuldu.
* Proje boyunca kullanılacak olan **Security Group** oluşturuldu.
* **EC2** servisi kullanılarak Template olarak kullanacağımız ve tüm sistemin yüklü olacağı **Instance** oluşturuldu. MySql, PHP, Apache gibi gerekli tüm paketler kuruldu.
* Tüm dosyaları bir arada tutmak adına bir tane **EFS File System** oluşturuldu.
* **RDS** servisi kullanılarak MysSql Engine bir veritabanı oluşturuldu. Sanal makine üzerinden veri tabanı tabloları hazırlandı.
* Gerekli html, php ve script dosyaları hazırlandı.
* Makineye bağlı diskin **Snapshot**'ı alındı, alınan snapshot'tan **AMI** yaratıldı.
* **Target Group** ve **Load Balancer** kuruldu.
* CPU Utilization üzerinden mevcut Instance'ı, belirtilen mevcut,minimum ve maksimum Instance sayısı kadar ölçeklendirebilecek **Auto Scaling** oluşturuldu.
* **Cloudfront** servisi kullanılarak bir adet web disturbition yaratıldı.
* **Route53** servisi kullanılarak DNS alındı ve gerekli ayarlar yapıldı. www...........com'a giderek web uygulamasının çalıştığı onaylandı.

Dipnot: Php,html dosyaları ve ImageResize.zip Özgür Öztürk tarafından hazırlanmıştır.