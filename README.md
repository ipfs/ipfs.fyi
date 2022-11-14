# 📇 ipfs.fyi shortlinks

<img src="./logo.png" align="right" alt="ipfs.fyi logo" />

ipfs.fyi is a short link service that uses the [`_redirects`](./_redirects) file to configure redirections.

It allows creating shortlinks with the `ipfs.fyi` domain

## Example

```
/blog   https://blog.ipfs.tech  301
```

Will redirect from **`ipfs.fyi/blog`** ➡️ `https://blog.ipfs.tech` with an HTTP `301` code.

## `_redirects` file syntax

[`_redirects` syntax docs](https://docs.netlify.com/routing/redirects/redirect-options/)

