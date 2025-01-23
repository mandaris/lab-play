# Play-Lab
Theme based off of ideas from [Labarum](https://github.com/mandaris/labarum).

## Version History

1.0.0
- Initial release

1.0.1
- Correct background color for `<audio>` element
- Change anchor styling to be more simplistic
- Remove `title` from `<menu>` element

1.0.2
- Added `box-decoration-break` to `pre`, `code`, and `kbd`
- Updated newsletter theme

1.0.3
- Use `.Params.Author` instead of `.Site.Author` this is because it was depreciated

1.1.0
- Change the minimum version of Hugo needed for this theme
- Change `a.footnote-ref` to match the style of `lozenge` class
- Remove all default padding (made some changes to accomidate)
- Add styling for `figure` and `figcaption`
- Change `.Site.Author` to `.Site.Params.Author`
- Add hover affect for includes
- Reduce motion if requested
- Adjustments for newsletter
- Add render hook for alerts

1.1.1
- Add page for author taxonomy
- Change padding to set value instead of `em`

1.1.2
- Add `aria-hidden` to staticly linked svgs
- Reference `notes.svg` instead of `note.svg`
- Modify `site-header` to have the menu under the title
- Adjust `li` and `ol` to have `inline-margin-start`
- Change order of table css to better
- Add margin for `blockquote > footer`

1.1.3
- Add more padding to lozenge
- Add more color to `blockquote` and add it to newsletter
- Adjust the definition terms `<dt>` to be `oblique`