# HTML-ve-CSS-ile-basit-Form-Yap-s-leti-im-sa
# İletişim Formu

Bu proje, temel HTML ve CSS kullanılarak oluşturulmuş bir iletişim formudur. Kullanıcıların adlarını, e-posta adreslerini ve mesajlarını girebilecekleri basit bir form yapısı içermektedir.

## Dosya Yapısı

- `index.html` → İletişim formunu içeren HTML dosyası.
- `styles.css` → Formun görünümünü düzenleyen CSS dosyası.

## Kullanım

1. Projeyi bilgisayarınıza klonlayın veya ZIP olarak indirin.
2. `index.html` dosyasını bir tarayıcıda açarak formu görüntüleyin.
3. Kullanıcı bilgilerini girerek formun nasıl çalıştığını test edin.

## Katkıda Bulunma

Geliştirmeler ve iyileştirmeler için pull request gönderebilirsiniz. Geri bildirimleriniz değerlidir!

## Lisans

Bu proje açık kaynaklıdır ve MIT lisansı altında yayınlanmaktadır.
## HTML FORM YAPISI

<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>İletişim Sayfası</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h2>İletişim Formu</h2>
        <form action="#" method="post">
            <label for="name">Adınız:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">E-posta:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Mesajınız:</label>
            <textarea id="message" name="message" rows="5" required></textarea>

            <button type="submit">Gönder</button>
        </form>
    </div>
</body>
</html>

## CSS DOSYA FORMU
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
}

.container {
    background: white;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    width: 100%;
    max-width: 400px;
}

h2 {
    text-align: center;
    color: #333;
}

form {
    display: flex;
    flex-direction: column;
}

label {
    margin-top: 10px;
    font-weight: bold;
}

input, textarea {
    padding: 10px;
    margin-top: 5px;
    border: 1px solid #ccc;
    border-radius: 5px;
    width: 100%;
}

button {
    margin-top: 15px;
    background: #28a745;
    color: white;
    padding: 10px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    font-size: 16px;
}

button:hover {
    background: #218838;
}
