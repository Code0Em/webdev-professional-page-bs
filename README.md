# Web Developer’s Professional Page (Bootstrap)

## Contents

* [Description](#description)
* [Build](#build)
* [Installation](#installation)
* [Usage](#usage)
* [Credits](#credits)
* [License](#license)
* [Acknowledgments](#acknowledgments)
* [References](#references)

## Description

This project is an iteration of the [Web Developer’s Professional Page (2023)](https://code0em.github.io/webdev-professional-page/). The aim of this project was to build a portfolio to showcase the developer’s work. The motivations for this included bolstering the developer’s public image and consolidating their deployed applications into a ‘one-stop-shop’ that is easily accessible to potential employers.

In this iteration of the project, however, the brief specified that the page should make use of Bootstrap.

The project criteria also included creating a page that displays the developer’s name and avatar in a jumbotron and sections to portfolio their recent work, their skills and details about them (including their contact details). The former two criteria (jumbotron and skills section) were additional criteria for this iteration of the project.

The specification for the footer section (also specific to this iteration of the project) was to include a hover effect on all hyperlinks in the footer, which display a box shadow upon hover.

As with the original project brief, the page was required to be responsive on various screens and devices.

## Build

To meet the aims of the project, Bootstrap layouts (e.g. containers, grids), components (e.g. navbar, cards, buttons) and more were utilised.

While the pages relies on Bootstrap’s styling for the most part, a custom CSS was also built to override some of this styling (e.g. font-family, color etc).

The page also relies on Bootstrap for its ‘built-in’ responsiveness, however two custom media queries were added for stylistic preferences at resolutions equal to or greater than 768px (i.e. Boostrap’s medium breakpoint).

## Installation

N/A

## Usage

Users navigate to the webpage via the URL ([Code Em - Web Developer](ADD LINK WHEN DEPLOYED)). When on the webpage, users can navigate to different sections of the page via the hyperlinks in the navigation bar.

Call to action (CTA) buttons within the jumbotron, built projects and about sections also prompt users to immediate action. For example, to visit the projects showcased on the page, users can select the CTA button labeled “Visit [project name]” and will be navigated to said project’s external page.

Note: Whilst some projects remain ‘in the making’ (i.e. are not yet available to visit), a Bootstrap modal has been used to display a ‘coming soon’ message when the user selects these associated CTA buttons.

The webpage on a resolution of 1400px (or higher) will display as follows:

![Screenshot of Code Em Web Developer Bootstrap homepage](./images/webdev-professional-page-bootstrap-screenshot.png)

Note: On resolutions of 1399px or below, aspects of the pages will display differently. For example, on resolutions equal to or less than 768px, the project images will appear in full (i.e. not cropped according to ratio) and will be positioned above the project header, text and CTA button.

## Credits

Credit given to Bootstrap (no date) for the icons utilised in the built projects and footer sections.

Credit given to smugglerFlynn, whose Stack Overflow (2013) response helped to solve how to override Bootstrap’s styling (credit also cited in code comments). Credit also given to W3Schools (no date) for their box-shadow colour combination, which was used on the hover effect in the footer section (credit also cited in code comments).

Credit given to the avatar-maker tool, which was used to create the avatar displayed in the jumbotron. All references listed below. 

## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

## Acknowledgments

Code written by Code0Em ([email](mailto:code.em@outlook.com)/ [GitHub](https://github.com/Code0Em)).

## References

Anon (no date) [*Avatar Maker*](https://avatarmaker.com).

Bootstrap (no date) [*Bootstrap Icons - Official open source SVG icon library for Bootstrap*](https://icons.getbootstrap.com/).

smugglerFlynn via Stack Overflow (2013) [*How can I override Bootstrap CSS styles?*](https://stackoverflow.com/questions/20721248/how-can-i-override-bootstrap-css-styles).

W3Schools (no date) [*CSS Box Shadow*](https://www.w3schools.com/css/css3_shadows_box.asp).
