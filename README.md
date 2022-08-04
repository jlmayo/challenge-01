# challenge-01: Refactoring Code to Meet Accessibility Standards

## **Table of Contents**
* [The Repository](#the-repository-br)
* [The Scenario](#the-scenario)
* [The Process](#the-process)
* [Specific Changes Made](#specific-changes-made)
* [Result](#result)
* [Contributors](#contributors)

### **The Repository**
This repository (challenge-01) contains HTML code, a CSS stylesheet, and image attachments for the stylesheet in response to an on-the-job ticket challenge for Week 1 of University of Arizona Coding Boot Camp.

### **The Scenario**
A marketing agency requested a restructuring of their codebase in order to meet current accessibility standards, thereby improving their site's search engine optimization as well.

### **The Process**
Starter code was provided for this refactor project. Without altering the design of the original page, the HTML and a CSS Stylesheet were modified to improve overall semantics. All links were reviewed and found to be functional.

### **Specific Changes Made**

#### HTML Updates
* Updated `title` to be more specific and detailed.
* Added `span` section under the `header` parent in order to provide an alt attribute for the header background image.
* Renamed the `div` section under the `header` parent. It became `nav` to better describe the text within the header that functions as a navigation bar.
* Moved `li` items to the left to show proper indentation.
* Renamed `div class="hero"` to `figure class="hero"` since it contains the header image.
* Renamed the next `div` as section and the following `div` child as article because the area underneath of the header image was a section of its own that contained 3 more sections. Instead of using `section` for all of them, I used `article` because the content was a short blurb describing a product.
* Within `article`, I updated the names of the classes to reflect changes made to the names in CSS.
* Added alt attributes to all of the images in the article section.
* Changed `div class="footer"` to `footer class="footer"`. Instead of `h2` for the first line of text, I changed it to `p` with a line break `br /`.

#### CSS Changes Made
* All changes made to the CSS Stylesheet can be found within the stylesheet itself as comments.

### **Result**
The code in this assignment does now meet accessibility standards, and should perform better for search engines. It is cleaner, more specific, functional, and follows a logical structure. Deployment is error free.

### **Contributors**
While the refactored code is my own, I had tremendous help from classmates in study sessions, my instructor and TA in office hours, and from my tutor in getting Git to work properly, recognizing and editing errors in the nav bar, and in consolidating the CSS code. 

You can find my site at [Challenge-01](https://jlmayo.github.io/challenge-01/)

## **Completed Project**
![Screenshot of Horiseon Web Page](assets/images/Challenge-01%20Screenshot%20of%20Horiseon.png)
