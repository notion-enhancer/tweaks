# Remove arrows on linked pages and databases

**last tested/working:** Nov 9, 2020

**author(s):** [@fabiosangregorio](https://github.com/fabiosangregorio)

> Removes all the arrow icons from linked databases/pages, resulting in a cleaner look.

_before tweak_

![before tweak](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/09fc5d35-ecf3-433b-b1a7-4be1da219f5e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAT73L2G45O3KS52Y5%2F20201117%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20201117T205153Z&X-Amz-Expires=86400&X-Amz-Signature=2b0b6ab65dc20f6239c7c70b67f248c50170e096ab3070927687120e129193b0&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Untitled.png%22)

_after tweak_

![after tweak](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/b608c948-b5f9-4a1b-87cf-f1e4c272e3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAT73L2G45O3KS52Y5%2F20201117%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20201117T205154Z&X-Amz-Expires=86400&X-Amz-Signature=8a6f3f4a0b8246dfd2c522d1b51bde7ea81b55bcc8def0160516fb4c82b6bc88&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Untitled.png%22)

## css

```css
/* ========== REMOVE ARROWS ON LINKED DATABASES/PAGES ========== */
svg.alias, .notion-collection_view-block [style="display: flex; align-items: center; margin-right: 6px;"] {
  display: none !important;
}
/* Remove in page mentions */
.notion-page-mention-token [style="width:1em;display:inline-block;vertical-align:-0.15em;margin-right:0.1em"] {
  width: 2px !important;
}
```