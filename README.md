# PublicTaramaTest

Bu depo yaln?zca kontroll? ESG testlerine ait sentetik belgeleri bar?nd?r?r. Dosyalardaki ?irket etiketleri test y?nlendirmesi i?indir; i?erikler ger?ek ?irket beyan?, raporu veya kan?t? de?ildir.

## HTTPS test adresi

GitHub Pages: https://ahmetrz.github.io/PublicTaramaTest/

- `T03/current.html` tek URL'dir. ??erik A ve B olarak ayn? yolda yay?mlanabilir; Pages/CDN yay?l?m ve ?nbellek s?resi denetlenemez. Son denemede B i?eri?i yakla??k 50 saniyede g?r?n?r olmu?, `Cache-Control: max-age=600` d?nm??t?r.
- `T04` 220 sayfal? sentetik PDF'lerdir. `T06_ABB_OCR.pdf` ve `T06_BAYLAN_OCR.pdf` iki sayfal?, metin katman? olmayan ve senaryodaki T?rk?e kontrol c?mlesini i?eren PDF'lerdir.
- `T05` PDF'leri kodda g?r?len 15 MiB uygulama ve 20 MiB okuma-servisi s?n?rlar?n?n iki yan?nda birer baytt?r; tam c?mle ve SHA-256 bilgisi `T05_envanter.json` i?indedir. Bunlar sa?lay?c?lar?n kendi limitini kan?tlamaz.
- `T19` yaln?zca ge?erli sayfa ve 404 davran???n? test eder. Statik GitHub Pages 401/403/429/5xx veya gecikme yan?tlar? ?retemez.
- Bu adresi yay?mlamak ?cretli Bing/Exa taramas? ba?latmaz. Sa?lay?c? sonu?lar? ve maliyetleri ayr?ca yetkilendirilmelidir.

??erikler sentetik olarak a??k?a etiketlenmi?tir; ger?ek ESG bulgusu olarak kullan?lmamal?d?r.
