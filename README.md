# pelican_crash_lab
play with Python pelican

# Guides or tips

* [Setup Python with pyenv + poetry](https://github.com/hong539/setup_dev_environment/tree/main/programing_languages/python#usage-with-pyenvpoetry)
* [Pelican](https://getpelican.com/)
* [deployment](https://docs.getpelican.com/en/latest/publish.html#deployment)
* [publishing-to-github](https://docs.getpelican.com/en/latest/tips.html#publishing-to-github)

## How to use?

```shell
#pyenv + poetry
#check which python
pyenv versions

#Activating the virtual environment 
poetry shell

#track your project's dependencies
poetry show --tree

#play with pelican
pelican-quickstart
pelican content

#run a webserver to check out your static web pages via markdown
pelican -r -l
```

## To do list

* design user interface(buttons/links...etc)
* make personal roadmap or passive tree graph
    * It could be static or dynamic web pages?
    * Fine some reference examples