# PNARUDE Workshop

Hugo based static webpage. Based on [hugo-conference](https://github.com/jweslley/hugo-conference). 

## TODO

- [x] Add speaker links to webpage from name and image
- [x] Add submission details
- [x] Add description for speaker bios
- [ ] Add talk descriptions
- [x] Add contact mail button for organizers
- [x] Customize organizer list
- [x] Better Overview Text

## Building locally

### Using docker

``` bash
git clone https://github.com/iros2022-pnarude/iros2022-pnarude.github.io
cd iros2022-pnarude.github.io
docker run --rm -it --net=host -v $(pwd):/src klakegg/hugo server
```
and then see the result at [http://localhost:1313/](http://localhost:1313/)

### Using hugo

1. Install [Hugo](https://gohugo.io)
2. Clone this project:

        git clone https://github.com/iros2022-pnarude/iros2022-pnarude.github.io
        cd iros2022-pnarude.github.io

3. It's done. Just start Hugo server to see it live!

        hugo server --watch

## Customizing the workshop site

Most of the site information can be found in the `config.yml` file. Just edit it to make changes.
By default, the site have the following sections:

- About - to describe what's the main goal of the workshop
- Speakers - to list information about speakers.
- Schedule - to show the agenda.
- Organizer - list of organizers

Ps: It's important to change the `baseurl` property from `config.yml` file in order to reflect your settings.

New images go into the static/img folder. 

Other content, for example the About section, is located at [.themes/hugo-conference/layouts/partials/about.html](.themes/hugo-conference/layouts/partials/about.html).

## License

MIT, see [LICENSE](https://github.com/jweslley/hugo-conference/blob/master/LICENSE).
