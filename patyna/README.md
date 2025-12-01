# Products Not Displaying After Selecting a Category from the Menu

### Bug ID: #150

### Reported By: Iga

### Date Reported: 01.12.2025

### Severity: High

### Priority: High

### Status: Open

## Description:

When a user selects one of the categories from the main menu, the product list does not display any items. However, the top section of the page shows a message indicating that "15 products were found". This suggests that the system retrieves the correct number of products, but the product list fails to render on the page.

## Preconditions:

The user doesn't have to be logged in.

## Steps to Reproduce:

1. Open the website https://patyna.pl/.
2. Click on category “Kuchnia” in the main menu.
3. Select “Garnki” from the list.
4. Observe the product listing section.

## Expected Behavior:

All products belonging to the selected category should be displayed in the product list.

## Actual Behavior:

No products are displayed, despite the message indicating that 15 products were found.

## Environment:

- Browsers: ChromeVersion 142.0.7444.176
- Devices: Desktop
- Operating Systems: macOS Tahoe 26.1


## Priority and severity

- Severity: High

The issue prevents users from viewing products, significantly impacting core functionality.

- Priority: High

Should be fixed as soon as possible due to its effect on the shopping experience. It hinders users from buying products.

Screenshots:

![bug report 1](screenshots/Screenshot.png)




