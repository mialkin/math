# LaTeX

**LaTeX** — программная система для подготовки документов.

LaTeX широко используется в научных кругах для публикации научных документов во многих областях, включая математику, информатику, инженерные науки, физику, химию, экономику, лингвистику, философию и политологию.

## Содержание

- [LaTeX](#latex)
  - [Содержание](#содержание)
  - [Греческий алфавит](#греческий-алфавит)
  - [Режимы](#режимы)
    - [Встроенный](#встроенный)
    - [Выделенный](#выделенный)
  - [Ажурные буквы](#ажурные-буквы)
  - [Бесконечность](#бесконечность)
  - [Дробь](#дробь)
  - [Интеграл](#интеграл)
  - [Интервалы](#интервалы)
  - [Корень](#корень)
  - [Логарифм](#логарифм)
  - [Логические символы](#логические-символы)
  - [Потолок/пол](#потолокпол)
  - [Предел](#предел)
  - [Произведение](#произведение)
  - [Сумма](#сумма)
  - [Троеточия](#троеточия)
  - [Умножение](#умножение)

## Греческий алфавит

| Символ                 | По-русски | LaTeX                  | По-английски            |
| ---------------------- | --------- | ---------------------- | ----------------------- |
| $\alpha$, $\Alpha$     | альфа     | `\alpha`, `\Alpha`     | alpha `/ˈælfə/`         |
| $\theta$, $\Theta$     | тета      | `\theta`, `\Theta`     | theta `/ˈθeɪtə/`        |
| $\lambda$, $\Lambda$   | лямбда    | `\lambda`, `\Lambda`   | lambda `/ˈlæmdə/`       |
| $\pi$, $\varpi$, $\Pi$ | пи        | `\pi`, `\varpi`, `\Pi` | pi `/ˈpaɪ/`             |
| $\sigma$, $\Sigma$     | сигма     | `\sigma`, `\Sigma`     | sigma `/ˈsɪɡmə/`        |
| $\tau$, $\Tau$         | тау       | `\tau`, `\Tau`         | tau `/ˈtaʊ, ˈtɔː, ˈtɒ/` |
| $\Xi, \xi$             | кси       | `\xi`, `\Xi`           | chi `/kaɪ/`             |

https://www.overleaf.com/learn/latex/List_of_Greek_letters_and_math_symbols

## Режимы

Math mode has two main modes: display mode and inline mode. Inline mode is for math that is included within a line or paragraph of text, and display mode is for math that is set apart from the main text.

### Встроенный

The TeX delimiters for inline math are `$` and `$.`

The LaTeX delimiters for inline math are `\(` and `\)`.

### Выделенный

The TeX delimiters for displayed math are `$$` and `$$.`

The LaTeX delimiters for displayed math are `\[` and `\]`.

## Ажурные буквы

`\mathbb` — команда которая преобразует шрифт заглавных и строчных букв к ажурному.

```text
\mathbb{R}
```

$\mathbb{R}$

## Бесконечность

```text
\infty
```

$\infty$

## Дробь

```text
\tfrac{1}{2}
\dfrac{1}{2}
\frac{a + b}{c}
```

$\frac{a + b}{c}$

$\dfrac{a + b}{c}$

$\tfrac{a + b}{c}$

`\tfrac` forces the fraction into text mode, no matter which mode it is in already.

`\dfrac` forces the fraction into display mode, no matter which mode it is in already.

`\frac`: the actual context implies the decision above.

## Интеграл

```text
\int_{a}^{b} x^2 \,dx
```

$\int_{a}^{b} x^2 \,dx$

$$\int_{a}^{b} x^2 \,dx$$

## Интервалы

```text
$f(x) = x^2 + 2x + 1$
$f(x) = x^2 \; + 2x \; + 1$
$f(x) = x^2 \quad + 2x \quad + 1$
$f(x) = x^2 \qquad + 2x \qquad + 1$
```

$f(x) = x^2 + 2x + 1$

$f(x) = x^2 \; + 2x \; + 1$

$f(x) = x^2 \quad + 2x \quad + 1$

$f(x) = x^2 \qquad + 2x \qquad + 1$

[↑ Spacing in math mode](https://www.overleaf.com/learn/latex/Spacing_in_math_mode)

| Команда  | Описание                                                                                                        |
| -------- | --------------------------------------------------------------------------------------------------------------- |
| `\quad`  | Интервал, равный текущему размеру шрифта (= 18 [↑ `mu`](https://www.overleaf.com/learn/latex/Lengths_in_LaTeX)) |
| `\,`     | 3/18 от `\quad` (= 3 mu)                                                                                        |
| `\:`     | 4/18 от `\quad` (= 4 mu)                                                                                        |
| `\;`     | 5/18 от `\quad` (= 5 mu)                                                                                        |
| `\!`     | -3/18 от `\quad` (= -3 mu)                                                                                      |
| `\`      | Интервал после обратного слэша, эквивалентен пробелу в обычном тексте                                           |
| `\qquad` | Двойной интервал `\quad` (= 36 mu)                                                                              |

## Корень

```text
\sqrt{9}
\sqrt[a]{d}
```

$\sqrt{9}$

$\sqrt[a]{d}$

## Логарифм

```text
\log_{b} a
\ln x
```

$\log_{b} a$

$\ln x$

## Логические символы

| Символ                    | Описание                                          | LaTeX                     |
| ------------------------- | ------------------------------------------------- | ------------------------- |
| $\Rightarrow$, $\implies$ | Импликация, влечет                                | `\Rightarrow`, `\implies` |
| $\Leftrightarrow$, $\iff$ | Равносильно, тогда и только тогда, if and only if | `\Leftrightarrow`, `\iff` |
| $\land$, $\wedge$         | Конъюнкция, логическое "и"                        | `\land`, `\wedge`         |
| $\lor$, $\vee$            | Дизъюнкция, логическое "или"                      | `\lor`, `\vee`            |
| $\lnot$                   | Отрицание                                         | `\lnot`                   |
| $\forall$                 | Квантор всеобщности                               | `\forall`                 |
| $\exists$                 | Квантор существования                             | `\exists`                 |

## Потолок/пол

```text
\lceil \rceil
\rfloor \rfloor
```

$\lceil$ $\rceil$

$\lfloor$ $\rfloor$

## Предел

```text
\lim_{x\to\infty} f(x)
```

$\lim_{x\to\infty} f(x)$

$$\lim_{x\to\infty} f(x)$$

## Произведение

```text
\prod_{i=a}^{b} f(i)
```

$\prod_{i=a}^{b} f(i)$

$$\prod_{i=a}^{b} f(i)$$

## Сумма

```text
\sum_{i=1}^{n}a_i
```

$\sum_{i=1}^{n}a_i$

$$\sum_{i=1}^{n}a_i$$

## Троеточия

```text
\cdots
\ldots
\vdots
\ddots
```

$\cdots$

$\ldots$

$\vdots$

$\ddots$

## Умножение

`\cdot` — vertically centred dot, вертикально центрированная точка.

```text
$1 \cdot 2$
$1 \times 2$
```

$1 \cdot 2$

$1 \times 2$
