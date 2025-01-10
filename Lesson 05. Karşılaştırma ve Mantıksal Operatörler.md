## Karşılaştırma Operatörleri

**Karşılaştırma operatörleri** iki değişken arasında ilişkileri kontrol eder ve bir boolean (**True**/**False**) değer döner. 2 değişken yaratıp operatörlerimizi denemeye başlayalım.

```python
num1 = 5
num2 = 2
```

| Operatör |       İsim      |       Örnek Kod       |  Sonuç  |                        Açıklama                         |
|----------|-----------------|-----------------------|---------|-------------------------------------------------------- |
| `==`     | Eşittirmi       | `print(num1 == num2)` | `False` | Değerlerin ikiside aynıysa True, değilse False verir.   |
| `!=`     | Eşit Değildirmi | `print(num1 != num2)` | `True`  | Değerlerin ikiside aynıysa False, değilse True verir.   |
| `>`      | Büyüktürmü      | `print(num1 > num2)`  | `True`  | Soldaki değer sağdaki değerden büyükse True verir.      |
| `<`      | Küçüktürmü      | `print(num1 < num2)`  | `False` | Sağdaki değer soldaki değerden büyükse True verir.      |
| `>=`     | Büyük Eşittirmi | `print(num1 >= num2)` | `True`  | Sol değer sağ değerden büyükse veya aynıysa True verir. |
| `<=`     | Küçük Eşittirmi | `print(num1 <= num2)` | `False` | Sağ değer sol değerden büyükse veya aynıysa True verir. |

___

```python
num1 = 5
num2 = 2
```

## Mantıksal Operatörler

#### and (Ve) - Tüm koşullar True ise sonuç True döner. Aksi halde False.
- `print(num1 == 5 and num2 == 3)  # False`

#### or (Veya) - Koşullardan en az biri True ise sonuç True döner. Tüm koşullar False ise False.
- `print(num1 == 5 or num2 == 1)   # True`

#### not (Değil) - Verilen koşulun tersini döner. True ise False, False ise True.
- `print(not(num1 == 5))    # False`

___

#### Konusmanin video halini youtube kanalimdan izleyebilirsiniz: https://youtu.be/KS7u810axBw?si=irATS1-E519JS5vm
