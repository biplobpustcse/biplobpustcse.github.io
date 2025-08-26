# Personal web page

[Papermod](https://github.com/adityatelange/hugo-PaperMod) theme for Hugo.

## Install Hugo on Windows.
[Installation](https://gohugo.io/installation/windows) Link

**Windows (Chocolatey):**
```
choco install hugo-extended
```
## Create a Hugo site locally
```
# Pick a parent folder, then:
hugo new site my-blog
cd my-blog
git init
```
Create a .gitignore so you don’t commit the generated site:
```
/public/
/resources/_gen/
```
## Add a theme (PaperMod)

**Submodule (easy)**
```
git submodule add https://github.com/adityatelange/hugo-PaperMod themes/PaperMod
```

**Update the theme submodule with the following command:**

```sh
git submodule update --init --recursive
```

**Run locally:**

```sh
hugo server -D
```
