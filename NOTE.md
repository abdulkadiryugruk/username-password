# NOTLAR
--------
Console.WriteLine("Hoşgeldiniz. Lütfen Üyeliğinizi tamamlayınız.");
Console.WriteLine("Kullanıcı adı: ");
    var kullaniciAdi=Console.ReadLine();

Console.WriteLine("Şifre: ");
    var sifre =Console.ReadLine();

Console.WriteLine("Giriş yapınız");
Console.WriteLine("kullanıcı Adı: ");
    var girilenKA=Console.ReadLine();
Console.WriteLine("şifre: ");
    var girilenS=Console.ReadLine();

var sonuc = (kullaniciAdi==girilenKA)&&(sifre==girilenS)?"Başarıyla giriş yaptınız.":"Kullanıcı adı veya hatalı şifre. Lütfen tekrar deneyiniz.";

Console.WriteLine(sonuc);
