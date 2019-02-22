## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/swift26/swift26.github.io/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

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

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/swift26/swift26.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.


Steps for Hosting a Website on GitHub

Create a GitHub account on github.com.
Download either GitHub for Mac or GitHub for Windows, depending on your operating system. Open the app and log in using the account you just created.
(On Mac): After you login, click advanced and make sure that your name and email are correct. Then, click "Install Command Line Tools", just in case you want to start using the command line later in life.
Create a new repository in your GitHub application. Name it your-username.github.io. The name is very important. Note the folder that GitHub is saving the repository to. Make sure the "Push to GitHub?" box is checked.
Move your website's files into the folder that GitHub just created when you made the repository. IMPORTANT: Your homepage HTML file must be called "index.html", and it must exist in the top-level directory.
Back in the GitHub application, you should see your files in the left column. Make sure they are all checked. If so, enter a message in the text box called "commit summary", something like "initial commit." Then, click the commit button.
Click the "Publish repo" button in the top right corner.
Give it about 10 minutes, then check your-username.github.io. Your website should be there!

Using a custom domain name

You can just leave your website at that address (it'll give you some serious street cred in the developer world), but if you have a custom domain you would like to use, it is very simple to make GitHub redirect your page.

Log in to your domain registrar and find where to change your host records. If you don't know, you can usually Google "(domain registrar) change host records", and your registrar will have an explainer telling you how to do it.
Change your domain's A Record to 204.232.175.78. This is GitHub's IP address, which allows GitHub to resolve your URL and serve the correct files.
In your website's directory folder on your computer, create a file called "CNAME". On the first line, type your domain name. Save the file.
In your GitHub application, you should see the file in the left column. Make sure it is checked and enter your commit message. Have it say something like "Adding CNAME file."
Click "Sync branches."
It can take as long as 48 hours for your domain to resolve to your GitHub page. However, it is usually pretty quick, so check back in an hour or so.
