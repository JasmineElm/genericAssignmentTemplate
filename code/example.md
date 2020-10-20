## Introduction {-}

Excepteur eiusmod exercitation est consequat non exercitation consequat cillum
excepteur duis. Velit laborum cupidatat anim culpa sunt. Deserunt mollit tempor
sit ex aute cillum culpa adipisicing culpa ut. Minim nisi amet Lorem ullamco ea
incididunt ad enim minim. Est anim ipsum magna aliquip id sunt nisi laboris
excepteur cupidatat amet dolore minim. Veniam proident sint qui officia ut do
consequat et pariatur irure culpa anim.

## Section 1 {-}

Using tables is easy, simple `markdown` syntax works out of the box, for bonus marks, you can use the `: your text here` syntax to caption the tables.  This syntax filters through to base `LaTeX` syntax, meaning it'll appear if you use the `lot` tag in YAML.

| Don't | Open   |
|-------|--------|
|  Dead | Inside |

: Here is a figure for the table

```BASH
for i in {0..9}; do echo $i; done
``` 

another language...

```python
for i in range(0,9):
    print($i)
```

 and a third for good measure

```sql 
select sysdate from dual
```

### Section 1.1   {-}

----

1. numbered 
1. lists 
1. for the win

@) numbered 
@) lists 

split by text

@) work with special syntax

don't confuse it with the pandoc-cite syntax (e.g.  @chatfieldchatfield_how_2012 )


some useful tests / syntax...

_italic_

__bold__

[small caps]{.smallcaps} aren't supported in vanilla markdown, but are in
pandoc...

<http://simple_url_render.com>

[more complex url render](http://example.com)

[my email](mailto:email@address.com)


reference link [example][]

[example]: https://james-lemin.com "my website"

DefinitionTerm

:   Definition

~~strike through~~

Super^script^

Sub~script~

$tex$ math formulae $f(x) = x^2$

![Hello World image](figures/hw.png){height=200px}

### A level-three heading with a [link](/url) and *emphasis*

Veniam velit occaecat quis culpa ex cupidatat Lorem nulla qui. Officia qui nisi esse et sint velit incididunt. Dolore non dolore quis officia.

## Conclusion {-}

Adipisicing magna ad proident Lorem aliqua quis aliquip ipsum sunt. Consequat ea
proident et adipisicing exercitation cillum officia ipsum ad. Minim in commodo
pariatur dolor Lorem qui aute tempor. Minim sint in amet dolor fugiat cillum
proident labore eiusmod mollit elit excepteur ex elit. Duis esse excepteur
laborum nostrud veniam incididunt anim aliqua proident ea aliquip irure ad. Aute
consectetur ullamco amet non. Est eiusmod occaecat culpa pariatur eu dolore.
@botton_seeing_2005. See [here](foo) for more info

\pagebreak

## References {-}

_Want References to appear somewhere specific?_ `<div id="refs"></div>` will
sort you out!


<div id="refs"></div>

\pagebreak

## Glossary {-}

Lorem amet magna et ex amet voluptate. Est excepteur sint labore reprehenderit
eu reprehenderit anim cillum laborum pariatur aliquip proident pariatur do. Est
dolor amet anim nulla fugiat veniam nostrud nulla. Sint incididunt excepteur
officia non commodo commodo dolor reprehenderit aliqua sint mollit voluptate
enim nulla.

