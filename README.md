# Mugam Cup E-Sport

Brauzerdə işləyən taktiki e-sport menecer oyunu. Komandanı seçirsiniz, oyunçuları alıb-satırsınız, taktika qurursunuz və mövsüm boyu round-robin cədvəldə yarışırsınız.

## Necə işə salınır

Yükləmək üçün repozitoriyanı klonlayın və ya `index.html` faylını brauzerdə açın. Əlavə quraşdırma tələb olunmur. Oyun vəziyyəti brauzerin `localStorage`-da saxlanılır.

GitHub Pages ilə də işlədə bilərsiniz: repozitoriyanın Settings → Pages bölməsində `main` branch-ı seçin.

## Oyunun əsasları

- **Komanda:** 16 komandadan birini seçin. Başlamaq üçün seçdiyiniz komandada ən azı 5 əsas oyunçu olmalıdır.
- **Oyunçular:** hər komandada 5 əsas oyunçu var, qalanları yedəkdir. Əsas və yedək arasında keçid edə bilərsiniz.
- **Oyunçu axtarışı:** digər komandalardakı və azad oyunçuları axtarıb büdcənizə görə alın. Qiymət oyunçunun K/D göstəricisinə görə müəyyən olunur (ən aşağı ~$1.5k, ən yüksək $60k).
- **Büdcə:** $20,000 ilə başlayırsınız. Hər matçdan sonra qələbə və ya məğlubiyyət üçün mükafat alır və əməkhaqqı ödəyirsiniz.
- **Mövsüm:** hər komanda 15 matç keçirir. Digər matçlar AI tərəfindən simulyasiya olunur.

## Rollar və uyğunluq

Hər oyunçunun öz rolu (Duelist, Initiator, Controller, Sentinel) var. Oyunçu təyin olunduğu rolda nə qədər uyğun olduğunu faizlə görürsünüz.

- Rol uyğunluğu 40%-dən aşağı düşərsə, oyunçu narazılıq bildirir. Ardıcıl 7 matçdan sonra komandanı tərk edir.
- Əsas heyət 5-dən azalarsa, yedəkdən və ya büdcəniz çatdığı qədər azad oyunçudan avtomatik doldurulur.

## Taktika lövhəsi

Taktika sekmesində xəritə seçin və **Hücum** və ya **Müdafiə** tərəfini seçin.

- Hər xəritə üçün oyunçuların yerləşə biləcəyi zonalar məhdudlaşdırılıb. Zonalar lövhədə kəsikli xətlə göstərilir.
- **Hücum** taktikası oyunçuların yerinə görə təsnif olunur: Execute (85%), Default (70%), Mid default (65%) və digərləri (45%).
- **Müdafiə** tərəfində oyunçuların sitelər (A, B) və ya Mid üzərində yerləşməsi yoxlanılır. Sitedə tək qalan oyunçu controller olmalıdır, Mid boş qalarsa komanda roundların bir hissəsini itirir.

## Assistant Coach

Koç sekmesində oyunla bağlı bildirişlər toplanır: taktikanı dəyişmək tövsiyəsi, müdafiə xətaları, oyunçunun narazılığı, komandanı tərk etməsi və yeni oyunçu alınması.

## Xəritələr

- Qala Keçidi
- Dağ Yolu
- Kəhrəba Limanı
- Sınıq Körpü

## Qeyd

Bütün oyunçu, komanda, agent və xəritə adları orijinaldır. Bu layihənin heç bir real oyun şirkəti ilə əlaqəsi yoxdur.
