## Welcome to Public Sans!

We're so glad you're thinking about contributing! If you're unsure or afraid of anything, just ask or submit the issue or pull request anyways. The worst that can happen is that you'll be politely asked to change something. We appreciate any sort of contribution, and don't want a wall of rules to get in the way of that.

Before contributing, we encourage you to read our CONTRIBUTING policy (you are here), our [LICENSE](https://github.com/uswds/public-sans/blob/develop/LICENSE.md), and our [README](https://github.com/uswds/public-sans/blob/develop/README.md).

## SIL Open Font License v1.1

Public Sans is licensed under the [SIL Open Font License v1.1](http://scripts.sil.org/OFL)

To view the copyright and specific terms and conditions please refer to [OFL.txt](https://github.com/impallari/Libre-Franklin/blob/master/OFL.txt). The terms and conditions for modifications made to the original font by USWDS in the USWDS Modified Version can be found at https://github.com/uswds/public-sans/blob/develop/LICENSE.md.

By submitting a pull request, you agree to comply with the terms and conditions of the SIL Open Font License, v. 1.1.

## Running the specimen site locally

The specimen site runs on Jekyll and Node, powered by USWDS. The site-related files are distinct from the Public Sans source files and are kept in the following locations:

```
public-sans/
├── _data/
├── _includes/
├── _layouts/
├── _sass/
├── pages/
└── assets/

```

## Running code locally

After cloning the repo, navigate to the correct folder and install USWDS, Jekyll, and any necessary dependencies using:

```
npm start
```

Then, to run the site locally:

```
npm run serve
```

If all goes well, visit the site at http://localhost:4000.

USWDS assets are in `assets/uswds/fonts` and `assets/uswds/img`.

SASS files are kept in the `/_sass` directory. To watch for changes and recompile the styles, run:

```
npm run watch
```
