# _Epicodus CSS module, Week 1_

#### _Project consists of a demo page for the Sylvia Beach Hotel, November 2017_

#### By _Holly Wilkalis_

## Description
This project is an exercise in page styling using only CSS styles to demonstrate knowledge of the following tools:
<html>
  <table>
    <thead>
      <th>TERM</th>
      <th>DESCRIPTION</th>
      <th>IMPLEMENTATION</th>
    <thead>
    <tbody>
      <tr>
        <td>border-box</td>
        <td>This is used to indicate that if the div element has modifications like padding, borders, etc., they should be included in the div's total width and height.</td>
        <td>I used this on several boxes on my page to create two columns of specified percentage widthand ensure that the content contained within would be displayed correctly within the page.</td>
      </tr>
      <tr>
        <td>float</td>
        <td>The CSS float property allows the element to which it is applied to float to either the right or left side of the page, with text flowing around it, while the floated elements remain a part of the regular flow of the page. </td>
        <td>I used this property to align two large content boxes on my page to different sides of the page.</td>
      </tr>
      <tr>
        <td>display: block</td>
        <td>Display: block displays the affected element as a block, similar to paragraphs and headers. A block will have whitespace above and will not allow any other HTML elements next to it, unless specifically instructed otherwise.</td>
        <td>I used display: block in the footer to style a block at the bottom of the page with the hotel's contact information that spans the width of the page with a block of color and text. While there are other ways that this could have been done, this was the most straightforward choice for this particular use</td>
       </tr>
       <tr>
         <td>display: inline</td>
         <td>Dislay: inline is used to style elements that will not have a defined/static height and width, and it will not create a new rows. (Display: block is to a p tag as Display:line is to span).</td>
         <td>I used this to create a nav bar composed of individual li items. I chose this over display:block because I didn't want it to create a new row within the layout. </td>
      </tr>
      <tr>
         <td>centered content</td>
         <td>Centered content is displayed with equal margins on the left/right, top/bottom or both. It can be accomplished in a variety of ways, depending on the type of content.</td>
         <td>I used centered content in several places (including a button and a header) in order to achieve a particular visual style</td>
      </tr>
      <tr>
         <td>pseudo-element</td>
         <td>A CSS pseudo-element is a keyword added to a selector that lets you choose and style a specific part (or parts) of the selected element. </td>
         <td>I used tr:nth-child(odd) and tr:nth-child(even) to provide a style table rows with alternating colored stripes. While this could also be accomplished by attaching a new class to specific rows within the HTML, doing it this way allows the color to be updated automatically as new rows are added or removed.</td>
      </tr>
      <tr>
         <td>pseudo-class</td>
         <td>A CSS pseudo-class is a keyword added to a selector that specifies a special state of the selected element(s). They also serve to apply a style to content not only as it relates to the rest of the document, but also in relation to external factors like the history of the navigator, content status, or the position of the mouse.</td>
         <td>I used psuedo classes in two places. First, to change the appearance of the reservation button when it is hovered on to indicate an action can be taken there. I also used it to create a popup on one of the room types to display more information specific to limitations of that room. This allowed me to highlight very specific items with out the need to write extensive additional codes or classes.</td>
      </tr>
      <tr>
         <td>clear-fix</td>
         <td>It is used to fix issues resulting from floating child elements within a parent element. Without a clearfix, when a HTML element is floated it can sit outside its parent element and the parent's height won't be adjusted accordingly, resulting in unexpected results in your layout when the page is viewed.
</td>
         <td>I used this on my left and right content boxes on the top half of my page to correct alignment issues resuulting from the use of floats. This could also have been achieved by changing the overflow settings. I'm still experimenting to see which works best in which circumstances.</td>
      </tr>
      <tr>
         <td>positional selector</td>
         <td>These are psuedo-elements used to select elements based on their position in the HTML</td>
         <td>I used tr:nth-child(odd) and tr:nth-child(even) to provide a style table rows with alternating colored stripes. While this could also be accomplished by attaching a new class to specific rows within the HTML, doing it this way allows the color to be updated automatically as new rows are added or removed.</td>
      </tr>
      <tr>
         <td>selector combinator</td>
         <td>Combinators result from two or more selectors being used together to make a more fine tuned selection - such as parent > child, which will selects any child	element that is a direct child of parent element.</td>
         <td>For this project I primarily used combinators to add specific styling to elements based on their parent - such as changing the appearance of link tags that fall within the nav div, or adding additional layout specifications to only images located within the bottom section of the page.</td>
      </tr>
    </tbody>
  </table>

## Setup/Installation Requirements

To install and access the files for this project:
* Open a new Terminal window
* cd to the directory where you wish to save the files
* Type the command $ git clone https://github.com/hollywilkalis/css-week-1 to download all files to your selected location.
* You can now access, view or edit the project files and assets.

To view a live version of this project, please visit http://hollywilkalis.github.io/css-week1

## Support and contact details

Questions about the project or recommendations for best rooms at the Sylvia Beach? I can be reached at holly.wilkalis@gmail.com.

## Technologies Used

This project uses HTML and a custom CSS.

## License

*MIT license*

Copyright (c) 2017 **Holly Wilkalis**
