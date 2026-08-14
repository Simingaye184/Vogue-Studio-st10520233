# Vogue Studio Website — README

## 1. Project Overview

**Vogue Studio** is a simple HTML website for a fashion and tailoring business. The website presents the studio, its services, an image, and a link for customers to book a fitting.

The website is designed to include the following pages:

* `index.html` — Home page
* `about.html` — About page
* `services.html` — Services page
* `contact.html` — Contact page

## 2. Requirements

To use this website, you need:

* A computer
* A web browser such as Google Chrome, Microsoft Edge, or Firefox
* A text/code editor such as Visual Studio Code or Notepad
* The website HTML files
* The Vogue Studio image (`vs.jpeg`)

No internet connection or server is required for the basic HTML website.

## 3. Project Folder Setup

Create a folder called:

```text
Vogue-Studio
```

Place all your website files inside this folder.

Your folder should look similar to this:

```text
Vogue-Studio/
│
├── index.html
├── about.html
├── services.html
├── contact.html
└── vs.jpeg
```

It is recommended that the image is stored inside the same project folder rather than using a file path from your Downloads folder.

## 4. Important: Fix the Image Path

The current code contains:

```html
<img src="c:\Users\Student\Downloads\vs.jpeg" alt="Vogue Studio Dress" width="400">
```

This is a **computer-specific file path**. It may work on your computer, but it will not work if you move the website to another computer or upload it online.

If `vs.jpeg` is in the same folder as `index.html`, change the code to:

```html
<img src="vs.jpeg" alt="Vogue Studio Dress" width="400">
```

This is the recommended method.

## 5. Creating the Home Page

Save your HTML code as:

```text
index.html
```

Make sure the file extension is `.html` and not `.txt`.

For example:

```text
index.html
```

not:

```text
index.html.txt
```

## 6. Running the Website

### Method 1 — Open Directly in a Browser

1. Open the `Vogue-Studio` folder.
2. Find `index.html`.
3. Double-click the file.
4. The website should open in your default web browser.

### Method 2 — Using Visual Studio Code

1. Open Visual Studio Code.
2. Select **File → Open Folder**.
3. Select the `Vogue-Studio` folder.
4. Open `index.html`.
5. Save your changes.
6. Open `index.html` in a browser to view the website.

If you use the **Live Server** extension in Visual Studio Code, you can also right-click `index.html` and select **Open with Live Server**.

## 7. Website Navigation

The navigation section contains:

```html
<a href="index.html">Home</a>
<a href="about.html">About</a>
<a href="services.html">Services</a>
<a href="contact.html">Contact</a>
```

This means the other HTML files must exist in the same project folder.

If a page does not exist, clicking its link will result in a "file not found" page.

## 8. Adding or Changing Images

To use another image:

1. Place the image inside the `Vogue-Studio` folder.
2. Change the image filename in the HTML.

For example:

```html
<img src="new-dress.jpg" alt="Vogue Studio Dress" width="400">
```

The filename in the HTML must exactly match the image filename.

For example:

```text
vs.jpeg
```

is different from:

```text
VS.jpeg
```

on some systems.

## 9. Editing the Website Text

You can change the text directly inside the HTML tags.

For example:

```html
<h2>Tailor-Made For Every Mbokodo</h2>
```

can be changed to:

```html
<h2>Fashion Designed Just For You</h2>
```

You can also change the paragraph:

```html
<p>Custom fits. Quality fabric. Confidence in every stitch.</p>
```

to any business description you prefer.

## 10. Changing the Image Size

The current image uses:

```html
width="400"
```

To make the image wider:

```html
<img src="vs.jpeg" alt="Vogue Studio Dress" width="600">
```

To make it smaller:

```html
<img src="vs.jpeg" alt="Vogue Studio Dress" width="250">
```

## 11. Important HTML Files

### `index.html`

This is the main/home page of the website.

### `about.html`

This page should contain information about Vogue Studio, its history, mission, or designers.

### `services.html`

This page can describe services such as:

* Custom dressmaking
* Alterations
* Bridal wear
* Traditional African clothing
* Event outfits

### `contact.html`

This page can contain contact information and a form for customers who want to book a fitting.

## 12. Common Problems

### Image is not showing

Check that:

* `vs.jpeg` is inside the project folder.
* The filename is spelled correctly.
* The image extension is correct.
* The HTML uses:

```html
<img src="vs.jpeg" alt="Vogue Studio Dress" width="400">
```

### Navigation link is not working

Check that the corresponding HTML file exists.

For example, this:

```html
<a href="about.html">About</a>
```

requires:

```text
about.html
```

to be in the same folder.

### Website changes are not showing

Save the HTML file and refresh the browser.

You can use:

```text
Ctrl + R
```

to refresh the page.

## 13. Recommended Project Structure

The final project should look like:

```text
Vogue-Studio/
│
├── index.html
├── about.html
├── services.html
├── contact.html
├── vs.jpeg
└── README.md
```

The `README.md` file is this documentation file.

## 14. Future Improvements

The current website uses basic HTML. You can improve it later by adding:

* CSS styling
* A navigation bar
* Custom fonts
* Background colours and images
* Responsive design
* A contact form
* Social media links
* A gallery
* Pricing information
* Online booking
* JavaScript functionality

## 15. Credits

**Website:** Vogue Studio
**Year:** 2026
**Purpose:** Fashion, tailoring, and custom clothing website

© 2026 Vogue Studio | We dress Mbokodos
