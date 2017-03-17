### Bower
```
Packages manager for the web.(I have used it for installing bootstrap)
```

* create a .bowerrc file, it install package in the given location.
```
vi .bowerrc

{
    "directory": "app/static/",
    "proxy":"http://<user>:<password>@<host>:<port>",
    "https-proxy":"http://<user>:<password>@<host>:<port>"
}
```

* Install bootstrap

```
bower install bootstrap
```

* Usage in templates

```
<html>
<head>
    <script src="/static/jquery/dist/jquery.js"></script>
    <script type="text/javascript" src="/static/bootstrap/dist/js/bootstrap.min.js"></script>
    <link rel="stylesheet" href="/static/bootstrap/dist/css/bootstrap.min.css">
    <link rel="stylesheet" href="/static/bootstrap/dist/css/bootstrap-theme.min.css">
</head>
```
* More Refer the docs.

```
https://bower.io/
```
