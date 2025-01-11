# Özel Video Oynatıcı

Bu proje, HTML, CSS ve JavaScript kullanılarak oluşturulmuş özel bir video oynatıcıdır. Modern bir görünüm, kullanıcı dostu kontroller ve bazı ek özellikler sunar.

## Özellikler

-   **Oynatma/Duraklatma:** Videoyu oynatabilir veya duraklatabilirsiniz.
-   **Ses Açma/Kapatma:** Videonun sesini açabilir veya kapatabilirsiniz.
-   **Tam Ekran Modu:** Videoyu tam ekrana geçirebilir veya tam ekrandan çıkabilirsiniz.
-   **İndirme:** Video dosyasını indirebilirsiniz.
-   **İlerleme Çubuğu:** Video ilerlemesini görebilir ve videoda herhangi bir konuma atlayabilirsiniz.
-   **Geri/İleri Sarma:** Videoyu 10 saniye geri veya ileri sarabilirsiniz.
-   **Logo:** Özel bir logo eklenmiştir.
-   **Klavye Kısayolları:**
    -   **Boşluk (Space):** Oynat/Duraklat
    -   **M:** Ses aç/kapat
    -   **Sol Ok:** Geri sar (5 saniye)
    -   **Sağ Ok:** İleri sar (5 saniye)
    -   **F:** Tam ekran
-   **Otomatik Gizlenen Kontroller:** Kontroller video üzerinde fare hareket ettirildiğinde görünür, hareket etmediğinde otomatik olarak gizlenir.
-    **Merkez Kontroller:** Video oynatılırken veya duraklatılırken video üzerinde merkezde geçici kontroller gösterilir.

## Nasıl Kullanılır

1.  Bu projeyi GitHub'dan indirin veya klonlayın.
    ```bash
    git clone KerimDemirkaynak/Kerimu-HTML5-Player
    ```
2.  `player.html` dosyasını bir web tarayıcısında açın.
3.  `video` etiketindeki `src` özniteliğini kendi video dosyanızın URL'si ile değiştirin.
4.  İsteğe bağlı olarak, `poster` özniteliğini video yüklenirken görüntülenecek bir resimle değiştirin.
5.  Logonuzu değiştirmek için, `img` etiketindeki `src` özniteliğini kendi logo URL'niz ile değiştirin.

## Yapı

Proje aşağıdaki dosyalardan oluşmaktadır:

-   `player.html`: Video oynatıcının HTML yapısı.
-   **Stil:** CSS, gömülü bir style etiketi içinde tanımlanmıştır, görünümü özelleştirir.
-   **Komut Dosyası:** JavaScript, video oynatıcının işlevselliğini yönetir.

## Bağımlılıklar

-   **Font Awesome:** Kontrol düğmeleri için simgeler sağlamak üzere kullanılmıştır.
    -   CDN linki : `https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css`

## Ekran Görüntüleri

_Video oynatıcının normal görünümü:_

![image](https://github.com/user-attachments/assets/2b3a25fa-6d00-4761-8568-a6bc38de6952)


_Video oynatıcının tam ekran görünümü:_

![image](https://github.com/user-attachments/assets/d9238b41-a12b-40f5-a9d6-28867589579b)


## Katkı

Katkılarınız her zaman memnuniyetle karşılanır. Lütfen herhangi bir hata veya iyileştirme öneriniz varsa issue açın veya pull request gönderin.

## Lisans

Bu proje, MIT Lisansı altında lisanslanmıştır. Daha fazla bilgi için [LICENSE](LICENSE) dosyasına bakın.

## Notlar

-   Video oynatıcının görünümü ve işlevselliği gereksinimlerinize göre özelleştirilebilir.
-   Video etiketine başka öznitelikler ekleyebilir veya JavaScript'e ek işlevsellik ekleyebilirsiniz.
