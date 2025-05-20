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
  - [Множества](#множества)
    - [Отношения](#отношения)
  - [Отображение](#отображение)
  - [Потолок/пол](#потолокпол)
  - [Предел](#предел)
  - [Произведение](#произведение)
  - [Равенство по определению](#равенство-по-определению)
  - [Сумма](#сумма)
  - [Троеточия](#троеточия)
  - [Умножение](#умножение)

## Греческий алфавит

| Символ                          | По-русски | LaTeX                           | По-английски         |
| ------------------------------- | --------- | ------------------------------- | -------------------- |
| $\alpha$, $\Alpha$              | альфа     | `\alpha`, `\Alpha`              | alpha `/ˈælfə/`      |
| $\beta$, $\Beta$                | бета      | `\beta`, `\Beta`                | beta `/ˈbeɪtə/`      |
| $\gamma$, $\Gamma$              | гамма     | `\gamma`, `\Gamma`              | gamma `/ˈɡæmə/`      |
| $\delta$, $\Delta$              | дельта    | `\delta`, `\Delta`              | delta `/ˈdɛltə/`     |
| $\epsilon$, $\Epsilon$          | эпсилон   | `\epsilon`, `\Epsilon`          | epsilon `/ˈɛpsɪlɒn/` |
| $\zeta$, $\Zeta$                | зета      | `\zeta`, `\Zeta`                | zeta `/ˈzeɪtə/`      |
| $\eta$, $\Eta$                  | эта       | `\eta`, `\Eta`                  | eta `/ˈeɪtə/`        |
| $\theta$, $\Theta$              | тета      | `\theta`, `\Theta`              | theta `/ˈθeɪtə/`     |
| $\iota$, $\Iota$                | йота      | `\iota`, `\Iota`                | iota `/aɪˈoʊtə/`     |
| $\kappa$, $\Kappa$              | каппа     | `\kappa`, `\Kappa`              | kappa `/ˈkæpə/`      |
| $\lambda$, $\Lambda$            | лямбда    | `\lambda`, `\Lambda`            | lambda `/ˈlæmdə/`    |
| $\mu$, $\Mu$                    | мю        | `\mu`, `\Mu`                    | mu `/mjuː/`          |
| $\nu$, $\Nu$                    | ню        | `\nu`, `\Nu`                    | nu `/njuː/`          |
| $\xi$, $\Xi$                    | кси       | `\xi`, `\Xi`                    | xi `/ksaɪ/`          |
| $o$, $O$                        | омикрон   | `o`, `O`                        | omicron `/ˈɒmɪkrɒn/` |
| $\pi$, $\varpi$, $\Pi$          | пи        | `\pi`, `\varpi`, `\Pi`          | pi `/ˈpaɪ/`          |
| $\rho$, $\varrho$, $\Rho$       | ро        | `\rho`, `\varrho`, `\Rho`       | rho `/roʊ/`          |
| $\sigma$, $\varsigma$, $\Sigma$ | сигма     | `\sigma`, `\varsigma`, `\Sigma` | sigma `/ˈsɪɡmə/`     |
| $\tau$, $\Tau$                  | тау       | `\tau`, `\Tau`                  | tau `/ˈtaʊ/`         |
| $\upsilon$, $\Upsilon$          | ипсилон   | `\upsilon`, `\Upsilon`          | upsilon `/ˈʌpsɪlɒn/` |
| $\phi$, $\varphi$, $\Phi$       | фи        | `\phi`, `\varphi`, `\Phi`       | phi `/faɪ/`          |
| $\chi$, $\Chi$                  | хи        | `\chi`, `\Chi`                  | chi `/kaɪ/`          |
| $\psi$, $\Psi$                  | пси       | `\psi`, `\Psi`                  | psi `/psaɪ/`         |
| $\omega$, $\Omega$              | омега     | `\omega`, `\Omega`              | omega `/ˈoʊmɛɡə/`    |

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
| $\neq$                    | Не равно                                          | `\neq`                    |

## Множества

```text
\varnothing
```

$\varnothing$

### Отношения

```text
x \in X, x \notin X
x \ni X, x \notni X
```

$x \in X$, $x \ni X$ — «есть элемент множества»

$x \notin X$, $x \notni X$

## Отображение

```text
X \to Y
X \xrightarrow{f} Y
dx \mapsto f(x)
```

$X \to Y$

$X \xrightarrow{f} Y$

$x \mapsto f(x)$

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

## Равенство по определению

```text
a \coloneqq b
```

$a \coloneqq b$

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
