## css-cascadding style sheets
id:-#id
class:-.class
tag:-tag


::before is used to set somthing before text
ex:-.class::before{//after
    content:url();
}
Selectors-Property
color:-used t o give color of text
    1.red
    2.blue.......
text-align:used to give position
    1.left
    2.right
    3.center
background-color:-used to give the color of background
anchor tag
    1.link:-unvisited color
    2.visites:-visites color
    3.hover:-move mouse to the link change color
    4.active:-when we click the link
    ex:-a:hover{}
    Note:-hover must come after link and visited in css 
    definition to be selected
    active must come after hober to be efective
font-variant:-is used to set the text format//it only apply block -level elements
1.Simple Selectors
    -Based on name/tag
    -Based on id
    -Based on class
2.CSS Combinators:-it explains the relationship between Selectors
    -Desendant Selector(space)
    -child selector(>):-it is used to check the direct tag ans apply to that tag
    -Adjacent sibbling(+):-is used to select imediate after the tag
    ex:-div+p
    tillde(~):-used to select all tags after div
    ex:-div~p
3.pseudo classe:-used to define a special state of an element mainly link
4.pseudo elements:-used to style specified part of an element
    ex:-.pseudoele::first-line{}
    ::before is used to set somthing before text
    ex:-.class::before{//after
    content:url();
    }
    ::marker
    ::selection//when ever we select it will