<h1 align="center">CSS Ödevi | Sıfırdan Responsive Ürün Vitrini</h1>
<h6 align="center"> [Bu repo, Insider&Testinium Tech Hub Developer Bootcamp ödevi için yapılmıştır.]</h6>   

<div align="center">
    
🌐 [View Live Page](https://yeni-urun-listesi.netlify.app/)

</div> 

![third-homework](https://github.com/user-attachments/assets/625bd6ec-0a8a-4e42-b0c1-dd52003c71e0)


## Amaç
Sıfırdan başlayarak, hem HTML yapısını kurup hem de modern CSS teknikleriyle responsive ve interaktif bir yeni ürün listeleme vitrini tasarlamak.

## ```Done:``` Görev 1: HTML İskeletini Oluşturma 
✅ ana başlık   
✅ ana container   
✅ ürün kartı yapısı   

ilk kart: 

```
<h1>Yeni Sezon Ürünleri</h1>

<div class="product-grid">  

    <div class="product-card">
        <div div class="product-image">
            <img src="/assets/product-1.jpg" class="product-image" alt="product-1">
        </div>
        <div div class="product-info">
          <h3>Papatyalı Çanta</h3>
          <p>49.99 TL</p>
          <button>Sepete Ekle</button>
        </div>
    </div>

</div>
```

## ```Done:``` Görev 2 : Vitrini CSS ile Hayata Geçirme

```
.product-grid {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    max-width: 1200px;
    gap: 20px;
    margin: 0 auto;
}
```
Responsive Tasarım: 

```
@media (max-width: 1024px) {
    .product-grid {
        grid-template-columns: repeat(3, 1fr);
    }
}

@media (max-width: 768px) {
    .product-grid {
        grid-template-columns: repeat(2, 1fr);
    }
}

@media (max-width: 480px) {
    .product-grid {
        grid-template-columns: 1fr;
    }
}
```


## ```Done:``` Bonus Puan İçin:
- grid-template-columns için repeat(auto-fill, minmax(250px, 1fr));   

- Bazı ürün kartlarına position: absolute ile "Tükendi" gibi bir rozet ekleyerek
konumlandırma bilginizi pekiştirin.



-----------
<b><em>İncelediğiniz için teşekkür ederim... <br>
Ruken ERPOLAT </em></b>

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-827a67?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/rukenerpolat)
[![Medium](https://img.shields.io/badge/-Medium-827a67?style=flat&logo=medium&logoColor=white)](https://medium.com/@rukenerpolat)
