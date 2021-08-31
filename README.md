# Sass Boilerplate

This is a sass boilerplate sticking to [Sass Guidelines](https://sass-guidelin.es/#architecture) writing conventions.

## Structure of the project files

```
styles/
|
|– abstracts/
|   |– _breakpoints.scss  # Sass Breakpoints
|   |– _helpers.scss      # Class & placeholders helpers
|   |– _mixins.scss       # Sass Mixins
|   |– _variables.scss    # Sass Variables
|
|– base/
|   |– _base.scss         # Default styles
|   |– _fonts.scss        # Font declarations
|   |– _reset.scss        # Reset
|   |– _typography.scss   # Typography rules
|
|– components/
|   |– __components-dir   # Import all components
|   |– _buttons.scss      # Buttons
|   |– _carousel.scss     # Carousel
|   |– _cover.scss        # Cover
|   |– _dropdown.scss     # Dropdown
|   ...                   # Etc…
|
|– layout/
|   |– __layout-dir       # Import all layouts
|   |– _navigation.scss   # Navigation
|   |– _grid.scss         # Grid system
|   |– _header.scss       # Header
|   |– _footer.scss       # Footer
|   |– _sidebar.scss      # Sidebar
|   |– _forms.scss        # Forms
|   ...                   # Etc…
|
|– pages/
|   |– __pages-dir        # Import all pages
|   |– _home.scss         # Home specific styles
|   |– _contact.scss      # Contact specific styles
|   ...                   # Etc…
|
|
`– main.scss              # Primary Sass input file
```
