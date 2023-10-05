# Marketing Agency Refactor

## Project Overview

This repository is where I was assigned a ticket, which consisted of refactoring a client's already existing code from a marketing agency website, to improve the site's accessibility. 

This involved improving the code without making any actual changes to the function of the code itself.

### Benefits of this are as follows:
-	Ensures that people with disabilities can access the website using assistive technologies such as video captions, screen readers, and braille keyboards. 

-	To improve the position of the site in search engines such as Google.

-	It also helps companies avoid litigation that can occur when people with disabilities cannot access their websites.

## The website must meet accessibility standards

The requirements to meet the client's needs are listed below:
- HTML elements follow a logical structure independent of styling and positioning

- Image and icon elements contain accessible alt attributes

- Heading attributes fall in sequential order

- Title elements contain a concise, descriptive title

## Actions taken to meet these standards
### HTML:

- I added a descriptive title to the page metadata.

- I cleaned up the HTML code, structuring it in a way to make it easier to read.

- I swapped out the non-semantic div elements and replaced them with elements such as article, section and aside, and also added in the main element to enclose the main section of the webpage; below the navigation and above the footer sections.

- The Search Engine Optimization link within the navigation was not correctly linked, this was amended to ensure it directed the user to the correct section of the page.

- Comments were added above each code section, labelling the specific function of the HTML code for clarity of the codes output.

- I ensured heading attributes through the page fell in sequential order and established there was only one H1 element for the page, which was the companys business name. I also altered the H2 element within the footer to a more suitable H4 element.

- I added descriptive accessible alt attributes to all image and icon elements.

### CSS:
- I consolidated the CSS code to improve readability and maintainability. This consisted of grouping sections of code together which had the same properties and would still output the same function when consolidated.

- Comments were added above each code section labelling the specific function of the CCS code for clarity of the codes output.

- I removed redundant code, such as the following:

```md
header nav ul {
    list-style-type: none;
}

and

p {
    font-size: 16px;
}
```
## User Story
As a marketing agency, I want the codebase for our website to follow accessibility standards
so that our own site is not only optimised to rank higher in search engines but to also make sure people with disabilities can effectively comprehend and interact with the information presented on our site.
## Acceptance Criteria
Website must meet accessibility standards this will be achieved by completing the following:

- When semantic HTML elements have replaced all the necessary elements throughout the source code.

- When HTML elements follow a logical structure independent of styling and positioning.

- When image and icon elements contain accessible alt attributes.

- When heading attributes fall in sequential order. 

- When title elements contain a concise, descriptive title.

## Project Completion
Image One shows the web application's appearance and functionality after the refactor, showcasing the site looks in accordance with how outlined by the client, which can be seen in Image Two.
 
### Image one 
![Alt text](assets/images/Horiseon-Marketing-Agency-Service-Page.png)

### Image Two
![Alt text](assets/images/image.png)

### Webpage link:
A link to the live site can be found here: https://joshp369.github.io/marketing-agency-refactor 