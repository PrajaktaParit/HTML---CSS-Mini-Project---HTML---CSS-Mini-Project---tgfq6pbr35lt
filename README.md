This is a Mini Project on  Responsive food delivery website 

The title of the website is Super_Meals. It contains several sections like Home, Services, Clients and Contact Us and ends with a copyright footer. Below is the detailed information about the website and its contents.

1.	NAVIGATION-BAR

A.	HTML 

a.	I have created a nav-bar with an attached an image to it representing the company’s logo. 
b.	Then I have added several to li’s to it sections like Home, Services, Clients and Contact Us.

B.	CSS

a.	The nav-bar section has been given flex properties to align the contents in one line.
b.	All the elements are aligned to center
c.	The nav-bar is positioned sticky so that even after scroll it remains on the top.
d.	A black background is added with z-index= -1. And position as absolute.
e.	The list elements are given text-decoration: none; property to remove the underline from the anchor tags.

2.	HOME-SECTION

A.	HTML

a.	The home section consists of heading, short description and a button of “Order Now”.
b.	This section has id as home.
c.	The heading has given a class name as h-primary.

B.	CSS

a.	A background-image is added with z-index= -1. And position as absolute, using ‘before’ pseudo element.
b.	The home section has been given flex properties to align the contents to center in a vertical line by giving flex-direction: column
c.	The button has been provided with appropriate css and hover properties.

3.	SERVICES-SECTION

A.	HTML

a.	This section has an id of services-container.
b.	It has a heading tag and 3 divs representing the services .these divs are enclosed in another div of id services.
c.	Each div has an image, heading and description.

B.	CSS

a.	The services-section has been given flex properties to align the contents in one line.
b.	The divs have given border properties to add aesthetic.
c.	Suitable properties are given to the image, heading and description.

4.	CLIENTS-SECTION

A.	HTML

a.	This section has an id of client-section.
b.	It has a heading tag and 4 divs representing the clients. These divs are enclosed in another div of id clients.
c.	Each div consist of an image representing the company logo.

B.	CSS

a.	This section has been given flex properties to align the contents in one line.
b.	All the elements are aligned to center
c.	The divs are given padding property to separate them from another divs
5.	Contact-Section

A.	HTML
a.	This section has an id of contact.
b.	It has a heading tag and div which contains a form inside it
c.	The form consists of several elements like Name, Email, Phone-Number and Message.
d.	Each input has a label with ‘for’ attribute.
e.	The form ends with a submit button.

B.	CSS

a.	A background-image is added with z-index= -1. And position as absolute, using ‘before’ pseudo element.
b.	This section has been given flex properties to align the contents in one line.
c.	All the elements are aligned to center
d.	The elements are given width, padding and border properties.
e.	The Submit button has display: block property then given auto margin
f.	Suitable hover properties to the button are added. With pointer cursor on hover

6.	FOOTER-SECTION

A.	 HTML
a.	This section has a div with copyright message in it.
b.	I have used &copy property of VS code for the copyright.

B.	CSS
a.	The footer has black background with white font color and padding.


RESPONSIVE CSS-PROPERTIES

1.	Using media query property with max-height: 1206px, the website is made responsive by adding suitable properties to the elements mentioned above
2.	The client-section having flex property have given flex wrap property in the media query so that the elements come one below another when width is reduced below 1206px.
3.	To avoid the overflow of the content in services section the flex-direction:column property is given so that the content covers the entire width.





