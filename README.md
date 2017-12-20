## Welcome to GitHub Pages

## Creating my Site Pages

I created my site pages and content. I went to my DNS CNAME to point www to gcallaway2015.github.io. It was just a few minutes before I checked nslookup to find that it answered.

```markdown

C:\Users\George>nslookup www.georgecallaway.com
Server:  UnKnown
Address:  192.168.1.1

Non-authoritative answer:
Name:    sni.github.map.fastly.net
Addresses:  2a04:4e42:d::403
          151.101.53.147
Aliases:  www.georgecallaway.com
          gcallaway2015.github.io
```

The browswer still goes to the networksolutions site at georgecallaway.com. I added the two addresses specified by github to my A record, and now I wait.

## Default content

You can use the [editor on GitHub](https://github.com/gcallaway2015/gcallaway2015.github.io/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

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

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/gcallaway2015/gcallaway2015.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
