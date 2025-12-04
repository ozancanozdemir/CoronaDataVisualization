## **Visualization using Plotly and Leaflet Packages for Corona Disease**

### **Türkçe & English**

---

# 🇹🇷 **Türkçe Açıklama**

## **Corona Virüsü Veri Görselleştirmesi (Plotly & Leaflet)**

Bu proje, **Kaggle** üzerinden alınan (orijinal kaynak: *Johns Hopkins University*) **Corona Virus 2019 (nCoV)** verileri kullanılarak oluşturulmuş interaktif veri görselleştirmelerini içermektedir. Çalışmada hem **plotly** hem de **leaflet** paketleri kullanılarak farklı grafikler ve harita tabanlı görselleştirmeler üretilmiştir.

### 📂 **Proje İçeriği**

* 22.01.2020–31.01.2020 tarihleri arasındaki:

  * Toplam vaka sayıları
  * Toplam ölüm sayıları
  * Toplam iyileşen sayıları
* Ülkeler bazında toplam vaka sayılarını gösteren **Leaflet interaktif dünya haritası**

### 🛠️ **Kullanılan R Paketleri**

* `ggplot2`
* `dplyr`
* `plotly`
* `hrbrthemes`
* `leaflet`

### 📊 **Yapılan İşlemler**

1. Veri Kaggle’dan alındı ve tarih kolonları yeniden düzenlendi.
2. Her tarih için toplam vaka, ölüm ve iyileşen sayıları hesaplandı.
3. `ggplot2` ile grafikler çizildi ve `plotly` ile interaktif hâle getirildi.
4. Ülkelerin enlem–boylam bilgileri eklenerek **Leaflet** ile interaktif bir harita oluşturuldu.

### 🌍 **Leaflet Haritası**

Her ülke için toplam vaka sayısına bağlı olarak farklı büyüklüklerde kırmızı noktalar çizilmiştir.

### 📁 **Veri ve Kodlar**

Tüm kodlar ve veriler GitHub hesabımda mevcuttur:
🔗 [https://github.com/ozancanozdemir](https://github.com/ozancanozdemir)

---

# 🇬🇧 **English Description**

## **Corona Virus Data Visualization (Plotly & Leaflet)**

This project includes interactive data visualizations created using **Novel Corona Virus 2019 (nCoV)** datasets obtained from **Kaggle** (original source: *Johns Hopkins University*). Both **plotly** and **leaflet** packages are used to build interactive charts and a world map.

### 📂 **Project Content**

The following metrics are visualized for the period **22.01.2020–31.01.2020**:

* Total number of confirmed cases
* Total number of deaths
* Total number of recovered patients
* Interactive world map showing total confirmed cases per country

### 🛠️ **R Packages Used**

* `ggplot2`
* `dplyr`
* `plotly`
* `hrbrthemes`
* `leaflet`

### 📊 **Workflow Overview**

1. The dataset was downloaded from Kaggle, and the date column was manually cleaned and corrected.
2. Daily totals were calculated for confirmed, death, and recovered cases.
3. Visualizations were created using `ggplot2` and converted to interactive charts using `plotly`.
4. Country-level data was merged with latitude–longitude coordinates, and an interactive **Leaflet** map was generated.

### 🌍 **Leaflet Map**

Each country is represented with a red circle whose size corresponds to the total number of confirmed cases.

### 📁 **Data and Code**

All datasets and scripts are available on my GitHub page:
🔗 [https://github.com/ozancanozdemir](https://github.com/ozancanozdemir)



Eğer istersen README’ye **ek görseller**, **kaç paket sürümlerinin kullanıldığı**, **kurulum adımları**, veya **çalıştırma talimatları** da ekleyebilirim.
