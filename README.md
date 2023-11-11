# جزوه خلاصه درس

## جلسه‌ی دوم

### اعداد و نماها
1. دقت کنین اگه جملتون شامل اعداد و نمادها باشه باید همچنان هم از نظر انگلیسی درست باشه، مخصوصا علائم نگارشی و نقطه گذاری

```python
Bad: a < b a ǂ 0
Good: We have a < b and a ǂ 0.
Good: We find that a < b and a ǂ 0.
Good: Let a < b, with a ǂ 0.
```
2. نمادهای غیر ضروری رو حذف کنین.
```python
Bad: Every differentiable real function f is continuous.
Good: Every differentiable real function is continuous.
```
> differentiable: تمایز پذیر

3. اگر از اعداد کوچک برای شمارش استفاده می کنین، اون‌ها را کامل بنویسین. اگر به اعداد خاصی اشاره می کنید، از فرم عددیشون استفاده کنین.

```python
Bad: The equation has 4 solutions.
Good: The equation has four solutions.
Good: The equation has 127 solutions.
Bad: Both three and five are prime numbers.
Good: Both 3 and 5 are prime numbers.
```
4. اگه می‌تونی جمله را با عدد یا علامت شروع نکن.

```python
Bad: ρ is a rational number with odd denominator.
Good: The rational number ρ has odd denominator.
```
> denominator: مخرج


5. از عملگر «⇒‟ یا نماد «∴‟ استفاده نکنید. اولی فقط تو جملات نمادین هست، دومی هم تو ریاضیات  سطح بالا استفاده نمیشه.
```python
Bad: a is an integer ⇒ a is a rational number.
Good: if a is an integer, then a is a rational number.
Bad: ⇒ x = 3.
Bad: ∴ x = 3.  
Good: hence x = 3.
```

> hence: از این رو

6. داخل جمله، فرمول ها و نماد‌های کنار هم رو با کلمه‌ها از هم جدا کن.

```python
Bad: Consider An, n < 5.
Bad: Add p k times to c.
Bad: Add p to c k times.
Good: Add p to c, repeating this process k times.
```

### استفاده از مقاله‌ی نامعین مثل `a`, `an و ...

‍1. بجای عدد `یک` (‍`one`)

```python
The four centers lie in a plane.

A chapter will be devoted to the study of expanding maps.
```
> devote: اختصاص دادن

2. وقتی بخواد از نظر معنایی عضو یک گروه از اشیا باشه یا معنای `مقداری` (`some`) یا `یکی از` (`one of`) رو بده.

```python
Then D becomes a locally convex space with dual space D’.
The right-hand side of (4) is then a bounded function.
Theorem 7 has been extended to a class of boundary value problems.
This property is a consequence of the fact that .....
```

حالا همین موارد بالا تو حالت جمع میشن:

```python
The existence of partitions of unity may be proved by .....
The definition of distributions implies that ....
```
> imply: دلالت داشتن 

3. تو تعریف کلاس اشیاء

```python
A fundamental solution is a function satisfying .....
We wish to find a solution of (6) which is of the form ....
```
تو حالت جمع:

```python3
The elements of D are often called test functions.
The integral may be approximated by sums of the form ....
```

~~این مورد پایین رو خیلی خوب متوجه نشدم.~~ 

4. In the plural—when you are referring to each element of a class:
```python
Direct sums exist in the category of abelian groups.
 In particular, closed sets are Borel sets.
 Borel measurable functions are often called Borel mappings.
```
6. If you are referring to all elements of a class, use `the`:
```python
The real measures form a subclass of the complex ones.
```
7. In front of an adjective which is intended to mean “having this particular quality”:
```python
This map extends to all of M in an obvious fashion.
A remarkable feature of the solution should be stressed.
Combining (2) and (3) we obtain, with a new constant C, .....
A more general theory must be sought to account for these irregularities.
```

توضیحات ChatGPT در موردش:
``` 
بله، حتما. این قسمت از متن در مورد استفاده از مقاله نامعین (a، an، ----) در زبان ریاضی است.

1. **در جمع (Plural):** وقتی که به هر عنصر یک کلاس اشاره می‌کنید، از مقاله نامعین استفاده می‌شود. به عنوان مثال، در گفته شده است که "جمع‌های مستقیم در دسته گروه‌های ابلیان وجود دارند". در اینجا، ما در مورد هر عنصر یا گروه ابلیان صحبت می‌کنیم.

2. **قبل از صفت موصول (Adjective):** وقتی که از یک صفت موصول استفاده می‌شود تا به "داشتن این خصوصیت خاص" اشاره کند. برای مثال، "این نقشه به صورت آشکار به همهٔ M گسترده می‌شود". در اینجا، صفت "آشکار" نشان‌دهندهٔ خصوصیت خاصی است که نقشه دارد.

3. **قبل از "the" وقتی به تمام عناصر یک کلاس اشاره می‌شود:** اگر شما به تمام عناصر یک کلاس اشاره می‌کنید، از "the" استفاده می‌کنید. به عنوان مثال، "اندازه‌گیری‌های واقعی یک زیرکلاس از اعداد مختلط هستند". اینجا به تمام اعداد مختلط اشاره شده و از "the" استفاده شده است.

4. **نکته آخر:** مقاله نامعین می‌تواند همراه با صفتی باشد که به "داشتن این خصوصیت خاص" اشاره دارد. به عنوان مثال، "یک ویژگی قابل توجه در راه حل باید تاکید شود". در اینجا، ویژگی قابل توجه به ماهیت خاصی اشاره دارد.
```

## جلسه‌ی سوم

1. سعی کنین بجای استفاده از زبان پیچیده از زبان واضح و سر راست استفاده کنین و الکی نپیچونین مطلب رو. از طرفی هم از جملات طولانی استفاده نکنین و اون جمله رو به چند تا جمله کوچیک‌تر بشکونین.

```python
Bad: We note the fact that the polynomial 2x^2 − x − 1 has the coefficient of the x^2 term positive.

Good: The leading coefficient of the polynomial 2x^2 − x − 1 is positive.

Bad: The inverse of the matrix A requires the determinant of A to be non-zero in order to exist, but the matrix A has zero determinant, and so its inverse does not exist.

Good: The matrix A has zero determinant, hence it has no inverse.
```

2. سعی کنین لغات مهم  و کلیدی یک جمله رو تو یک جایی بذارین که مخاطب با دیدن سریع اون جمله متوجه اون لغت بشه. مثلا مثال های زیر رو ببینین:

```python
Bad: An important example of a transcendental function is the logarithm.
Good: The logarithm is an important example of a transcendental function.
Good: Let us now define a key transcendental function: the logarithm.
Bad: A commonly used method to check the orthogonality of two vectors is to verify that their scalar product is zero.
Good: If the scalar product of two vectors is zero, then the vectors are orthogonal.
```

> orthogonal: متعامد، قائم.\
transcendental: ماورایی، غیرجبری

3. بجای فعل مجهول از فعل حال استفاده کنین.

```python
Bad: The convergence of the above series will now be established.
Good: We establish the convergence of the above series.
```

4. بجای تکرار کلمات و کسل کننده تر کردن متن کلمات رو  تغییر بدین.

```python
Bad: The function defined above is a function of both x and y.
Good: The function defined above depends on both x and y.
```
> monotony: یکنواختی

5. اگه معنی یک لغت رو دقیقا نمی‌دونید، ازش استفاده نکنین!

```python
Bad: A simplistic argument shows that our polynomial is irreducible.
Good: A simple argument shows that our polynomial is irreducible.
```