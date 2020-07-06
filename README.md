![Markdown Guide](https://github.com/AndrewFakher/Markdown-Guide/blob/master/markdown-guide-og.jpg)
<h1 align="center">Markdown Guide</h1>
<p align="center">
	This Markdown cheat sheet provides a quick overview of most the Markdown syntax elements.
</p>

## 1. Badges
[Shields.io](https://shields.io) contains quality metadata badges for open source projects.

```markdown
[![Build Status](https://img.shields.io/travis/markdown-it/markdown-it-deflist/master.svg?style=flat)](https://shields.io)  
[![Coverage Status](https://img.shields.io/coveralls/markdown-it/markdown-it-deflist/master.svg?style=flat)](https://shields.io)
```
[![Build Status](https://img.shields.io/travis/markdown-it/markdown-it-deflist/master.svg?style=flat)](https://shields.io)
[![Coverage Status](https://img.shields.io/coveralls/markdown-it/markdown-it-deflist/master.svg?style=flat)](https://shields.io)

## 2. Check List
```markdown
- [ ] item 1
- [x] item 2
```
- [ ] item 1
- [x] item 2

## 3. Ordered List
```markdown
1. First item
2. Second item
3. Third item
```
1. First item
2. Second item
3. Third item

## 4. Sub Ordered List
```markdown
1. First item
2. Second item
3. Third item
    1. Indented item
    2. Indented item
```
1. First item
2. Second item
3. Third item
    1. Indented item
    2. Indented item

## 5. Unordered List
```markdown
- First item
- Second item
- Third item
```
- First item
- Second item
- Third item

## 6. Sub Unordered List
```markdown
- First item
- Second item
- Third item
    - Indented item
    - Indented item
```
- First item
- Second item
- Third item
    - Indented item
    - Indented item
  
## 7. Nested lists
```markdown
- First item
  - sub-item
    - sub-sub-item
```
- First item
  - sub-item
    - sub-sub-item
    
## 8. Dropdown Menu
```html
  <details>
	<summary><code>Swift 5.2</code> </summary>

	Released July 15, 2019	<br>
	<a href='https://github.com/AndrewFakher/GitDemo/blob/master/github.png'><code>Screenshot</code></a> 
  </details>
```
- [Swift](https://swift.org/about/): Check Swift Documentation 
  <details>
	<summary><code>Swift 5.2</code> </summary>

	Released July 15, 2019	<br>
	<a href='https://github.com/AndrewFakher/GitDemo/blob/master/github.png'><code>Screenshot</code></a> 
  </details>
  
    <details>
	<summary><code>Swift 5</code> </summary>
   
	Released March 25, 2019<br>
	<a href='https://github.com/AndrewFakher/GitDemo/blob/master/github.png'><code>Screenshot</code></a> 
  </details>

## 9. Text Format
```markdown
**bold text**
*italicized text*
~~The world is flat.~~
```
**bold text**  
*italicized text*  
~~The world is flat.~~

## 10. Definitions
```markdown
Markdown
: Markdown is a lightweight markup language with plain text formatting syntax. Its design allows it to be converted to many output formats, but the original 
tool by the same name only supports HTML.
```
Markdown
: Markdown is a lightweight markup language with plain text formatting syntax. Its design allows it to be converted to many output formats, but the original 
tool by the same name only supports HTML.

## 11. Footnote
```html
<sup>1</sup>This is the first footnote.
```
<sup>1</sup>This is the first footnote.

## 12. New line
You can make a new line by ending a line with two spaces  
you don't have to use `<br>`.

## 13. Blockquote
```markdown
> blockquote
```
> blockquote

### 14. Nested blockquote
```markdown
> blockquote
>> nested blockquote
```
> blockquote
>> nested blockquote

## 15. Keyboard Actions
```html
<kbd>CMD</kbd> + <kbd>R</kbd>
```
<kbd>CMD</kbd> + <kbd>R</kbd>

## 16. Fenced Code Block
```markdown
    ```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
    ```
```
```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

## 17. Link
```markdown
[Github](https://www.github.com)
```
[Github](https://www.github.com)

## 18. Back to top
```markdown
[↑Top of the page↑](#readme) 
```
[↑Top of the page↑](#readme) 

## 19. Image
```markdown
![alt text](https://github.com/AndrewFakher/Markdown-Guide/blob/master/github.png)
```
![alt text](https://github.com/AndrewFakher/Markdown-Guide/blob/master/github.png)

### Simple Icons
 - Supports [SVG Icons](https://github.com/simple-icons/simple-icons/tree/develop/icons) icons for popular brands only.
 - Black color only.
 - HTML syntax.
 - Higher quality. 
 
 ```html
<img alt="simple-icons" width="80" src="https://cdn.jsdelivr.net/npm/simple-icons@latest/icons/github.svg" />
```
<img alt="simple-icons" width="80" src="https://cdn.jsdelivr.net/npm/simple-icons@latest/icons/github.svg" />

## 20. Table
```markdwon
| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |
```
| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |

### Table With Alignment
```markdown
| Left        | Center      | Right         |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |
```
| Left        | Center      | Right         |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |

## 21. Emoji
You can use this [list of emoji shortcodes](https://gist.github.com/rxaviers/7360908)
```markdown
Gone camping! :tent: Be back soon.
That is so funny! :joy:
```
Gone camping! :tent: Be back soon.  
That is so funny! :joy:

## 22. Captions
```html
<div align= "center">
    <sub>© 2020, licensed under the <a href="https://opensource.org/licenses/MIT">MIT License</a>.</sub>
</div>
```
<div align= "center">
    <sub>© 2020, licensed under the <a href="https://opensource.org/licenses/MIT">MIT License</a>.</sub>
</div>

## 23. Contributors Image
[contributors-img](https://contributors-img.web.app/preview?repo=wxphp%2Fwxphp) To Keep in sync your contributors list, ENTER repository name and GENERATE an dynamic image URL for displaying it!
```html
<a href="https://github.com/nextcloud/docker/graphs/contributors">
  <img src="https://contributors-img.web.app/image?repo=nextcloud/docker" />
</a>
```
<a href="https://github.com/nextcloud/docker/graphs/contributors">
  <img src="https://contributors-img.web.app/image?repo=nextcloud/docker" />
</a>

## 24. Horizontal Rule
```markdown
---
```
---
