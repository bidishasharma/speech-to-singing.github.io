## Welcome to GitHub Pages


You can use the [editor on GitHub](https://github.com/bidishasharma/speech-to-singing.github.io/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown
Speech and singing are different in many ways. In this work, we propose a novel method to align phonetically identical spoken lyric with a singing vocal in a speech-singing parallel corpus, that is needed in  speech-to-singing conversion. We attempt to align speech to singing vocal using a combination of model-based forced alignment and feature-based dynamic time warping (DTW). We first obtain the word boundaries of speech and singing vocals with forced alignment using speech and singing adapted acoustic models, respectively. We consider that speech acoustic models are more accurate than singing acoustic models, therefore, boundaries of spoken words are more accurate than sung words. By searching in the neighborhood of the sung word boundaries in the singing vocal, we hope to improve the alignment between spoken words and sung words. Considering the word boundaries as landmark, we perform speech-to-singing alignment at frame-level using DTW.

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/bidishasharma/speech-to-singing.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
