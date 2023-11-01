# Bitki Biyolojisi

```mermaid
flowchart TD
    t[Bitkiler]
    t --> t-1[Tohumsuz bitkiler]
    t --> t-2[Tohumlu bitkiler]
    t-1 --> a[Su yosunları]
    t-1 --> b[Kara yosunları]
    t-1 --> c[Eğrelti otları]
    t-2 --> d[Çiçekli bitkiler, tohumlu bitkiler]
    d --> d-1[çeneklerine göre]
    d-1 --> d-1-1[Tek çenekli]
    d-1 --> d-1-2[Çift çenekli]
    d-1 --> d-1-3[Çok çenekli]
    d --> d-2[gövdelerine göre]
    d-2 --> d-2-1[Otsu]
    d-2 --> d-2-2[Odunsu]
```


```mermaid
flowchart TD
    t[Bitkiler]
    t --> t-1[Tohumsuz bitkiler]
    t --> t-2[Tohumlu bitkiler]
    t-1 --> a[Damarsız tohumsuz]
    t-1 --> b[Damarlı tohumsuz]
    a --> a-1[Kara yosunu]
    b --> b-1[Eğrelti otları]
    t-2 --> c[Açık tohumlu, kozalaklı bitkiler]
    t-2 --> d[Kapalı tohumlu]
    c --> c-1[Coniferler bitkiler]
    c-1 --> c-1-1[Kozalak yaprakları arasında tohum bulunur]
    c-1 --> c-2-1[Çam]
    c-1 --> c-2-2[Ardıç]
    c-1 --> c-2-3[Ladin]
    c-1 --> c-2-4[Servi]
    d --> d-1[Tek çenekli]
    d --> d-2[Çok çenekli]
```

## Çiçekli Bitkiler
![çiçekli bitkiler](img/çiçekli-bitki.svg) 

### Çiçekli Bitkilerin Dokuları
#### Meristem Doku
- Hücreleri bölünür.
- Bitkilerin ömrü sınırsızdır. Bitki ömrü boyunca bölünür.
- Bölünen meristem doku hücrelerinin bazıları farklılaşır ve bitkinin diğer yani *değişmez dokularını* oluşturur.
- Bazı hücreler G₁den çıkıp G₀a girer ve bir daha bölünmez. Bazı hücreler ihtiyaç olduğunda geniden G₁e döner ve bölünür.
- Bazı meristematik hücreler bazı bitki hormonlarını sentezler ve salgılar.
```
     ┌─ oksin
     │  giberellin
     │  sitokinin
     └─ filorigen
     ┌─ absisik asit
     └─ etilen
```
- Bitki yapılarında boyca büyüme ve ence kalınlaşma sağlar.
- Kök, gövde ve yaprak yapılarında bulunur.
- Meristem hücrelerinin özellikleri:
  - Hücreleri küçük ve çeperleri incedir.
  - Oransal olarak stoplazma büyüktür.
  - Kofullar küçük, sayıca azdır.
  - Çekirdek oransal olarak büyüktür.
  - Hücreler arası boşlukları yok denecek kadar azdır.
  - Metabolizmaları hızlıdır.

```mermaid
flowchart TD
    t[Bulunduğu yere göre meristem]
    t --> t-1[Primer, Uç, Apikal]
    t --> t-2[Internal, Ara]
    t --> t-3[Sekonder, Yanal, Lateral]
```

```mermaid
flowchart TD
    t[Kökenine göre meristem]
    t --> t-1[Primer]
    t --> t-2[Sekonder]
```

##### Primer Meristem
1. Bitkinin ömrü boyunca bölünme özelliğini kaybetmeyen hücrelerin meydana getirdiği dokudur.
2. Kök ve gövde uçlarında, ayrıca dal uçlarında bulunur.
3. Bulunduğu yerde boyca uzamayı sağlar. 
4. Primer meristemin kök ve göve uçalarında bulunduğu yere büyüme noktası ya da *büyüme konisi* denir.
5. Büyüme noktaları kökte kaliptrayla, gövdede koruyucu yaparaklarla korunur.
6. **Kaliptra hücreleri canlıdır. Bölünebilme özellikleri yoktur. Toprakta ilerlerken zedelendiğinde primer meristem hücreleri tarafından yenilenir.** 
7. Kaliptra, müsilaj adı verilen özel bir salgı üretir. Kökün toprak içinde rahat ilerlemesini sağlar.
8. Büyüme noktalarından alınan boyuna ya da enine kesitlerde dıştan içe doğru üç tabaka oluşur. *Histojen* adı verilen bu üç tabakalı doku bitkinin farklılaşarak diğer dokularını oluşturur.

##### Sekonder Meristem
```mermaid
flowchart TD
    t[Sekonder meristem]
    t --> t-1[Vasküler kambiyum, Demet kambiyomu]
    t --> t-2[Mantar kambiyumu, Fellogen]
```
1. Kök ve gövdede bulunur, yapraklarda bulunmaz. 
2. Kabiyum, bitkide enine büyümeyi sağlar.
3. Bitkilerde primer meristem farklılaşarak bitkinin diğer dokularını oluşturur. Bu sırada meydana gelen farklılaşma hücreleri G₀ evresine sokar. Böylece, oluşan parankimatik hücrelerin bazıları hormonların etkisiyle 

![sekonder meristem](img/sekonder-meristem.svg) 

#### Temel Doku
- Hayvanlardaki bağ dokunun karşılığıdır.
- Üçe ayrılır:
  - Parankima doku
    - Asimilasyon (özümleme) parankiması
    - İletim parankiması
    - Depo parankiması
    - Havaldırma parankiması
  - Kollenkima doku (canlı)
  - Seklerankima doku (ölü)

#### İletim Doku
- Üçe ayrılır:
  - Ksilem (odun) borusu
  - Floem (soymuk) borusu

#### Örtü Doku
- İkiye ayrılır:
  - Epidermis doku (otsu bitkilerde yok)
  - Peridermis (mantar) doku 
