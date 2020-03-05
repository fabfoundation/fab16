## FAB16 Notice

In order to help "non-tech" people who wants to edit the website content
Please don't hesitate to suggest specific "how-to" by raising an issue ;)

### Structure

```
.
├── _data
├── _includes
├── _layouts
├── _posts
├── _sass
├── assets
├── drafts
├── fr

```

#### _data

This should contain all text informations. Datas has been agregated here because some infos are redondant between secondary page and the home page (for example, the 'Travel' section in homepage and the 'Travel' page)

*TO-DO: Also put the content of 'Press', 'Programme' and 'Privacy policy' pages (actually in root folder - for example in press.md)

Warning: Remember that YML syntax doesn't accept specific caracters (i.e tabs, double quotes) and could put the website down.
For more infos, please read https://docs.ansible.com/ansible/latest/reference_appendices/YAMLSyntax.html

#### _includes
This contains all the HTML templates for the different sections

#### _layouts

Here all the layout templates (i.e for the different page types).

#### _posts
Not used - for blogging purposes

#### _sass
This contains all the SCSS files (equivalent to CSS, but better ;)), separated by section

#### assets
This folder contains all the assets, for example the images

#### drafts
This folder is used to keep track of old pages

#### fr
All the french translations, linked to original english pages with /_data/map.yml

#### index.html , press.md , privacy-policy.md , programme.md , tickets.md , travel.md , venues.md 
All the files for specific pages

Some exceptions are still containing their text ( press.md , privacy-policy.md , programme.md ) especially because their content is not used elsewhere