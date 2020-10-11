# Git Markdown codes

### Heading

#### Syntax
```git
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```

#### Appearance
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6


### Font

#### Syntax
```git
*Italics*
**Bold text**
***Bold and Italics***
~~Striked Text~~
```

#### Appearance

*Italics*

**Bold Text**

***Bold and Italics***

~~Striked Text~~


### Lists(Unordered and Ordered)

#### Syntax
Unordered list
```git
* list1
* list2
  * sublist1
  * sublist2
```

#### Appearance
* List item-1
* List item-2
  * Sublist-1
  * Sublist-2

Ordered list
```
1. First
2. Second
3. Third
    1. Three / One
    2. Three / Two 
4. Fourth
```
#### Appearance
1. First item
2. Second item
3. Third item
    1. Indented item
    2. Indented item
4. Fourth item


### Links

#### Syntax
```git
* [This is a link to GitHub](https://github.com "GitHub Home Page")
* <https://www.google.com/>
```
#### Appearance
* [This is a link to GitHub](https://github.com "GitHub Home Page")
* <https://www.google.com/>


### Images
#### Syntax
```
 ![GitHub Logo](https://cdn4.iconfinder.com/data/icons/iconsimple-logotypes/512/github-512.png "GitHub Logo")
```
As same as links, but add an exlamation mark (!) before opening square bracket.  
The square bracket contains `alt` for the image and parenthesis contains image source.  
Image source can be either a location from the local machine or any valid image URL.  
the last part contains additional information about the image shown when use hovers through it.
#### Appearence
 ![GitHub Logo](https://cdn4.iconfinder.com/data/icons/iconsimple-logotypes/512/github-512.png "GitHub Logo")
 

### Linking Image
To open another webpage when image is clicked, enclose the Markdown for the image in brackets, and then add the link in parentheses.

#### Syntax
```
 [![GitHub Logo](https://cdn4.iconfinder.com/data/icons/iconsimple-logotypes/512/github-512.png "GitHub Logo")](https://github.com/)
```

#### Appearance
[![GitHub Logo](https://cdn4.iconfinder.com/data/icons/iconsimple-logotypes/512/github-512.png "GitHub Logo")](https://github.com/)


### Tables

#### Syntax
```git
|Header1|Header2|Header3|
| --- | --- | --- |
| This | is a | table |
| This | is 2nd | row |
| This | is 3rd | row |
```

#### Appearance
|Header1|Header2|Header3|
| --- | --- | --- |
| This | is a | table |
| This | is 2nd | row |
| This | is 3rd | row |


### CheckBox

#### Syntax
```git
* [ ] Checkbox1

* [ ] Checkbox2

* [x] Checkbox selected
```

#### Appearance

* [ ] Checkbox1

* [ ] Checkbox2

* [x] Checkbox selected


### Block Quotes

#### Syntax
```git
> This is a block quoted text
```

#### Appearance
> This is a block quoted text


### Horizontal Line
#### Syntax
```git
***
___
--- 
```
#### Appearance
All three will be rendered as:
___


### Code Block
There are three ways to add code in markdown
1. Inline Code (single backtick)
1. Whitespace (Four Spaces Indentation)
1. Fenced Code Block (Three Backticks *or* Tildes)

#### Syntax
    `this` is an example of inline code.
    
    '''
    console.log('Used backticks to show snippets')
    '''
    
    console.log('four whitespace works too!')
    
    
#### Appearance
`this` is an example of inline code.
```
console.log('Used backticks to show snippets')
```
    console.log('four whitespace works too!')
    

### Syntax Highlighting
If language name is mentioned after the end of first set of backticks, the code snippet will be highlighted according to the language.

#### Syntax
    ```js
    console.log('javascript')
    ```
    
    ```python
    print('python')
    ```
    
    ```java
    System.out.println('java')
    ```
       
    ```json
    {
      "firstName": "Kaushal",
      "lastName": "Joshi
      "age": 18
    }
    ```



#### Appearance 
```js
console.log('javascript')
```

```python
print('python')
```

```java
System.out.println('java')
```

```json
{
  "firstName": "Kaushal",
  "lastName": "Joshi",
  "age": 18
}
```
####Emphasis
```
*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_
```
