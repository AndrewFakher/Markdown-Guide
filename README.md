![Markdown Guide](https://github.com/AndrewFakher/Markdown-Guide/blob/master/markdown-guide-og.jpg)
<h1 align="center">Markdown Guide</h1>
<p align="center">
	This Markdown cheat sheet provides a quick overview of most the Markdown syntax elements.
</p>

## Badges
[Shields.io](https://shields.io) contains quality metadata badges for open source projects.

```markdown
[![Build Status](https://img.shields.io/travis/markdown-it/markdown-it-deflist/master.svg?style=flat)](https://shields.io)  
[![Coverage Status](https://img.shields.io/coveralls/markdown-it/markdown-it-deflist/master.svg?style=flat)](https://shields.io)
```
[![Build Status](https://img.shields.io/travis/markdown-it/markdown-it-deflist/master.svg?style=flat)](https://shields.io)
[![Coverage Status](https://img.shields.io/coveralls/markdown-it/markdown-it-deflist/master.svg?style=flat)](https://shields.io)

## Check List
- [ ] item 1
- [x] item 2

## Ordered List
1. First item
2. Second item
3. Third item

## Sub Ordered List
1. First item
2. Second item
3. Third item
    1. Indented item
    2. Indented item

## Unordered List
- First item
- Second item
- Third item

## Sub Unordered List
- First item
- Second item
- Third item
    - Indented item
    - Indented item
  
## Nested lists
- First item
  - sub-item
    - sub-sub-item
    
## Expandable Menu
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

## Bold Text
**bold text**

## Italic Text
*italicized text*

## Strikethrough
~~The world is flat.~~

## Definitions
Markdown
: Markdown is a lightweight markup language with plain text formatting syntax. Its design allows it to be converted to many output formats, but the original 
tool by the same name only supports HTML.

## Footnote
<sup>1</sup>This is the first footnote.

## New line
You can make a new line by ending a line with two spaces  
you don't have to use `<br>`.

## Blockquote
> blockquote

### Nested blockquote
> blockquote
>> nested blockquote

## Keyboard Actions
<kbd>CMD</kbd> + <kbd>R</kbd>

## Block of Code
```swift 
    func application(_ application: UIApplication, didFinishLaunchingWithOptions launchOptions: [UIApplication.LaunchOptionsKey: Any]?) -> Bool {
         return true
    }
```

## Fenced Code Block
```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

## Block
`Desktop/Projects/ProjectFolder/ProjectFile`

## Link
[Github](https://www.github.com)

## Back to top
[↑Top of the page↑](#readme) 

## Image
![alt text](https://github.com/AndrewFakher/Markdown-Guide/blob/master/github.png)

### Simple Icons
 - Supports [SVG Icons](https://github.com/simple-icons/simple-icons/tree/develop/icons) icons for popular brands only.
 - Black color only.
 - HTML syntax.
 - Higher quality. 
 
<img alt="simple-icons" width="80" src="https://cdn.jsdelivr.net/npm/simple-icons@latest/icons/github.svg" />

## Table
| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |

### Table With Alignment
| Left        | Center      | Right         |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |

## Emoji
Gone camping! :tent: Be back soon.

That is so funny! :joy:

You can use this [list of emoji shortcodes](https://gist.github.com/rxaviers/7360908)

## Captions
<div align= "center">
    <sub>© 2020, licensed under the <a href="https://opensource.org/licenses/MIT">MIT License</a>.</sub>
</div>

## Contributors Image
[contributors-img](https://contributors-img.web.app/preview?repo=wxphp%2Fwxphp) To Keep in sync your contributors list, ENTER repository name and GENERATE an dynamic image URL for displaying it!

<a href="https://github.com/nextcloud/docker/graphs/contributors">
  <img src="https://contributors-img.web.app/image?repo=nextcloud/docker" />
</a>

## Horizontal Rule
---
