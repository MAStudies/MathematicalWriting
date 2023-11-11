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

### جلسه‌ی چهارم 

#### مجموعه‌ها

*مجموعه*: به یک کالکشن از اشیاء مشخص بدون ترتیب و متمایز گفته می‌شود که با کاما از هم جدا شده و داخل {} هستن گفته می‌شه مثلا `{1,2,3,4}`

```python
The set of all odd integers
The set of vertices of a pentagon
The set of differentiable real functions
```
*مولتی ست*: اگر تو یک مجموعه تکرار مجاز باشه اونوقت مولتی ست داریم.
*کثرت (multiplicity)*: به تعد تکرار‌های یک عضو تو یک مجموهخ کثرت اون شی گفته می‌شه.
*مجموعه‌ی تهی*: اگر تعداد اعصای یک مجموعه صفر باشه به اون مجموعه مجموعه‌ی تهی می‌گن. (‍∅)

برای اختصاص دادن یک نماد به یک شی ریاضی، از یک دستور (یا تعریف) استفاده می کنیم که دارای
نحو زیر:
  `A:= {1، 2، 3}`.

برای این که بگیم که شی ‍`x` یک عض. از مجموعه‌ی `A` هست به روش‌های زیر عمل می‌کنیم.

- x ∈ A
- x is an element of A 
- x belongs to A.

برای این که بگیم نیست بالایی‌ها رو برعکس می‌کنیم:

- 7 ∉ {5, {5, 7}}.

*زیر مجموعه*: به یک مجموعه گفته می‌شه که کل اعضاش عضو یک مجموعه‌ی دیگه باشن و اینجوری نوشته می‌شه.

- B ⊂ A
- B is a subset of A 
- B is contained in A

و برای این که بگیم نیست هم بالایی ها رو برعکس می‌کنیم یا به روش زیر عمل می‌کنیم:

- {2, 3} ⊄ {2, {2, 3}}.

هر مجموعه حداقل دو زیر مجموعه داره: خودش و مجموعه تهی. گاهی اوقات از اینا به عنوان زیر مجموعه های بی اهمیت یاد می شه.
هر زیر مجموعه دیگری - در صورت وجود - یک زیر مجموعه مناسب نامیده می شه.

*کاردینالیتی*: به تعداد اعضای یک مجموعه گفته می‌شه و با `#` نشونش می‌دن.

- #{7,−1, 0} =3 
- #A = n.
- |A| = n

*مجموعه‌ی متناهی*: به مجموعه‌ای که تعداد اعضاش عدد صحیح باشه مجموعه‌ی متناهی گفته می‌شه.

- اشتراک:  A ∩ B - intersection
-  A ∩ B = ∅, disjoint =  empty intersection

- A\B یعنی اعضای `A` به `B` تعلق ندارن.

- symmetric difference: یعنی اعضای مجموعه‌ها اشتراک مجموعه‌ها رو از تفاضلشون بندازیم بیرون. `AΔ B ≝ (A \ B) ∪ (B \ A)`.



