Web Development II 2017-2018
============================

Student: Brian Verschoore

> Artevelde University College Ghent

Productiedossier
----------------

### Installatie

```
PS> c
PS> git clone «repository-url» «mapnaam»
PS> c «mapnaam»
```

```
PS> c «mapnaam»
PS> cd docs
PS> bundle update
PS> bundle exec jekyll serve
```

### Jekyll-configuratie

In `_config.yml` pas je de `baseurl` aan, van:

```
# Site settings
# ─────────────
baseurl: /1718-webdev2-project # the subpath of your site, e.g. /blog
```

naar `«repositorynaam»` (bv. `1718-webdev2-project-olivpa`):

```
# Site settings
# ─────────────
baseurl: /«repositorynaam» # the subpath of your site, e.g. /blog
```

### GitHub Pages Configuratie

Op GitHub ga je naar je repository en klik op **Settings**. Scroll naar beneden tot aan **GitHub Pages**, zet de **Source** op `master branch /docs folder` en klik op **Save** om te bewaren.
