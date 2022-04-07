# PNARUDE Workshop

Hugo based static webpage. Based on

## Building locally

1. Install [Hugo](https://gohugo.io)
2. Clone this project:

        git clone https://github.com/iros2022-pnarude/iros2022-pnarude.github.io
        cd iros2022-pnarude.github.io

3. It's done. Just start Hugo server to see it live!

        hugo server --watch

## Customizing the workshop site

All the site information can be found in the `config.yml` file. Just edit it to make changes.
By default, the site have the following sections:

- About - to describe what's the main goal of the workshop
- Speakers - to list information about speakers.
- Schedule - to show the agenda.
- Organizer - list of organizers

Ps: It's important to change the `baseurl` property from `config.yml` file in order to reflect your settings.

## License

MIT, see [LICENSE](https://github.com/jweslley/hugo-conference/blob/master/LICENSE).