|فارسی| انگلیسی | نماد | توضیح| مثال|
|--|--|--|--|--|
مجموعه | set | {} | یک کالکشن متمایز بدون ترتیب از اشیا | {1,2,3}
|مجموعه چندین | multiset | | یک مجموعه که در آن شرط متمایز بودن مهم نباشد. | {1,2,2,2,4}
کثرت | multiplicity | | تعداد تکرار یک عضو در یک مجموعه | |
مجموعه‌ی تهی| emptyset | ∅ | تعداد اعضای مجموعه صفر باشد. | {}
انتصاب | Assignment | := |برای اختصاص دادن یک نماد به یک شی ریاضی |A:= {1، 2، 3}
عضو بودن | belongs | ∈ | برای بیان این که یک شی عضو یک مجموعه هست | 1 ∈ {1,2,3}
عضو نبودن | don't belongs| ∉| یک شی عضو یک مجموعه نیست | 7 ∉ {1,2,3}
زیرمجموعه | subset | ⊂ | تمام اعضای یک مجموعه عضو یک مجموعه اند. | B ⊂ A
| | | ⊄ | | {1,2} ⊄ {1,3}
کاردینالیتی | cardinality | # or \| \| | تعداد اعضای یک مجموعه | #A = n
| مجموعه متناهی | finite set| | تعداد اعضاش عدد صحیح باشه | 
مجموعه نامتناهی | infinite set | | |
| اشتراک | intersection | ∩ | تعداد اعضای مشترک | A ∩ B = 2
از هم گسسته | disjoint | A ∩ B = ∅| اشتراک نداشته باشن | |
دو به دو از هم گسسته | pairwise disjoint  | | The sets ��1, ��2, . . . are 
pairwise disjoint if A ∩ ‌B = ∅ whenever i ≠ j | |
اجتماع | union | ∪ | در A یا B باشن. | A ∪ B = {1,2,3}
اختلاف | difference | \\ | مجموعه ای از چیزا که تو یه مجموعه هستن ولی تو مجموعه ی دیگه نیستن. | A\B = {2,3}
|  | symmetric difference | Δ | AΔ B ≝ (A \ B) ∪ (B \ A) | {1, 2, 3} Δ {3, 4, 5} = {1, 2, 4, 5}.
متمم | complement | A' | متمم|A' = {4,5,6,7}
مجموعه‌ی مرجع | ambient set | | |
زوج مرتب | ordered pair | (a, b) = (c, d) if a = c and b = d. | (1,2)
ضرب دکارتی | cartesian product | × | A × B | |


| Persian Translation | Word | Symbol | Definition in Persian | Example |
|----------------------|------|--------|------------------------|---------|
| مجموعه اعداد مختلط | Set of ordered pairs of complex numbers | ℂ² | - | - |
| مجموعه نقاط منطقی در دایره واحد | Set of rational points on the unit circle | - | - | *(𝑥, 𝑦) ∈ ℚ²: 𝑥² + 𝑦² = 1* |
| - | Set of fractions representing a rational number | - | - | - |
| - | Set of divisors of an odd integer | - | - | - |
| - | A proper infinite subset of the unit circle | - | - | - |
| ضرب دستی دو مجموعه متناهی اعداد مختلط | Cartesian product of two finite sets of complex numbers | - | - | - |
| مجموعه متناهی اعداد صحیح متوالی | Finite set of consecutive integers | - | - | - |
| - | The set whose only element is the integer 3 | - | Let 𝑋 = {3} | - |
| - | A set whose only element is an integer | - | Let 𝑋 = {𝑛} with 𝑛 ∈ ℤ | - |
| - | A set which contains a given integer | - | Let 𝑛 ∈ ℤ, and let 𝑋 be a set such that 𝑛 ∈ 𝑋 | - |
| - | A set which contains at least one integer | - | Let 𝑋 be a set such that 𝑋 ∩ ℤ ≠ ∅ | - |
| - | A set which contains precisely one integer | - | Let 𝑋 be a set such that #(𝑋 ∩ ℤ) = 1 | - |
| - | A proper infinite subset of a unit circle | - | - | - |
| - | The set whose only element is an integer 3 | - | - | - |
| - | The set which contains precisely one integer | - | - | - |
| - | The set whose only element is an integer | - | - | - |
| - | The intersection of a line and a conic section has at most two points | - | - | - |
| - | The set of rational points in any open interval is infinite | - | - | - |
| - | A cylinder is the cartesian product of a segment and a circle | - | - | - |
| - | The complement of the unit circle consists of two disjoint components | - | - | - |

