Contributing
Please feel free to submit pull requests or open issues to improve the language of this document or to provide additional translations.

You should also check the issues for the latest discussions involving the current and future versions of the Contributor Covenant.

If you're new to contributing to projects hosted on Github, or need a refresher, you may find How to make your first pull request on GitHub a useful resource.

Adding a Project to the List of Adopters
Fork the repository.
Add a new row to the adopters.csv file, with the project name in the first column, and the project URL in the second column.
Open a pull request.
We respect and appreciate different kinds of contributions.
Ways that you can contribute:

Community governance experts
We value collaboration with contributors who bring their experience with code of conduct design or enforcement to continue to improve Contributor Covenant.

Writers and copy editors
We welcome contributions to improve the language of our site.

Designers
We welcome improvements to the design elements of our website or other ways that you can use your talents to improve contributor-covenant.org.

Translators and native speakers
We're always looking for new localizations of the Contributor Covenant and are thankful to the volunteers who spend their time on translations.

We also rely on the contributions of native speakers in the form of review, edits, and suggestions.

If you are interested in doing a translation, please follow these steps:

Fork the repository and make a branch for your translation.
If it's a new language, add it to config.toml, with a localized name and language code/optional region (e.g. pt or pt-br).
Create a markdown file with your translation in version/2/0/code_of_conduct.LANGUAGECODE.md. (Underscores, not hyphens.)
Open a pull request.
We will put out a call to have one or more other native speakers review the translation.
Collaborate until the translation is satisfactory.
We will merge your translation!
HTML and plain text versions are automatically generated from your markdown file.
A link to your translation is automatically added to the translations page.
Developers
Code contributions to improve the development or operation of the contributor-covenant.org web site are welcome.

Build the website locally
To build the website locally, first install Hugo using your package manager of choice. For example, on Debian/Ubuntu:

apt-get install hugo
If you are using Arch Linux:

pacman -S hugo
If you are using Homebrew on macOS:

brew install hugo
Start the server
From the repository's root directory, start the development server:

hugo server -D
Code Style
Use spaces for indentation
Order properties alphabetically
HTML
Include alt attribute for all images
Include title attribute for all links
Close all your tags properly
CSS
Try to use classes instead of IDs unless things are absolutely unique
One selector per line
Support IE 9 and above
Use rem over em or px
Capitalize hexadecimal
Breaking lines should be 1px solid #CCC
Maintain contrast to WCAG AA on normal text, WCAG AAA on large text
Use colors from this palette
Markdown
Do not use fancy quotes, dashes, and such; the Markdown processor will handle that.
