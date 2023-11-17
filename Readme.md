pliki yaml zawierają ojekty kubernetesa:
 - namespace zad5
 - quota
 - pod worker
 - deployment oraz service admin-php
 - HorizontalPodAutoscaler

po utworzeniu obiektów wewnątrz poda worker uruchomiłem komendę

```while [ true ]
do
   curl http://php-apache
done;
```

która wytwarza obciążenie na aplikacji php-apache

screan zasobów w namespace zad5

![alt text](https://i1.kwejk.pl/k/obrazki/2018/04/u97jG7IkwVwtAG4Z.jpg)

screan przedstawiający obciążenie na aplikacji php-apache

![alt text](https://fwcdn.pl/fpo/47/13/4713/7535946.3.jpg)
