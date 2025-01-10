## Aritmetik Operatörler

**Aritmetik Operatörler**, matematiksel işlemler yapmak için kullanılır. Şimdi örnek olarak iki değişken yaratalım ve operatörleri deneyelim.

```python
num1 = 5
num2 = 2
```

| Operatör | Açıklama        | Örnek Kod         | Sonuç       | Ek Bilgi |
|----------|-----------------|-------------------|-------------|----------|
| `+`      | Toplama         | `print(num1 + num2)`   | `7`    |          |
| `-`      | Çıkarma         | `print(num1 - num2)`   | `3`    |          |
| `*`      | Çarpma          | `print(num1 * num2)`   | `10`   |          |
| `/`      | Bölme           | `print(num1 / num2)`   | `2.5`  |          |
| `//`     | Tam Bölme       | `print(num1 // num2)`  | `2`    | Bölme sonucunun tam kısmını alır. |
| `%`      | Modül (Kalan)   | `print(num1 % num2)`   | `1`    | Kalanı verir. Örnek: `5 - (2 * 2) = 1` |
| `**`     | Üs Alma         | `print(num1 ** num2)`  | `25`   |          |

___

## Atama Operatörleri

Atama operatörleri, bir değişkene değer atamak veya mevcut değeri değiştirmek için kullanılır ve Normal Atama Operatörü hariç diğerleri **Aritmetik Operatörlerin** yaptığı işlevin aynısını yapar ama daha kısa şekilde.

```python
num1 = 5
num2 = 2
```

| Operatör | Açıklama        | Örnek Kod         | Sonuç        |      Uzun Hali       |
|----------|-----------------|-------------------|--------------|----------------------|
| `=`      | Normal Atama    | `num1 = 6`        |  `num1: 6`   |                      |
| `+=`     | Artı eşittir    | `num1 += num2`    |  `num1: 7`   |  num1 = num1 + num2  |
| `-=`     | Eksi eşittir    | `num1 -= num2`    |  `num1: 3`   |  num1 = num1 - num2  |
| `*=`     | Çarpı eşittir   | `num1 *= num2`    |  `num1: 10`  |  num1 = num1 * num2  |
| `/=`     | Bölü eşittir    | `num1 /= num2`    |  `num1: 2.5` |  num1 = num1 / num2  |
| `//=`    | Tam Bölü eşittir| `num1 //= num2`   |  `num1: 2`   |  num1 = num1 // num2 |
| `%=`     | Modül eşittir   | `num1 %= num2`    |  `num1: 1`   |  num1 = num1 % num2  |
| `**=`    | Üs eşittir      | `num1 **= num2`   |  `num1: 25`  |  num1 = num1 ** num2 |               

___

## Pratik

### String Birleştirme (Concatenation)
```python
str_1 = "Yazilimci"
str_2 = "Olma"
str_3 = "Yolunda"
str_4 = str_1 + " " + str_2 + " " + str_3
print(str_4)
```

### Sayının Son İki Rakamini Alma
```python
print(12345 / 100)
num1 = 12345
last_two_digits = num1 % 100  # Son iki basamak
print(last_two_digits)   #45
```
___

#### Konusmanin video halini youtube kanalimdan izleyebilirsiniz: https://youtu.be/yUfbZK8ZgWQ?si=cfRQNpHBooqS6Tw4
