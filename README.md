# 🛡️ Kardelen Aura: Ghost Protocol v8.0 [MASTER]

**Kardelen Aura: Ghost Protocol**, geleneksel antivirüs ve statik analiz yöntemlerini bypass etmek amacıyla geliştirilmiş, hibrit bir polimorfik siber güvenlik kalkanıdır. Sistem, çalışma zamanında (runtime) hem kendi dijital imzasını hem de işlem mantığını sürekli değiştirerek "yakalanamaz" ve "analiz edilemez" bir yapı sunar.

![Security Status](https://img.shields.io/badge/Status-Active-brightgreen)
![Language](https://img.shields.io/badge/Language-Python%20%7C%20C%2B%2B-blue)
![Version](https://img.shields.io/badge/Version-8.0%20Master-blueviolet)

---

## 🚀 Öne Çıkan Özellikler

### 1. Metamorfik Komut Transpiler
Yazılımın temel işlemci komutlarını (Opcode) çalışma zamanında anlamsal olarak eşdeğer ancak yapısal olarak farklı komutlarla yeniden yazar. 
* *Örnek:* `ADD EAX, 5` komutu canlı olarak `SUB EAX, -5` operasyonuna dönüştürülür.

### 2. Gerçek Zamanlı LSB Steganografi
Sistemin mutasyon enerjisini sağlayan "Master Key", herhangi bir dosyada saklanmaz. Bunun yerine, sisteme yüklenen bir görselin pikselleri arasına **Least Significant Bit (LSB)** yöntemiyle gizlenir.

### 3. Logic Maze (Control Flow Flattening)
Kodun doğrusal akış şeması bozularak bir labirent yapısına dönüştürülür. IDA Pro veya Ghidra gibi araçlarla yapılan analizlerde kodun mantıksal akışı takip edilemez hale gelir.

### 4. Anti-Analysis & Anti-Dump
* **Debugger Detection:** Hata ayıklayıcı tespit edildiğinde sistem anında savunma moduna geçer.
* **Memory Scrubbing:** Kritik veriler ve anahtarlar, işleri biter bitmez RAM üzerinden kalıcı olarak silinir.

---

## 📸 Sistem Ekran Görüntüleri

| Sürüm | Açıklama |
| :--- | :--- |
| **v5.0 Next Gen** | Statik durum izleme ve polimorfik bellek haritası başlangıcı. |
| **v6.0 Premium** | Bölge kilidi (Kayseri/TR) ve çok çekirdekli mutasyon motoru. |
| **v7.0 Ultimate** | Metamorfik transpilation ve heuristik analiz grafikleri. |
| **v8.0 Master** | **Ghost Protocol:** Steganografi ve tam kapsamlı anti-dump koruması. |

---

## Görseller
<img width="927" height="525" alt="image" src="https://github.com/user-attachments/assets/a75f897a-7453-4d6a-bac9-d0dd7bc6e68f" />
<img width="925" height="521" alt="image" src="https://github.com/user-attachments/assets/371c7250-f555-45d4-8e29-665d2da6f168" />
<img width="930" height="525" alt="image" src="https://github.com/user-attachments/assets/9adffd2b-b4e0-4cd6-b269-31bbebeeedd1" />
<img width="924" height="523" alt="image" src="https://github.com/user-attachments/assets/0f103180-3a2a-4042-a852-02e8ea835b24" />
<img width="930" height="529" alt="image" src="https://github.com/user-attachments/assets/8dc05c63-12d8-417a-a118-227ece50eb61" />
<img width="928" height="521" alt="image" src="https://github.com/user-attachments/assets/bfd1f110-7085-447a-bec4-adde56c59cf5" />
<img width="929" height="523" alt="image" src="https://github.com/user-attachments/assets/b261c44b-fc3e-473b-ae4a-a388e735841e" />
<img width="928" height="526" alt="image" src="https://github.com/user-attachments/assets/33847428-fab0-4b83-a1c8-9bd6ba6020df" />
<img width="926" height="523" alt="image" src="https://github.com/user-attachments/assets/3276a523-3a59-4abd-b0df-d90ac82b1cad" />
<img width="928" height="524" alt="image" src="https://github.com/user-attachments/assets/4c00c10f-c99b-4628-bc9c-4d638151d285" />
<img width="927" height="525" alt="image" src="https://github.com/user-attachments/assets/ce91af35-153b-4bd0-93bf-638d3a145ea8" />
<img width="927" height="521" alt="image" src="https://github.com/user-attachments/assets/0f7dafe5-0188-4723-a33a-90952a1f7569" />
<img width="930" height="521" alt="image" src="https://github.com/user-attachments/assets/abb68f31-eb03-4c37-876e-f4dbce5daa69" />
<img width="929" height="522" alt="image" src="https://github.com/user-attachments/assets/d53b8dcb-c4f7-4738-a228-50731ebab1b8" />


## 📝 Lisans ve Notlar
Bu proje, Elif Nur Ayhan tarafından geliştirilmiştir.

Kardelen Aura: Ghost Protocol - Görünmeyeni Savun.