| Persian Translation | Word | Symbol | Definition in Persian | Example |
|----------------------|------|--------|------------------------|---------|
| - | Definite Article (The) | - | - | - |
| - | Meaning “mentioned earlier”, “that” | - | - | Let 𝐴 ⊂ 𝐵. If 𝑓(𝑥) = 0 for every 𝑥 intersecting the set 𝐴, then ... |
| - | In front of a noun referring to a single, uniquely determined object | - | - | Let 𝑓 be the linear form defined by (2). So 𝑓 = 1 in the compact set 𝐶 of all points at distance 1 from 𝑃. |
| - | In the construction: the + property + of + object | - | - | The continuity of 𝑓 follows from ... |
| - | In front of a cardinal number if it embraces all objects considered | - | - | The two groups have been shown to have the same number of generators. |
| - | In front of an ordinal number | - | - | The first Poisson integral in (4) converges to 𝑔. |
| - | In front of surnames used attributively | - | - | The Dirichlet problem |
| - | In front of a noun in the plural referring to a class of objects as a whole | - | - | The real measures form a subclass of the complex ones. This class includes the Helson sets. |



| Persian Translation | Word | Symbol | Definition in Persian | Example |
|----------------------|------|--------|------------------------|---------|
| اعداد طبیعی | Natural numbers | ℕ | - | - |
| اعداد صحیح | Integers | ℤ | - | - |
| اعداد ریاضی | Rationals | ℚ | - | - |
| اعداد حقیقی | Real numbers | ℝ | - | - |
| اعداد مختلط | Complex numbers | ℂ | ℂ ≝ *𝑥 + 𝑦 ∶ 𝑥² + 𝑦² = −1, 𝑥, 𝑦 ∈ ℝ+* | 𝑧 = 𝑥 + 𝑦, 𝑥 = 𝑅𝑒(𝑧), 𝑦 = 𝐼𝑚(𝑧) |
| بازه | Interval | [𝑎, 𝑏] | {𝑥 ∈ ℝ : 𝑎 ≤ 𝑥 ≤ 𝑏} | [1, 5], [0, 2] |
| نقطه | Point | - | A degenerate closed interval: {𝑥 ∈ ℝ : 𝑎 = 𝑏} | {𝑎} |
| بازه باز | Open interval | (𝑎, 𝑏) | {𝑥 ∈ ℝ : 𝑎 < 𝑥 < 𝑏} | (1, 5), (0, 2) |
| نصف‌بازه | Half-open interval | [𝑎, 𝑏) (𝑎, 𝑏] | {𝑥 ∈ ℝ : 𝑎 < 𝑥 ≤ 𝑏} {𝑥 ∈ ℝ : 𝑎 ≤ 𝑥 < 𝑏} | [0, 1), (1, 2] |
| بازه واحد | Unit interval | [0, 1] | The interval with end-points 𝑎 = 0 and 𝑏 = 1 | [0, 1] |
| شعاع | Ray | - | {𝑥 ∈ ℝ : 𝑎 < 𝑥} or {𝑥 ∈ ℝ : 𝑥 > 𝑏} | ℝ+, ℝ- |
| اعداد مثبت | Positive numbers | ℝ⁺ | {𝑥 ∈ ℝ, 𝑥 > 0} | ℝ⁺ |
| اعداد مثبت ریاضی | Positive rational numbers | ℚ⁺ | {𝑥 ∈ ℚ , 𝑥 > 0} | ℚ⁺ |
| صفحه کارتزی | Cartesian plane | ℝ² | The set of all ordered pairs of real numbers | (𝑥, 𝑦) ∈ ℝ²: 𝑥 is abscissa, 𝑦 is ordinate |
| نقاط مختلط صحیح | Set of rational points in ℝ² | ℚ² | {𝑥 ∈ ℝ² : 𝑥 is rational} | (𝑥, 𝑦) ∈ ℚ² |
| مربع واحد | Unit square | ,0,1-² | {𝑥 ∈ ℝ² : 0 ≤ 𝑥 ≤ 1, 0 ≤ 𝑦 ≤ 1} | ,0,1-² |
| مکعب واحد | Unit cube | ,0,1-³ | {𝑥 ∈ ℝ³ : 0 ≤ 𝑥 ≤ 1, 0 ≤ 𝑦 ≤ 1, 0 ≤ 𝑧 ≤ 1} | ,0,1-³ |
| هایپرمکعب واحد | Unit hypercube | ,0,1-ⁿ | For 𝑛 > 3 in ℝⁿ | ,0,1-ⁿ |
| دایره واحد | Unit circle | 𝑆¹ | {(𝑥, 𝑦) ∈ ℝ² : 𝑥² + 𝑦² = 1} | 𝑆¹ |
| دایره واحد بسته | Closed unit disc | - | {(𝑥, 𝑦) ∈ ℝ² : 𝑥² + 𝑦² ≤ 1} | *{(𝑥, 𝑦) ∈ ℝ² : 𝑥² + 𝑦² = 1}* |
| دایره واحد باز | Open unit disc | - | {(𝑥, 𝑦) ∈ ℝ² : 𝑥² + 𝑦² < 1} | *{(𝑥, 𝑦) ∈ ℝ² : 𝑥² + 𝑦² ≤ 1, 𝑥² + 𝑦² < 1}* |
| کره واحد 𝑛-بعدی | n-dimensional unit sphere | 𝑆ⁿ | {(𝑥₀, ..., 𝑥𝑛) ∈ ℝⁿ⁺¹ : 𝑥₀² + ... + 𝑥𝑛² = 1} | 𝑆², 𝑆³, ... , 𝑆ⁿ |



