 
# Innoloft's Dashboard for displaying product

<!-- OVERVIEW -->

### Product Page (`/product`)
  - Product image
  - Product main info contains
    - title
    - type
  - 2 tab buttons to switch/change the tab content
    - Description
    - Attributes
  - Description tab contains product description
  - Attributes tab contains:
    - categories (name only, free text input when adding/editing)
    - business models (name only, free text input when adding/editing)
    - [TRL](https://en.wikipedia.org/wiki/Technology_readiness_level) (single choice field)
  - User info contains:
    - user image
    - user name
    - user company name
  - Map displays company address on Google maps (bonus)

## Finished app screenshot
 ![innoloft-mobile](https://user-images.githubusercontent.com/60210091/151350799-c113c043-5fce-474d-81e6-b40f6c2d6d20.jpg)

 ![innoloft-tablet](https://user-images.githubusercontent.com/60210091/151350826-5b39dae7-49c4-4a33-97a6-8265e5806413.jpg)

## Design
**Design** : https://www.figma.com/file/Gw0ZNBbYN8asqFlZWy3jG1

## Features
  - Built with React Hooks when applying Redux, and CSS 
  - Fetch some data from an API. The API base url is `https://api-test.innoloft.com`
      Product
        - GET `/product/6781/`
        - PUT `/product/6781/`
        - TRL List
        - GET `/trl/` 
 
## Built With
- [React](https://reactjs.org/)
- [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
- Redux

## Example Mockup
![mockup](mockup.jpg)

## How To Use

<!-- Example: -->

To clone and run this application, you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

```bash
# Clone this repository
$ git clone https://github.com/ganamavo/Frontend-Application.git

# Install dependencies
$ yarn install

# Run the app
$ yarn start 
``` 

## Contact

<!-- -   Website [your-website.com](https://{your-web-site-link}) -->
-   GitHub [@ganamavo](https://github.com/ganamavo)
-   Twitter [@rinon](https://twitter.com/Tojo_Rinon)
