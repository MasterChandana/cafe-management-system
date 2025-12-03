# Color Theme Change Plan

## Overview

Change the project's color scheme to a premium dark blue (#2c3e50), gold (#f1c40f), and red (#e74c3c) theme.

## Steps

- [ ] Update variable.scss: Change Material $primary to dark blue palette, $accent to gold, $warn to red. Update custom variables ($themecolor, $primary, $info, etc.) to new colors.
- [ ] Update home.component.scss: Replace #1abc9c with #f1c40f, #7b1fa2 with #2c3e50, #ae2a7b with #e74c3c, etc.
- [x] Update dashboard.component.scss: Replace #474e5d with #2c3e50, #2b8aac with #2c3e50, #555 with #2c3e50.
- [x] Update manage-user.component.scss: Replace #671AB7 with #2c3e50.
- [x] Update manage-product.component.scss: Replace #671AB7 with #2c3e50.
- [x] Update manage-category.component.scss: Replace #671AB7 with #2c3e50.
- [x] Update view-bill-products.component.scss: Replace #04AA6D with #f1c40f.
- [x] Update spinner.scss: Replace #1976d2 with #2c3e50.
- [x] Update app.scss: Replace #212121 with #2c3e50.
- [ ] Update best-seller.component.scss: Change --bs-primary to #f1c40f, --bs-warning to #f1c40f.
- [ ] Update styles.scss: Change green snackbar #00ff7f to #f1c40f if needed.
- [ ] Test the changes by running the Angular app and verifying the theme.