Sets and Definitions

| Persian Translation | Word | Symbol | Definition in Persian | Example |
|----------------------|------|--------|------------------------|---------|
| اعداد طبیعی | Natural numbers | ℕ | ℕ := {1, 2, 3, . . .} | ℕ := {1, 2, 3, . . .} |
| اعداد صحیح | Integers | ℤ | ℤ := {. . . ,−2,−1, 0 , 1 , 2, . . .} or ℤ := {0,±1,±2, . . . } | ℤ := {0,±1,±2, . . . } |
| مجموعه خالی | Empty set | ∅ | ∅ ≝{x : x ≠ x} | ∅ ≝{x : x ≠ x} |
| اعداد ریاضی | Rational numbers | ℚ | ℚ := {𝑎/𝑏 : a ∈ ℤ, b ∈ ℕ, gcd(a, b) = 1} | ℚ := {𝑎/𝑏 : a ∈ ℤ, b ∈ ℕ, gcd(a, b) = 1} |

Set Definitions and Zermelo Definitions

| Persian Translation | Definition in Persian | Example |
|----------------------|------------------------|---------|
| تعریف مجموعه با زرملو | W := {x ∈ X : x has ��} | The set of real numbers strictly between 0 and 1 |
| تعریف مجموعه با زرملو | W := {x : x ∉ x} | W := {x : x ∉ x} |
| تعریف توان | x^y | 3^4 ≝ 3 · 3 · 3 · 3 |
| علامت تقسیم | 3 | 3 divides x (x is a multiple of 3) | 3 | 
| مضرب مشترک بزرگ و کمترین مضرب مشترک | gcd, lcm | - |

Arithmetic Notations

| Notation | Description | Example |
|-----------|-------------|---------|
| x + y, x - y | Sum and difference | 3 + 4, 3 - 4 |
| x × y, x ÷ y | Product and quotient | 3 × 4, 3 ÷ 4 |
| 1/x, -x | Reciprocal and opposite | 1/3, -3 |
| x^y | Exponentiation | 2^3 |
| x | y | Divisibility | 3 | 6 (3 divides 6) |

Divisibility and Primes

| Term | Definition | Example |
|------|------------|---------|
| proper divisor | Positive divisor of n, not 1 or n | Proper divisor of 12: 3 |
| prime | Integer > 1 with no proper divisors | Prime numbers: 2, 3, 5, ... |
| gcd, lcm | Greatest common divisor, least common multiple | gcd(12, 18) = 6, lcm(4, 5) = 20 |
| co-prime | Two integers with gcd = 1 | 15 and 28 are co-prime |



