# Gmail Email Signature

A clean, minimal, professional Gmail email signature built with HTML
tables and inline CSS for broad email-client compatibility.

## Preview

The signature features:

-   **Name:** Munashe Walter Jojo
-   **Email:** jomunashe@gmail.com
-   **Phone:** +263 784 600 988 / +263 715 995 667
-   **Website:** [www.munaxxe.co.zw](https://www.munaxxe.co.zw)
-   A dark navy name, a short baby-blue accent line, and muted blue-grey
    contact details
-   No icons, emojis, or horizontal dividers

## Features

-   Email address, phone numbers, and website are clickable.
-   Uses inline CSS to improve compatibility with Gmail and other email
    clients.
-   Uses a simple table-based layout to help preserve alignment.
-   Easy to customize with your own contact information and colors.

## Installation in Gmail

1.  Save the signature HTML as `signature.html`.
2.  Open `signature.html` in a web browser.
3.  Select the rendered signature and copy it.
4.  Open Gmail.
5.  Select **Settings** (gear icon), then **See all settings**.
6.  In the **General** tab, scroll to **Signature**.
7.  Create a new signature and paste the copied signature into the
    editor.
8.  Set it as the default for new emails and/or replies if desired.
9.  Scroll to the bottom and select **Save Changes**.

> **Tip:** Copy the rendered signature from your browser, not the HTML
> source code.

## Customization

Open `signature.html` in a code editor and update the following values:

  Item      Current value
  --------- ---------------------
  Name      Munashe Walter Jojo
  Email     jomunashe@gmail.com
  Phone 1   +263 784 600 988
  Phone 2   +263 715 995 667
  Website   www.munaxxe.co.zw

You can also change the colors in the inline styles:

-   Name: `#263b52`
-   Accent line: `#55b8ed`
-   Contact text: `#40566d`
-   Labels: `#8799a9`
-   Background: `#ffffff`

When changing the email address, update both the visible text and the
`mailto:` link. Do the same for phone numbers and their `tel:` links.

## Project structure

``` text
My-Gmail-Signature/
├── README.md
└── signature.html
```

## Browser and email-client notes

This signature is designed for use in Gmail. Email clients may render
some CSS properties differently, so check the pasted signature by
sending a test email to yourself before using it.
