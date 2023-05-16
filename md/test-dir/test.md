$$
$$

For example:

$$
f(x) = \int_{-\infty}^\infty
	\hat f(\xi)\,e^{2 \pi i \xi x}
	\,d\xi
$$



$$\hat{y} = \sigma(w^{T}x+b) = \frac{1}{1+e^{-w^{T}x+b}}$$
    $$cost = \frac{-1}{m} \cdot \sum_{i=o}^{m} [y \cdot log(\hat{y}) + (1 - y)log(1-\hat{y})]$$


```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```
```mermaid
sequenceDiagram
    participant Alice
    participant Bob
    Alice->>John: Hello John, how are you?
    loop Healthcheck
        John->>John: Fight against hypochondria
    end
    Note right of John: Rational thoughts <br/>prevail!
    John-->>Alice: Great!
    John->>Bob: How about you?
    Bob-->>John: Jolly good!
```

```mermaid

gantt
dateFormat  YYYY-MM-DD
title Adding GANTT diagram to mermaid
excludes weekdays 2014-01-10

section A section
Completed task            :done,    des1, 2014-01-06,2014-01-08
Active task               :active,  des2, 2014-01-09, 3d
Future task               :         des3, after des2, 5d
Future task2               :         des4, after des3, 5d
```

```mermaid
classDiagram
Class01 <|-- AveryLongClass : Cool
Class03 *-- Class04
Class05 o-- Class06
Class07 .. Class08
Class09 --> C2 : Where am i?
Class09 --* C3
Class09 --|> Class07
Class07 : equals()
Class07 : Object[] elementData
Class01 : size()
Class01 : int chimp
Class01 : int gorilla
Class08 <--> C2: Cool label
```

```mermaid
journey
    title My working day
    section Go to work
      Make tea: 5: Me
      Go upstairs: 3: Me
      Do work: 1: Me, Cat
    section Go home
      Go downstairs: 5: Me
      Sit down: 5: Me

```

```mermaid
erDiagram
    CUSTOMER ||--o{ ORDER : places
    ORDER ||--|{ LINE-ITEM : contains
    CUSTOMER }|..|{ DELIVERY-ADDRESS : uses

```

![Benjamin Bannekat](https://octodex.github.com/images/bannekat.png)
silly cat image


<img src="https://media.tenor.com/cX92mi1p-NYAAAAd/coding-anime.gif" height="300" align="center"/>
</div>

# Heading 1
## Heading 2
## Heading 3

**bold text**
*italic text*
>Josh: What button do we pwess?
>Me: Nothing yet son...
>Neep: This is too easy sensei! 
Unordered List(-,*,+):
* Bacon
* Eggs
* Cheese
* Tortillas
* Juice

Ordered List:
1. Title
2. Table of Contents
   1. recognition
   2. thank you message
3. Chapter 1
4. Etc.

Inline code 	

This is `someJavaScript()`

Code block 	

Here's some JavaScript code:

```
function hello() {
    alert('hello');
}
```

Language is normally auto-detected,
but it can also be specified:

```sql
SELECT * FROM users;
DELETE FROM sessions;
```

Horizontal Rule 	
---
One rule:
***
Another rule:
___

<https://eff.org>
2
<fake@example.com>


Link, you can find original text here: [Simple MD Documentation](https://joplinapp.org/markdown/#math-notation)
---
This is detected as a link:

https://joplinapp.org

And this is a link anchoring text content:

[Joplin](https://joplinapp.org)

And this is a link, with a title,
anchoring text content:

[Joplin](https://joplinapp.org "Joplin project page")


Images 	

![Joplin icon](https://git.io/JenGk)


Tables🔗

Tables are created using pipes | and hyphens -. This is a Markdown table:

| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

Checkboxes🔗

Checkboxes can be added like so:

- [ ] Milk
- [x] Rice
- [ ] Eggs

This is <s>strikethrough text</s> mixed with regular **Markdown**.
==marked==

Simples inline footnote ^[I'm inline!]




I really like using Markdown.

I think I'll use it from now on.