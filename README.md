### Jackcraig.com

Source for my personal site

## Worfklow

`$ jekyll build`
The current folder will be generated into ./_site

`$ jekyll build --destination <destination>`
The current folder will be generated into `<destination>`

`$ jekyll build --source <source> --destination <destination>`
The `<source>` folder will be generated into `<destination>`

`$ jekyll build --watch`
The current folder will be generated into ./_site, watched for changes, and regenerated automatically.

## Misc

If on initial build it says 
`cannot load such file -- jekyll-sitemap (LoadError)`

install following gem 
`gem install jekyll-sitemap`