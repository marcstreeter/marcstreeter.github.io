# Example Markdown Based Github Pages Site
This repository shows all that is needed to get a functioning github pages site.

The only thing it is missing is the setting pointing it to the appropriate DNS entry under

```
Settings > Pages > Custom domain
```
in my case I had the value

```
about.kube.watch
```
After setting this, github will create a file named `CNAME` via a git commit that contains the entered value.

And then, through a self owned domain, like gandi/godaddy/tucows, we would need a corresponding CNAME entry. This entry needs to point the above mentioned custom domain to here (in my case marcstreeter.github.io.)
