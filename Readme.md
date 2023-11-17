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

![alt text](https://github.com/AdamPiechowiak/fullstack-zad5/blob/main/Screenshot2.png)

screan przedstawiający obciążenie na aplikacji php-apache

![alt text](https://github.com/AdamPiechowiak/fullstack-zad5/blob/main/Screenshot1.png)
