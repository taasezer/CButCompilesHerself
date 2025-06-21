# CButCompilesHerself
a c code but it can compile herself

## Açıklama:
- canım sıkıldı ve yapay zeka yardımıylada olsa neden kendi kendine basit de olsa C yapılarını derleyebilen bir C kodu yazmıyorum dedim kendisi kaydedildiği dosya içinde ayrı bir C dosyası açıyor ve "main" fonksiyonu içine girilmiş olan işlemi yapıştırıp çalıştırıyor ve sonucu sizin ekranınıza output olarak yansıtıyor kısaca böyle
- hatalarım olabilir yapayda olsa zeka hata yapar değilmi?

## Kullanım:
- derlemek için terminal kullanmak gerekli gibi birşey linux bazlı sistemlerde daha rahat çalışır
``` terminal
gcc CButCompilesHerself.c -o repl

./repl
```

## Örnek Çıktılar Ve Girdiler:
``` bash
Basit C REPL (Cikmak icin 'exit' yazin)
C kodu yazin ve calistirmak icin Enter a basin:

>>> printf("Merhaba dunya!");
Cikti:
--------------------
Merhaba dunya!
--------------------

>>> for(int i=0; i<5; i++) { printf("%d ", i); }
Cikti:
--------------------
0 1 2 3 4 
--------------------

>>> int x = 5; if(x > 3) { printf("X 3'ten buyuk"); } else { printf("X 3'ten kucuk"); }
Cikti:
--------------------
X 3 ten buyuk
--------------------

>>> exit
```
renkleri değişik oldu ama böyle duruyor 
