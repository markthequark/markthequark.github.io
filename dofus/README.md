# Custom Dofus theme.
 To use this theme, paste the following into options > themes  
`https://markthequark.github.io/dofus/themes.json`

Original guide from Ankama Games:  
`https://www.dofus.com/en/forum/1-log-book/325437-how-can-i-create-my-very-own-dofus-theme`

## Changes
`darkstone.dt` -> `darkstone3.dt`
```xml
<theme>
    <name> -> <name>darkStone3</name>
    <description> -> <description>darkStone with increased font size.</description>
    <author> -> <author>Mark</author>
</theme>
```
`chat.css `
```css
p {
  font-size: 16 -> 20;
}
bubble {
  font-size: 18px -> 20px;
}
```
