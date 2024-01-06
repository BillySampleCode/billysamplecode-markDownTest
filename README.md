# billysamplecode.github.io

Headings:
# A first-level heading
## A second-level hading
### A third-level heading

Styling text:

**Bold**

*Italic*

~~Strikethrough~~

**Bold and _nested italic_**

***All bold and italic***

Text<sub>subscript</sub>

Text<sup>superscript</sup>

Quoting code:

```Backticks: 

1) To call out code

2) To call a command
```

```git status```

```git add```

```git commit```

Supported color models:
HEX:
`#RRGGBB`
`#0969DA`
RGB:
`rgb(R,G,B)`
`rgb(9,105,218)`
HSL:
`hsl(H,S,L)`
`hsl(212, 92%, 45%)`
Notes: 1) A supported color model cannot have any leading or trailing spaces within the backticks.
2) The visualization of the color is only supported in issues, pull requests, and discussions.

Links:
This site was built using [https://github.com/billysamplecode](https://github.com/billysamplecode)
Section links:
[# A first-level heading with Section links](root/fileName.fileType)
Relative links:
[Relative links](root/fileName.fileType)

Images:
![Github logo](https://github.githubassets.com/assets/github-logo-55c5b9a1fe52.png)

Specifying the theme an image is shown to:
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/25423296/163456776-7f95b81a-f1ed-45f7-b7ab-8fa810d529fa.png">
  <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
  <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
</picture>

Lists:
Unordered Lists:
- Unordered ListItem1
- Unordered ListItem2
- Unordered ListItem3
* Unordered ListItem4
* Unordered ListItem5
* Unordered ListItem6
+ Unordered ListItem7
+ Unordered ListItem8
+ Unordered ListItem9

Ordered Lists:
1. Ordered ListItem3
1. Ordered ListItem2
1. Ordered ListItem1
2. Ordered ListItem6
2. Ordered ListItem5
2. Ordered ListItem4
3. Ordered ListItem9
3. Ordered ListItem8
3. Ordered ListItem7

Nested Lists:
1. First ListItem1
   - First NestedListItem1
     - Second NestedListItem2 

Nested Lists in comment editor on GitHub:
100. First ListItem1
    - First NestedListItem1
100. First ListItem1
    - First NestedListItem1
      - Second NestedListItem2

Task lists:
- [] TaskItem1
- [x] TaskItem2MarkedWithX
- [ ] \(TaskItem3ItemDescriptionBeginsWithAParenthesis,EscapeWith\AtFront)

Mentioning people and teams:
@billysamplecode

Referencing issues and pull requests:
#TypeThisSymbol To bring up a list of suggested issues and pull requests within the repository by typing #

Referencing external resources:
Repository administor has ability to create custom autolink references to external resources.

Uploading assets:
You can upload assets like images by dragging and dropping, selecting from a file browser, or pasting. You can upload assets to issues, pull requests, comments, and .md files in your repository.

Using emoji:
You can add emoji to your writing by typing :EMOJICODE:, a colon followed by the name of the emoji. For a full list of available emoji and codes see: [the Emoji-Cheat-Sheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md)

Paragraphs:
You can create a new paragraph by leaving a blank line between lines of text.

Footnotes:
You can add footnotes to your content by using this bracket syntax:

Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].

[^1]: My reference.

[^2]: To add line breaks within a footnote, prefix new lines with 2 spaces.
  This is a second line.

Alerts:

Five types of alerts are available:

>[!NOTE]
>Useful information that users should know, even when skimming content.

>[!TIP]
>Helpful advice for doing things better or more easily.

>[!IMPORTANT]
>Key information users need to know to achieve their goal.

>[!WARNING]
>Urgent info that needs immediate user attention to avoid problems.

>[!CAUTION]
>Advises about risks or negative outcomes of certain actions.  

Hiding content with comments:

You can tell GitHub to hide content from the rendered Markdown by placing the content in an HTML comment.

<!-- This content will not appear in the rendered Markdown -->

