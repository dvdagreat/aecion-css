# aecion-css
A minimalistic CSS framework made only for layouts using flexboxes and SASS. Pretty much whole framework is overridable for customization.

Note: The current version does NOT support responsive design. It is still a work in progress. A New Branch will be added soon with responsive support.


# what?

-> Aecion-css is a CSS layout framework or basically a bunch of ready-to-use CSS classes bundled together to help you structure your layouts.  
-> Aecion-css is built using flexbox model.


# why?

-> I like row-column layout, the flexibility they give. But other frameworks that provide these also come with other "bloat" (okay..okay.. features).  
-> I had to include large css and js files just to set a basic working layout.  
-> So created a lightweight framework that can be utilized only for layouts and nothing more. That's it. 


# how?

1) Clone the Master Repo (for now)
2) Super Important: '&lt;link&gt;' or '@import' the layout.css file located in public folder in your html file or js file.
3) Use the utility classes provided in the css file.

# prerequisites
1) html
2) css
3) display: FLEX !!

# Current List of classes and what they do

Note: apply all the below given given class only on a parent container and NOT on a child element.  

class: flex  
=> The most important class, give this to the parent element whose child are to be structured. This will make the target element a flex parent.  
  
class: inner-gap-5  
=> use this class to add padding inside a flex container. (value: 5px)  

class: inner-gap-10  
=> use this class to add padding inside a flex container. (value: 10px)

class: inner-gap-20
=> use this class to add padding inside a flex container. (value: 20px)

class: f-row  
=> use this class to make the elements in a flex parent, flow in a row direction. Will display child elements from left to right. First child is displayed first, second child is displayed second, and so on.

class: f-row-rev  
=> use this class to make the elements in a flex parent, flow in a reverse row direction. Will display child elements from right to left. Last child is displayed first, second to the last child is displayed second, and so on.

class: f-col 
=> use this class to make the elements in a flex parent, flow in a column direction. Will display child elements from top to bottom. First child is displayed first, second child is displayed second, and so on

class: f-col-rev  
=> use this class to make the elements in a flex parent, flow in a reverse row direction. Will display child elements from bottom to top. Last child is displayed first, second to the last child is displayed second, and so on.

class: j-center  
=> use this class to justify the content in center. 

.j-space-around  
=> use this class to justify the content until the very end on edges of the parent container

# documentation for other classes coming soon! sit tight!
