# DNS Analiz Çalışması - Wireshark ve nslookup

Bu proje, DNS trafiğini analiz etmek için Wireshark ve nslookup komutunun kullanıldığı çalışmaları içermektedir. Amaç, DNS sorgularının ve yanıtlarının nasıl işlendiğini incelemek ve ilgili protokolleri analiz etmektir.

## İçerik

- **21100011016_Odev3.pdf**: DNS analiz çalışmasına ait rapor ve detaylı açıklamalar.
- **21100011016_Odev3.pcapng**: DNS paket yakalama işleminin Wireshark verilerini içeren dosya.

## Projede Yapılan Çalışmalar

1. **nslookup Kullanımı**:
   - `iitb.ac.in` sunucusunun IP adresi belirlendi: `103.21.124.133`.
   - Güvenilir (authoritative) DNS sunucuları ve IP adresleri belirlendi.
  
2. **DNS Trafiği Analizi**:
   - DNS sorgu ve yanıt mesajları incelendi.
   - Mesajların TCP veya UDP protokolü kullanılarak gönderildiği tespit edildi.
   - Sorgu ve yanıt mesajlarının port numaraları belirlendi: Sorgu mesajı genellikle rastgele bir büyük sayı, yanıt mesajı ise genellikle `53` port numarası kullanmaktadır.
   - Cevap içermeyen sorgu mesajları ve içerik bilgileri analiz edildi.

## Kullanılan Araçlar

- **Wireshark**: DNS paketlerini yakalama ve analiz etme aracı. [Wireshark'ı indirin](https://www.wireshark.org/)
- **nslookup**: DNS çözümlemeleri yapmak için kullanılan komut satırı aracı.

## Nasıl Kullanılır?

1. **Wireshark Dosyasını Açın**: `21100011016_Odev3.pcapng` dosyasını Wireshark ile açarak DNS trafiğini analiz edebilirsiniz.
2. **PDF Raporunu İnceleyin**: `21100011016_Odev3.pdf` dosyasında, analiz sonuçları ve yapılan işlemler detaylıca açıklanmıştır.

---

Bu çalışma, DNS protokolü üzerinden gerçekleştirilen sorgu ve yanıt alışverişlerinin incelenmesini amaçlar. Protokolün işleyişini daha iyi anlamak ve analiz becerilerini geliştirmek için hazırlanmıştır.

