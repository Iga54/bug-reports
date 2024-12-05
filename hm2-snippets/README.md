# Code Snippets visible in registration form

## Description:

In the H&M registration form, there are visible technical strings displayed as field labels. This appears to expose internal code or misconfigured text keys. Examples include:

1. Above the email input field: “CUSTOMER.email.label.text”
2. Above the password field: “CUSTOMER.password.label.text”
3. In the password field: “password.show and password.hide”

These strings seem to be references to internal code or localization keys, likely displayed due to missing or improperly linked translations.

## Preconditions:

The user is not logged in.

## Steps to Reproduce:

1. Run the browser and go to https://www2.hm.com/pl_pl/dom.html.
2. Select “Zaloguj się” from the right side of the menu.

## Expected Behavior:

All visible label fields should be displayed in user-friendly format, localized messages ("Email," "Password”). Additionally, the password field should contain a show/hide password icon within this field.

## Actual Behavior:

All label fields are displayed incorrectly (incomprehensible code snippets), resulting in poor user experience and potential confusion.

## Environment:

Browsers: ChromeVersion 131.0.6778.108 
Devices: Desktop
Operating Systems: macOS Sequoia Version 15.1.1


## Priority and severity

Severity: Medium

The bug affects the usability of the page and causes confusion for users, especially those unfamiliar with the technical terms. However, it does not completely impact the functionality of the form. Users are able to enter details, but the issue makes it harder for them to understand what is expected.

Priority: High

The issue directly impacts the user experience and could hinder users from registering, which is a critical step for the business. Fixing visible label fields could improve user experience and provide professional appearance on the website.

## Screenshots:

![bug report 1](Screenshot1.png)



