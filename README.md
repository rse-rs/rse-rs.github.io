# rs4rse website

This is the website src for http://rs4rse.github.io .

## Redeploy without changes

To update the current listed meetup without changes to any files.

Go to action and trigger the deploy CI manually.

## Creating the next events

Add a markdown file under `./content/_events/`.

## Local development

Sometimes you want to test or modify things locally. Luckily, this is pretty easy, you just have to do the following:

- Clone or download the repository
- Make sure you have static site engine [zola](https://www.getzola.org/) installed.
- Run `zola serve` in the directory where you cloned the project to get a local preview of your site. It auto-updates every time you edit something.

