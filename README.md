# Scholar-docs

[Hugo](https://gohugo.io/) theme using [Bootsrap 5](https://getbootstrap.com/)
to show documentation.

- It creates a expandable sidebar created using all the files inside the
  `content` folder. This way you can easily navigate all the pages of your
  project. Each folder should contain an `_index.html` file with a `title` on
  the `yaml` section.
- It includes a sticky header. You can define the desired added links into the
  header. These elements should be defined in `[menu.main]` on the
  `config.toml` file.
- It includes a sticky footer. You can use social media links on the footer
  defining `[params.social]` on the `config.toml` file. The icons are used from
  `fontawesome`.

Check the `config-example.toml` to define the desired attributes.