In writing mathematics, we use words and symbols to describe facts. We need to explain the meanings of words and symbols and to state and prove the facts. We'll be concerned with facts later. In this chapter and the next, we list mathematical words with accompanying notation. This is our essential mathematical dictionary. It contains some 200 entries, organized around few fundamental terms: set, function, sequence, equation. As we introduce new words, we use them in short phrases and sentences. Dictionaries are not meant to be read through, so don't be surprised if you find the exposition demanding. Take it in small doses. The last section of this chapter deals with advanced terminology and may be skipped on first reading.

Set
A set is a collection of well-defined, unordered, distinct objects. (This is the so-called 'naive definition' of a set, due to Cantor.) These objects are called the elements of a set, and a set is determined by its elements. We may write:

The set of all odd integers
The set of vertices of a pentagon
The set of differentiable real functions
In simple cases, a set can be defined by listing its elements, separated by commas, enclosed within curly brackets. The expression {1, 2, 3} denotes the set whose elements are the integers 1, 2, and 3.

It is customary to ignore repeated set elements: {2, 1, 3, 1, 3} = {2, 1, 3}. If repeated elements are allowed and not collapsed, then we speak of a multiset: {2, 1, 3, 1, 3}. The multiplicity of an element of a multiset is the number of times the element occurs. Reference to multiplicity usually signals that there is a multiset in the background.

Every quadratic equation has two complex solutions, counting multiplicities.

The set {} with no elements is called the empty set, denoted by the symbol ∅.

Assignment Operator
To assign a symbol to a mathematical object, we use an assignment statement (or definition), which has the following syntax: A := {1, 2, 3}. This expression assigns the symbolic name A to the set {1, 2, 3}, and now we may use the former in place of the latter. The symbol ‘:=’ denotes the assignment operator. It reads ‘becomes’, or ‘is defined to be’, rather than ‘is equal to’, to underline the difference between assignment and equality.

There are other symbols for the assignment operator, namely <-, =, and :=: which make an even stronger point. To indicate that x is an element of a set A, we write x ∈ A, x is an element of A, or x belongs to A. The symbol ∉ is used to negate membership.

Subset and Cardinality
A subset B of a set A is a set whose elements all belong to A. We write B ⊂ A or B is a subset of A and we use ⊄ to negate set inclusion.

Every set has at least two subsets: itself and the empty set. Sometimes these are referred to as the trivial subsets. Every other subset, if any, is called a proper subset.

The cardinality of a set is the number of its elements, denoted by # or | · |. A set is finite if its cardinality is an integer, and infinite otherwise.

Set Operations
A ∩ B: Intersection of sets A and B, containing elements that belong to both A and B.
A ∪ B: Union of sets A and B, containing elements that belong to A or B (or both).
A \ B: Set difference of A and B, containing elements of A that do not belong to B.
AΔB: Symmetric difference of A and B, defined as (A \ B) ∪ (B \ A).
Examples:

{1, 2, 3} ∩ {3, 4, 5} = {3}
{1, 2, 3} ∪ {3, 4, 5} = {1, 2, 3, 4, 5}
{1, 2, 3} \ {3, 4, 5} = {1, 2}
{1, 2, 3} Δ {3, 4, 5} = {1, 2, 4, 5}
Set operators have properties like commutativity and associativity, but set difference doesn't follow these properties.

Complement
Let A be a subset of a set X. The complement of A (in X) is the set X \ A, denoted by ��′ or by ����. The complement of a set is defined with respect to an ambient set X.

The odd integers are the complement of the even integers, where it's clear that the ambient set is the integers.

Ordered Pair and Cartesian Product
An ordered pair is an expression of the type (a, b), with a and b arbitrary quantities. Ordered pairs are defined by the property (a, b) = (c, d) if a = c and b = d. The ordered pair (a, b) should not be confused with the set {a, b}, since for pairs order is essential and repetition is allowed.

