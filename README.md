# Code @ Simula website

This is just a prototype website for the website that will be hosting
the Simula Github space.


## Developing the website

The code is generated using [Hugo](https://gohugo.io). To develop the
website you need to install Hugo. 

All content is written in Markdown and can be found in the
[content](content) folder. The see how the webpage looks while
developing you can type the command

```
hugo server
```
and go to [http://localhost:1313/simula_code_web](http://localhost:1313/simula_code_web).
It will also tell you the correct adress in the terminal.

## Deployment

When you are happy with the current version of the website and you
want to deploy it you run

```
./deploy
```
The site will now be deployed at
[https://finsberg.github.io/simula_code_web/](https://finsberg.github.io/simula_code_web/).
within a couple of minutes. 

