*TODA VEZ QUE INICIAR PROJETO POR ESSE REPOSITORIO, PARA EFETUAR O PRIMEIRO COMMIT SIGA AS INSTRUCOES ABAIXO*
NO TERMINAL INSIRA:
rm -rf .git
git init 
git add .
git commit -m "first commit"
git remote... (veja endereco de repositorio criado no GITHUB)
git push -u origin master


The most basic boilerplate for any 4Geeks Academy Student using the [gitpod.io](gitpod.io) coding editor.

## What to do next?

Create a `index.html` file with the [basic HTML structure](http://content.breatheco.de/lesson/what-is-html-learn-html#page-structure) and see it live by running web-server using the following command:
```sh
$ pip3 install flask      (only the first time)
$ python3 server.py
```

- You can create as many HTML files you want
- You can also create CSS files and you can import them onto your website using a `<link>` tag placed between the `<head></head>` tags, like this:

```html
<head>
  ...
  <link rel="stylesheet" type="text/css" href="styles.css">
  ...
</head>
```
python3 -m http.server 3000