Let A and B be sets. The cartesian product of A and B is the set of all ordered pairs (a, b), with a in A and b in B, denoted as A × B. Note that A and B need not be distinct; one may write A^2 for A × A, A^3 for A × A × A, etc. The explicit presence of the multiplication operator ‘×’ is needed here because the expression AB has a different meaning.


Mathematical Writing
Chapter 1: Style

Clarity Over Fancy Language

Bad: We note the fact that the polynomial 
2
�
2
−
�
−
1
2x 
2
 −x−1 has the coefficient of the 
�
2
x 
2
  term positive.
Good: The leading coefficient of the polynomial 
2
�
2
−
�
−
1
2x 
2
 −x−1 is positive.
Inverse of a Matrix

Bad: The inverse of the matrix A requires the determinant of A to be non-zero in order to exist, but the matrix A has zero determinant, and so its inverse does not exist.
Good: The matrix A has zero determinant, hence it has no inverse.
Prominence of Important Words

Bad: An important example of a transcendental function is the logarithm.
Good: The logarithm is an important example of a transcendental function.
Good: Let us now define a key transcendental function: the logarithm.
Active Voice and Word Variation

Bad: The convergence of the above series will now be established.
Good: We establish the convergence of the above series.
Bad: The function defined above is a function of both x and y.
Good: The function defined above depends on both x and y.
Avoid Unfamiliar Words

Bad: A simplistic argument shows that our polynomial is irreducible.
Good: A simple argument shows that our polynomial is irreducible.


Chapter 1: Numbers and Symbols

Correct English Sentences with Numbers and Symbols

Bad: 
�
<
�
a<b, 
�
≠
0
a

=0
Good: We have 
�
<
�
a<b and 
�
≠
0
a

=0.
Good: We find that 
�
<
�
a<b and 
�
≠
0
a

=0.
Good: Let 
�
<
�
a<b, with 
�
≠
0
a

=0.
Omit Unnecessary Symbols

Bad: Every differentiable real function 
�
f is continuous.
Good: Every differentiable real function is continuous.
Number Representation

Bad: The equation has 4 solutions.
Good: The equation has four solutions.
Good: The equation has 127 solutions.
Bad: Both three and five are prime numbers.
Good: Both 3 and 5 are prime numbers.
Starting Sentences with Numerals or Symbols

Bad: 
�
ρ is a rational number with an odd denominator.
Good: The rational number 
�
ρ has an odd denominator.
Combining Operators with Words

Bad: The difference 
�
−
�
b−a is < 0.
Good: The difference 
�
−
�
b−a is negative.
Misuse of Implication and Therefore Symbols

Bad: 
�
a is an integer 
⇒
�
⇒a is a rational number.
Good: if 
�
a is an integer, then 
�
a is a rational number.
Bad: 
⇒
�
=
3
⇒x=3.
Bad: 
∴
�
=
3
∴x=3.
Good: hence 
�
=
3
x=3.
Separation of Formulae or Symbols by Words

Bad: Consider 
�
�
A 
n
​
 , 
�
<
5
n<5.
Bad: Add 
�
p 
�
k times to 
�
c.
Bad: Add 
�
p to 
�
c 
�
k times.
Good: Add 
�
p to 
�
c, repeating this process 
�
k times.
GRAMMAR Part1: INDEFINITE ARTICLE (a, an, ----)

Instead of the Number “One”

Examples: The four centers lie in a plane.
A chapter will be devoted to the study of expanding maps.
Meaning “Member of a Class of Objects”, “Some”, “One Of”

Examples: Then 
�
D becomes a locally convex space with dual space 
�
′
D 
′
 .
The right-hand side of (4) is then a bounded function.
In Definitions of Classes of Objects

Examples: A fundamental solution is a function satisfying .....
We wish to find a solution of (6) which is of the form .....
In the Plural—When Referring to Each Element of a Class

Examples: Direct sums exist in the category of abelian groups.
In particular, closed sets are Borel sets.
In Front of an Adjective Which Means “Having This Particular Quality”

Examples: This map extends to all of 
�
M in an obvious fashion.
A remarkable feature of the solution should be stressed.