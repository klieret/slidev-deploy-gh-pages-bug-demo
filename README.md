# Demonstrate failure to publish with gh pages

See [issue report](https://github.com/slidevjs/slidev/issues/667).

Site should be deployed [here](https://klieret.github.io/slidev-deploy-gh-pages-bug-demo/).

## Solution

Subpath needs to be specified in the `npm run` step as follows:

```bash
npm run build -- --base '/slidev-deploy-gh-pages-bug-demo/'
```
