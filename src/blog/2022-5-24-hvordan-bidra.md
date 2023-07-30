# How to contribute

If you want to enter a recipe yourself and then make a pull request, you can do so
that by following these steps.

## Dec

Create a [fork](https://github.com/engeir/simple-recipes-cookbook/fork) of the repository.

## New recipe

A new recipe can be added by creating a new file in an existing one or a new one
folder.

New files _must_ have the file extension `.md`, and the file name must be without spaces (use instead
hyphen, `-`) and in lower case only, also known as [kebab
case](https://en.wikipedia.org/wiki/Letter_case#Kebab_case).

Let's say you want to add a bowl recipe. Then you create a new file in the folder
`bakst' and calls it, for example, `ferske-boller.md'. Copy the contents of the
[TEMPLATE.md](https://github.com/engeir/simple-recipes-cookbook/blob/main/TEMPLATE.md?plain=1) into
`ferske-boller.md', and edit as you wish.

The file structure you want to add files to looks roughly like this, before and after:

||| For

```text
.
├── IMAGE.md
├── LICENSE
├── README.md
├── TEMPLATE.md
├── retype.yml
└── src
     ├── _includes
     │   └── head.html
     ├── baking
     │   ├── banana pancakes.md
     │   └── index.yml
     ├── blog
     │   └── 2022-5-24-hverdan-bidra.md
     ├── main courses
     │   ├── index.yml
     │   └── tomato-paprika-suppe.md
     ├── index.md
     └── static
         └── pasta-a-la-vodka.webp
```

||| After

```text
.
├── IMAGE.md
├── LICENSE
├── README.md
├── TEMPLATE.md
├── retype.yml
└── src
     ├── _includes
     │   └── head.html
     ├── baking
     │   ├── banana pancakes.md
     │   ├── fresh-boller.md
     │   └── index.yml
     ├── blog
     │   └── 2022-5-24-hverdan-bidra.md
     ├── main courses
     │   ├── index.yml
     │   └── tomato-paprika-suppe.md
     ├── index.md
     └── static
         └── pasta-a-la-vodka.webp
```

|||

## Open PR

Now can open a pull request (PR) against my branch "main".