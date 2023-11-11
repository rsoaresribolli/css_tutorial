Emmet abbreviation for generating HTML code in VSCode = **type "!"**

# Important tag to work with responsive layouts
```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```
# Syntax
```css
@media media type and (condition: breakpoint) {
    // CSS Rules
}
```
* Media types: screen, all, print or speech (for screen readers)
* Exaple of conditions: 
    * min-with = start from
    * max-with = stop at
    * orientation = landscape, portrait
    * min-aspect-ration

**Mobile first**: from the smaller, to the larger (it easier to start with the smallest than with the largest and have to fit everithing in a small "box")


**From this point, source:**
https://github.com/gitdagray/css_course/blob/main/17_lesson_starter/notes.md

### Common Media Query breakpoints:
| Breakpoint | Description |
| -------- | ---------- |
| < 481px | Mobile devices |
| 481px — 768px | iPads, Tablets |
| 769px — 1024px | Small screens, laptops |
| 1025px — 1200px | Desktops, large screens |
| 1201px and greater | Extra large screens, TV |

### Bootstrap breakpoints:
| Breakpoint | Description |
| -------- | ---------- |
| < 576px | xs |
| >=576px | small |
| >=768px | medium |
| >=992px | large |
| >=1200px | xl |
| >=1400px | 2xl |

### Tailwind breakpoints:
| Breakpoint | Description |
| -------- | ---------- |
| < 640px | xs |
| >=640px | small |
| >=768px | medium |
| >=1024px | large |
| >=1280px | xl |
| >=1536px | 2xl |