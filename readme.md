This is a template for new progress reports.

# Basic Pandoc
This is a pandoc command for writing a basic pdf from a markdown file.
```bash
pandoc writing.md -o writing.pdf
```

# Article Pandoc
This is a command for making a pdf with the article.tex template.
```bash
pandoc --filter pandoc-citeproc --template article.tex  example.md -o example.pdf
```
# Cloning this template
To clone this template, use the following commands.
```bash
cd ~/path
mkdir dir_name
git clone https://github.com/JBWBecker/progress_report_template.git
```
