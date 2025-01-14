README.md
Günlük Uygulaması
Bu proje, bir günlük uygulaması oluşturmak için Tkinter kullanılarak yazılmış bir Python programıdır. Kullanıcılar günlük yazıları yazabilir, geçmiş günlük yazılarını görüntüleyebilir ve zaman kapsülleri oluşturabilirler.

Kurulum
Bu projeyi yerel makinenize klonlayın:

sh
git clone https://github.com/zeynep060/gunlukuygulamasi.py.git
cd gunlukuygulamasi.py
Gerekli bağımlılıkları yükleyin:

sh
pip install tkinter
Kullanım
Programı çalıştırmak için aşağıdaki komutu kullanın:

sh
python main.py
Uygulama açıldığında, aşağıdaki işlevleri gerçekleştirebilirsiniz:

Günlük Yaz: Günlük yazısı yazmak ve kaydetmek için.
Hatıra Canlandırıcı: Rastgele bir günlük yazısını hatırlatır.
Zaman Kapsülü: Zaman kapsülü oluşturmak ve geçmiş zaman kapsüllerini görüntülemek için.
Uygulama Ekranları
Ana Menü: Uygulamanın ana menüsüdür ve kullanıcıyı günlük yazı ekranına, hatıra canlandırıcı ekranına ve zaman kapsülü ekranına yönlendirir.
Günlük Yazma Ekranı: Kullanıcı günlük başlığını ve yazısını girdikten sonra kaydedebilir.
Hatıra Canlandırıcı Ekranı: Rastgele bir günlük yazısını görüntüler.
Zaman Kapsülü Ekranı: Kullanıcı, belirli bir tarihte açılacak mesajlar oluşturabilir ve mevcut zaman kapsüllerini görüntüleyebilir.
JSON Dosyaları
user_info.json: Kullanıcı adını saklar.
diary.json: Günlük yazılarını saklar.
time_capsules.json: Zaman kapsülü mesajlarını saklar.
