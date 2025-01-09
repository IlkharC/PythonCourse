## Değişken Nedir?

Değişken, içinde bir değer yani veri tutmak için kullanılır. Bunu şöyle düşünebilirsiniz: **Değişken bir kutudur ve kutuya bir değer koyarız**. 

![chrome_KqyeT5nfJl](https://github.com/user-attachments/assets/abe35cf8-f8a7-494e-9fe2-6d52b16a1e19)

Bu işleme **değer atama** denir ve **=** sembolü ile yapılır.
```python
degisken = "deger"
```

### Değişkene İsim Verme Kuralları

Değişken isimleri belirli kurallara göre verilmelidir. İşte bazı kurallar:

1. **İsmin baş harfi büyük olmamalıdır.**  
   (Örnek: `Yaş` yanlış, `yas` doğru)

2. **İsmin başında alt çizgi (_), rakam veya özel karakter olmamalıdır.**  
   (Örnek: `_yas` yanlış, `yas_` doğru)

3. **Sadece harfler ve alt çizgi (_) kullanılabilir.**  
   (Örnek: `yas_1` doğru, `yas 1` yanlış)

## **Değişkenlerin Çalışma Mantığı**

Değişkenler, programımız çalıştırıldığında **source file** (kaynak dosya) üzerinden okunarak bilgisayarımızın **RAM**'ine (operatif bellek) yüklenir. Bu süreçte değişkenler geçici olarak bellekte saklanır.

![chrome_Q9sIGslrZO](https://github.com/user-attachments/assets/484309d5-3fc5-468c-ac47-2b4b70c41f5d)

### **Önemli Nokta:**
- Program **kapatıldığında** operatif bellekteki değişkenler silinir.
- Bu nedenle değişkenler, program çalışırken kullanılabilir.

___

## **Veri Tipleri**

Python'da 4 tane ana veri tipi vardır.

### 1. **`str` (String)**  
String veri tipi, klavyemizdeki tüm karakterleri saklayabilir. Bir değerin string olduğunu tanımlamak için karakterleri çift tırnak (`" "`) veya tek tırnak (`' '`) içerisine yazmalıyız.  

### 2. **`int` (Integer)**  
Integer veri tipi, tam sayıları saklar. Örneğin, 123 ve -263 birer tam sayıdır.  

### 3. **`float` (Floating Point)**  
Float veri tipi, ondalıklı sayıları saklamak için kullanılır. Örnekler: 1.5, -2.0, 0.321.  

### 4. **`bool` (Boolean)**  
Boolean veri tipi, sadece iki değer saklayabilir: **`True`** (Doğru) veya **`False`** (Yanlış).  

**Örnek:**  
Bir `lambaAcikmi` isimli değişkenimiz olsun. Eğer `True` değerini verirsek lamba açıktır, `False` değerini verirsek kapalıdır.
```python
lambaAcikmi = True
```
___

#### Konusmanin video halini youtube kanalimdan izleyebilirsiniz: https://youtu.be/HAZ9i4iDh_0?si=iiivfE-AOSs0U1SJ
