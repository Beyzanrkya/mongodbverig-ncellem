<div align="center">

# 📍 MongoDB Güncelleme

✨ *Yakınındaki mekanları keşfet!* ✨  

<i>
Bu proje, Web Programlama dersi kapsamında geliştirilmiş
konum tabanlı bir mekan bulma uygulamasının <b>backend</b> tarafını içermektedir.
</i>

<br/>

🚀 *Canlı Demo*  
👉 [mongo_dp_guncelleme_DEMO](https://mongodbverig-ncellem.vercel.app/)

</div>

---

## 🧭 Mekan Bul Nedir?

*MongoDB Güncelleme*, kullanıcıların konum bilgilerine göre
yakın çevredeki mekanları görüntüleyebileceği
modern bir web uygulamasıdır.

Bu repository, uygulamanın *sunucu (backend)* tarafını barındırır
ve RESTful API mimarisi ile çalışır.

---

## 🌟 Öne Çıkan Özellikler

- 📍 *Konuma göre mekan arama*
- 🗺 *MongoDB GeoJSON (2dsphere) desteği*
- 🕒 *Çalışma saatleri yönetimi*
- ⭐ *Puanlama & yorum sistemi*
- 🔐 *Temiz ve modüler API yapısı*
- ☁ *Vercel üzerinde canlı deployment*

---

## 🛠 Kullanılan Teknolojiler

| Teknoloji | Açıklama |
|----------|----------|
| 🟢 Node.js | Sunucu ortamı |
| ⚡ Express.js | API & routing |
| 🍃 MongoDB | NoSQL veritabanı |
| 🧩 Mongoose | ODM |
| 🌍 GeoJSON | Konumsal sorgular |
| 🚀 Vercel | Canlı yayın |

---

## 🔗 API Genel Bakış

```http
GET    /api/venues           → Yakındaki mekanları listele
POST   /api/venues           → Yeni mekan ekle
GET    /api/venues/:venueid  → Mekan detayları
PUT    /api/venues/:venueid  → Mekan güncelle
DELETE /api/venues/:venueid  → Mekan sil
