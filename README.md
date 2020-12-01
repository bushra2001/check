## Create a Github page:
Go to Settings ~ Github Pages ~ Branch = main ~ change theme to your desired theme 

Save it

Beneath Github pages you will find a url like:

Your site is published at https://[username].github.io/[repository]/

### Create Hello World site in github page:

Create a folder site in repository

Add index.html in site folder

```index.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home</title>
</head>
<body>
<h1>Hello World!</h1>

</body>
</html>
```
Now go to your site published https://[username].github.io/[repository]/

Add `site` at the end of url;

https://[username].github.io/[repository]/site

### Adding browser-sync to quicckly load site:

In your command line, move to the folder where html file is locate and add the following command:

[user]@[host-name]:~/[folder]/[repo]/site$ browser-sync start --server --directory --files "*"
