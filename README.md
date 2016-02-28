# pudding.io

* Setup github pages
* Install identity server
* Call api without security
* Call api with security

## Setup github project pages

* create github repository
* create gh-pages branch
* settings > branches > set as default branch
* clone
* create index.html
* point A records to github (192.30.252.153
 & 192.30.252.154)
* add pudding.io to cloudflare
* change dns server to cloudflare

* ipconfig /flushdns
* dig pudding.io +nostats +nocomments +nocmd
* tracert pudding.io

* set ssl to flexible on cloudflare
* ensure html contains canonical
* ensure html contains redirect

### more

* https://help.github.com/categories/customizing-github-pages/

