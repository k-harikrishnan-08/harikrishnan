FLEX box is layout module that provides an efficient way to arrange and align the html elements within a container.

why flex is used ? 
flex-box is used to create a dynamic and responsive layouts, making it easier to align and distribute elements within elements within a container.

advantage of flex-box
- **simplified layout**
- **responsive design**
- **axis**
- **flex property**

Role of axis, display and flex property :   ---- **default axis is row**
	flex layout work along two axis: main axis and cross axis
		The main axis is defined by **flex-direction** property , which can be set to  row or column, determining the direction of the layout . the cross axis is perpendicular to the main axis. 

The display property is set to flex to establish a flex container and enable flex layout on its child elements.

flex properties :

**justify-content:**

| flex-start | Default value. Items are positioned at the beginning of the container |
| ---- | ---- |
| flex-end | Items are positioned at the end of the container |
| center | Items are positioned in the center of the container |
| space-between | Items will have space between them |
| space-around | Items will have space before, between, and after them |
| space-evenly | Items will have equal space around them |
| initial | Sets this property to its default value. [Read about _initial_](https://www.w3schools.com/cssref/css_initial.php) |
| inherit | Inherits this property from its parent element. [Read about _inherit_](https://www.w3schools.com/cssref/css_inherit.php) |
**align-items:**


| Value | Description |
| ---- | ---- |
| normal | Default. Behaves like 'stretch' for flexbox and grid items, or 'start' for grid items with a defined block size. |
| stretch | Items are stretched to fit the container |
| center | Items are positioned at the center of the container |
| flex-start | Items are positioned at the beginning of the container |
| flex-end | Items are positioned at the end of the container |
| start | Items are positioned at the beginning of their individual grid cells, in the block direction |
| end | Items are positioned at the end of the their individual grid cells, in the block direction |
| baseline | Items are positioned at the baseline of the container |
| initial | Sets this property to its default value. [Read about _initial_](https://www.w3schools.com/cssref/css_initial.php) |
| inherit | Inherits this property from its parent element. [Read about _inherit_](https://www.w3schools.com/cssref/css_inherit.php) |

align-content:

| stretch | Default value. Lines stretch to take up the remaining space |
| ---- | ---- |
| center | Lines are packed toward the center of the flex container |
| flex-start | Lines are packed toward the start of the flex container |
| flex-end | Lines are packed toward the end of the flex container |
| space-between | Lines are evenly distributed in the flex container |
| space-around | Lines are evenly distributed in the flex container, with half-size spaces on either end |
| space-evenly | Lines are evenly distributed in the flex container, with equal space around them |
| initial | Sets this property to its default value. [Read about _initial_](https://www.w3schools.com/cssref/css_initial.php) |
| inherit | Inherits this property from its parent element. [Read about _inherit_](https://www.w3schools.com/cssref/css_inherit.php) |

flex-direction:

| row | Default value. The flexible items are displayed horizontally, as a row |
| ---- | ---- |
| row-reverse | Same as row, but in reverse order |
| column | The flexible items are displayed vertically, as a column |
| column-reverse | Same as column, but in reverse order |
| initial | Sets this property to its default value. [Read about _initial_](https://www.w3schools.com/cssref/css_initial.php) |
| inherit | Inherits this property from its parent element. [Read about _inherit_](https://www.w3schools.com/cssref/css_inherit.php) |

order:

| _number_ | Default value 0. Specifies the order for the flexible item |
| ---- | ---- |
| initial | Sets this property to its default value. [Read about _initial_](https://www.w3schools.com/cssref/css_initial.php) |
| inherit | Inherits this property from its parent element. [Read about _inherit_](https://www.w3schools.com/cssref/css_inherit.php) |

flex-wrap:

| nowrap | Default value. Specifies that the flexible items will not wrap |  |
| ---- | ---- | ---- |
| wrap | Specifies that the flexible items will wrap if necessary |  |
| wrap-reverse | Specifies that the flexible items will wrap, if necessary, in reverse order |  |
| initial | Sets this property to its default value. [Read about _initial_](https://www.w3schools.com/cssref/css_initial.php) |  |
| inherit | Inherits this property from its parent element. [Read about _inherit_](https://www.w3schools.com/cssref/css_inherit.php) |  |

CSS COMBINATORS : the final selector we will look at are called combinators. (.parent **child**) because they combine other selectors in a way that gives them a useful relationship to each other and the location  of content in the document.

DESCENDANT COMBINATOR :

typically represented by a single space ( ) character - combines two selectors such that elements matched by the second selector are selected if they have an ancestor (parent , parent's parent , etc) element matching the **first selector** .selectors that utilize a descendant combinator are called descendant selectors.

eg :           .parent div{     inside parent all div targeted

}

CHILD COMBINATOR:

the child combinator > is placed between  two css selectors . it matches only those elements matched by the **first. descendant elements** further down the hierachy don't match . for example , to select only <p> elements that are direct children of <article> elements.

eg .            .parent > div {     inside parent first direct "child" divs are targeted & descendant child are not targeted

}

ADJACENT SIBILING COMBINATOR :

the adjacent sibiling selector (+) is placed between two selectors .it matches  only those elements  matched by the second .