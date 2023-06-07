## Türkçe README.md

### MAC Changer

Bu program, kullanıcıların ağ arayüzlerinin MAC adreslerini değiştirmelerine olanak tanır.

#### Kullanım Talimatları

1. Programın çalışması için `sudo` yetkilerine sahip olmanız gerekiyor.
2. Terminalde programın bulunduğu klasöre gidin.
3. Aşağıdaki komutları sırayla çalıştırarak yeni bir MAC adresi belirleyin:

```python3
python3 mac_changer.py -i [arayüz adı] -m [yeni mac adresi]
```

`[arayüz adı]` yerine ağ arayüzü adınızın doğru şekilde yazılmalısınız (örneğin: eth0).

4. Eğer işlem başarıyla tamamlandığında yeni MAC adresiniz gösterilecektir.

#### Önemli Notlar
- Lütfen bu programın yanlış kullanımından kaynaklanan tüm sorunlardan kendiniz sorumlu olduğunuzu unutmayın.
- 
## English README.md

### MAC Changer

This program allows users to change the MAC address of their network interfaces.

#### Usage Instructions

1. You need to have `sudo` privileges for the program to work.
2. Navigate to the folder where the program is located in your terminal.
3. Run the following command to specify a new MAC address:

```python
python3 mac_changer.py -i [interface name] -m [new mac address]
```

Replace `[interface name]` with your correct network interface (e.g., eth0).
 
4. If successful, you will be shown your new MAC address.

#### Important Notes
- Please note that you are responsible for any issues caused by misuse of this program.

