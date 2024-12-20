### Python yuksek seviyeli yani insan diline daha yakin, bilgisayarin anlayabilecegi dile daha uzak bir dildir. Buyuzden bilgisayarimizin yazdigimiz kodlari anlayabilmesi icin bize bir tercuman lazim burda Interpreter(Yorumlayici) devreye giriyor peki Interpreter nasil calisir ve kodumuz hangi asamalardan gecer birlikte bunlari inceleyelim. 

## Editor ve Source File
- Ilk once yazdığımız kod .py uzantılı bir dosyaya yani source file'a kaydedilir. Bu işlemi kullandığımız editörler mesela Pycharm yapar

![how-python-interpreter-works](https://github.com/user-attachments/assets/896b1482-7385-45ff-8317-1e57630334aa)

- Burada dikkat etmemiz gereken bir nokta var: yorum satırları ve boşluklar çalıştırılabilir kod olarak sayılmaz ve Python tarafından dikkate alınmaz.
## Yorum satırları 
- genellikle kodumuzda not almak için kullanılır. Örneğin:
```python
print("Merheba") # Bu bir print funksiyonudur ve Console'da Merheba ciktisini verir
```
## ByteCode Olusturulmasi
- Bu asamada devreye compiler(derleyici) girer.
Python'da compiler, kaynak dosyada yazdığımız tüm kodu bytecode adı verilen bir ara formata dönüştürür.

- Bytecode, CPU(islemci)'nun doğrudan anlayacağı bir dil değildir, ancak daha düşük seviyeli bir ara formattır.
Örneğin, print("Merhaba") fonksiyonu bytecode'da:

```
  0           0 RESUME                   0

  1           2 PUSH_NULL
              4 LOAD_NAME                0 (print)
              6 LOAD_CONST               0 ('Merheba')
              8 PRECALL                  1
             12 CALL                     1
             22 RETURN_VALUE
```

## Virtual Machine ve Yorumlama Süreci
- Bytecode oluşturulduktan sonra Virtual Machine devreye girer.

- VM, oluşturulan bytecode'u satır satır yorumlar ve çalıştırır.
Yani, her bir komutu CPU'nun anlayabileceği şekilde yorumlar yani bilgisayarin tam anlayabilecegi makine diline cevirir buysa cogu zaman filmlerde vb.
gordugumuz 0 ve 1 lerden olusan kodlar ve çalıştırılması için işlemciye gönderir.
İşlemci de bu komutları çalıştırarak kodumuzun sonucunu bize gösterir.

### Özetle:
- Kodumuz .py uzantılı bir kaynak dosyasına kaydedilir.
Compiler devreye girerek kodumuzu bytecode'a dönüştürür.
Virtual Machine bytecode'u satır satır yorumlayarak makine diline (0&1) cevirir, 
CPU ise bu komutları çalıştırarak kodun sonucunu ekrana yansıtır.

#### Konusmanin video halini youtube kanalimdan izleyebilirsiniz: https://youtu.be/acXA-I1F1X4?si=ajMe2TKeue242Y-n
