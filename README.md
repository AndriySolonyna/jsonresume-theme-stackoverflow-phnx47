# Stack Overflow theme for jsonresume 

[DEMO](https://themes.jsonresume.org/theme/stackoverflow)

Forked from [jsonresume-theme-stackoverflow-ibic](https://github.com/houtianze/jsonresume-theme-stackoverflow-ibic)

## Getting started

### Install the command line

Create your resume in json on [jsonresume](https://jsonresume.org)

The official [resume-cli](https://github.com/jsonresume/resume-cli) to run the development server.

Go ahead and install it:

```sh
npm install -g resume-cli
```

### Install and serve theme

Clone the repository

```sh
npm install git+https://gitlab.com/phnx47/jsonresume-theme-stackoverflow-phnx47.git
```

And simply run:

```sh
resume export resume.html --theme stackoverflow-phnx47
```

To build your own resume, create a 'resume.json' file in the current folder and follow the [json resume schema](https://jsonresume.org/schema/)

### Social Profiles Icons

**Profiles supported with brand colors:**

github, stack overflow, linkedin, dribbble, twitter, facebook, pinterest, instagram, soundcloud, wordpress, youtube, flickr, google plus, tumblr, foursquare.

To have a social icon close the social link profile (or username) it is enough to set a `network` the name of the Social Network (es: 'Stack Overflow').

#### Support to extra fields

With stackoverflow theme it is possible to add:

- `keywords` to each 'work', 'publication' and 'volunteer' item
- `summary` to each 'interests' and 'education' item
- `location` to each 'work', 'education' and 'volunteer' item
- `birth` to 'basics'

example of the extra `location` object:

```json
"location": {
  "city": "Zürich",
  "countryCode": "CH",
  "region": "Switzerland"
} 
```

example of the extra `birth` object:

```json
"birth": {
  "place": "New York",
  "state": "USA",
  "date": "1988"
}
```

## License

Available under the [MIT license](http://opensource.org/licenses/mit-license.php).
