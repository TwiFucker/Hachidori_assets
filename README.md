# Hachidori Assets

This repository contains Hachidori Xposed module assets.

## How to contribute?

- Fork or sync this repository
- Create a new branch (to ensure you don't messed up main branch)
- Edit file in new branch
- Create a pull request
- You can delete this branch after pull request merged

## Localization (i18n)

- Copy `values/strings.xml` to `values-{lang}/strings.xml` if it does not exists
- Remove any line containing `translateable="false"`
- Translate and remember to escape characters `<`, `>`, `&`, `"`, `'` ([READ ME](https://docs.oracle.com/cd/A97335_02/apps.102/bc4j/developing_bc_projects/obcCustomXml.htm))
- Remember to include your GitHub username into `translators`
- Validate the XML using any XML validator you can find online or use an IDE

