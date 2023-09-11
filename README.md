# HelloWorld

# First Level Heading

## Second Level Heading

### Third Level Heading

**This is bold text**

_this text is italicized_

~~this was mistaken text~~

**This text is _extremely_ important**

***All this text is important***

this is a <sub>subscript</sub> text

this is a <sup>superscript</sup> text

>text that is a quote

use `git status` to list all new or modified files that have not been comitted yet (this section shows how to call out code within text)

some basic git commands are:
```
git status
git commit
git add
```

the background color is  `#ffffff` for light mode and `#000000` for dark mode (HEX, RGB and HSL format supported)

this site was built using [Github Pages] (https://pages.github.com/)


![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://myoctocat.com/assets/images/base-octocat.svg)

the following code displays a sun image for light themes and a moon for dark themes:

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/25423296/163456776-7f95b81a-f1ed-45f7-b7ab-8fa810d529fa.png">
  <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
  <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
</picture>

LISTS
- George Washington
* John Adams
+ Thomas Jefferson

ORDERED LISTS
1. James Madison
1. James Monroe
1. John Quincy Adams

NESTED LISTS
1. First list item
   - First nested list item
     - Second nested list item

TASK LISTS
- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:
- [ ] - [ ] \(Optional) Open a followup issue

MENTIONS 
(format = organization/team-name)
@github/support What do you think about these updates?

EMOJI
You can add emoji to your writing by typing :EMOJICODE:, a colon followed by the name of the emoji.

@octocat :+1: This PR looks great - it's ready to merge! :shipit:


FOOTNOTES
this bracket syntax:

Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].

[^1]: My reference.
[^2]: To add line breaks within a footnote, prefix new lines with 2 spaces.
  This is a second line.


ALERTS
> [!NOTE]
> Highlights information that users should take into account, even when skimming.

> [!IMPORTANT]
> Crucial information necessary for users to succeed.

> [!WARNING]
> Critical content demanding immediate user attention due to potential risks.


HIDING CONTENT W COMMENTS
<!-- This content will not appear in the rendered Markdown -->

IGNORING MARKDOWN RENDERING
(format = use \ before the character to be ignored)
Let's rename \*our-new-project\* to \*our-old-project\*.

