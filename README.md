# Translation Guide

**Please read this guide thoroughly from beginning to end.** 

You're welcome to contribute in whichever way suits you best:

- **Submit a pull request**
- **Translate live in your browser** → on our easy-to-use translation platform: [https://translate.devevil.com](https://translate.devevil.com)

Every translation helps make DevEvil Universe more accessible to people all around the world.  
Thank you in advance for your time and effort! 💜

## How to Translate

### What to Translate

- Translate all user-facing text strings
- Keep technical terms consistent
- Maintain the same tone and style as the original
- Preserve HTML tags and formatting

### HTML Formatting Guide

**IMPORTANT:** When translating text that contains HTML tags, you **must** preserve the exact HTML structure. Here's how to handle different HTML elements:

#### HTML Tags to Preserve

- `<span class='highlight'>` → Highlighted text (translate the content inside)
- `<h1>`, `<h2>`, `<h3>` → Headings (translate the content)
- `<br>` → Line breaks (keep as is)
- `<a href='...'>` → Links (translate the link text, **keep the href attribute**)

#### Examples

**Original:**
```html
<h1>Welcome to <span class='highlight'>DevEvil Universe 💫</span></h1>
```

**Spanish Translation:**
```html
<h1>Bienvenido al <span class='highlight'>Universo DevEvil 💫</span></h1>
```

**Original:**
```html
Visit <a href='./contact'>our contact page</a> for more info.
```

**French Translation:**
```html
Visitez <a href='./contact'>notre page de contact</a> pour plus d'informations.
```

#### Special Cases

- **Emojis:** Keep emojis as they are (💫, 🎉, etc.)
- **HTML Entities:** Preserve entities like `&lt;`, `&gt;`, `&amp;`
- **CSS Classes:** Never translate class names or IDs

### What NOT to Translate

- Variable names and technical identifiers
- URLs and email addresses
- Code snippets and technical terms that should remain in English
- Brand & services names (e.g. "DevEvil", "uId", "BetterDiscord", "Discord", etc.) and proper nouns
- HTML tag names and attributes
- CSS class names and IDs

### Tips

- Read the context carefully before translating
- If unsure about a translation, leave it blank
- Maintain consistency with terminology

### What's in it for you as a translator?

- A **Translator badge** on your uID page and your DevEvil Universe account (after approval)
- **Translator role** in my Discord server (after approval)
- Your username and uID will be publicly displayed on this page:  
  👉 https://devevil.com/translators
- Plenty of virtual hugs from me! 🤗
