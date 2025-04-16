# Contributing

This gallery is intended to be a community-driven showcase of how Kroxylicious can be used and extended, so new contributions are always welcome.

You can help by:

 * Adding a link to your own Kroxylicious filter (see the [style guide](#style-guide) below),
 * Updating outdated links or removing broken links
 * Fixing spelling and grammar mistakes
 * Adding missing descriptions

...Or anything else you think might improve the gallery!

## How to contribute

To make changes to the gallery you will need to open a pull request, but that's not the only way to contribute! Opening issues and starting discussions are also great ways to help out.

## DCO Signoff

The project requires that all commits are signed-off, indicating that _you_ certify the changes with the [Developer Certificate of Origin (DCO)](./DCO.txt).

This can be done using `git commit -s` for each commit
in your pull request. Alternatively, to signoff a bunch of commits you can use `git rebase --signoff _your-branch_`.


## Gallery Style Guide

When adding a new filter to the gallery there are a few details that need to be included, like the name of the filter, where it can be found, and what it does.

Help us keep things neat and tidy by following this style checklist before opening a pull request:

- [ ] New entries should start with a bullet point (`*`)
- [ ] The title of each entry should be the name of the filter repository, including the owner's name (i.e. `my-org/my-filter` rather than just `my-filter`)
- [ ] The title of each entry should be a link to the filter repository.
- [ ] Each entry should include a short description of what the filter is or what it does (around 10 to 15 words is probably sufficient).
- [ ] Entries where the filter has not been tested with the latest version of Kroxylicious should include the most recent version they were tested with.

### Do:

```markdown
 * [my-org/my-filter](https://example.com/my-org/my-filter): An example for illustrating the Kroxylicious Community Gallery style guide. *(Last tested on Kroxylicious v0.1.0)*
```

> * [my-org/my-filter](https://example.com/my-org/my-filter): An example for illustrating the Kroxylicious Community Gallery style guide. *(Tested with Kroxylicious v0.1.0)*

:white_check_mark: The entry starts with a bullet point

:white_check_mark: The title of the entry is the filter repository name

:white_check_mark: The filter repository name includes the name of the owning organization

:white_check_mark: The title of the entry is a link to the filter repository

:white_check_mark: The entry has a short description of what the filter is

:white_check_mark: The filter was not tested with the latest version of Kroxylicious, so the last tested Kroxylicious version is included at the end of the entry.

### Don't:

```markdown
my-filter https://example.com/my-org
```

> My Filter https://example.com/my-org

:x: The entry doesn't start with a bullet point

:x: The title of the entry is not the filter repository name

:x: The title is not a link to the repository

:x: The link doesn't go to the filter repository

:x: There is no description of the filter

:x: There is no indication of whether the filter has been tested against the latest Kroxylicious version
