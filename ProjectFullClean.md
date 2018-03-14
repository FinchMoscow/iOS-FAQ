**Полная очистка проекта**

Иногда возникает ситуация, что по какой-то причине начинают лезть непонятные ошибке при сборке проекта. Вот небольшой туториал, как полностью удалить pods из проекта и все вычистить.

1.  Удалям pods
Последовательно выполняем команды в терминале:  
sudo gem install cocoapods-deintegrate cocoapods-clean  
pod deintegrate  
pod clean  

2. Клиним проект
cmd+shift+k  
cmd+option+shift+k  

3. Убираем derived data  
Вводим команду в терминале:  
rm -rf ~/Library/Developer/Xcode/DerivedData