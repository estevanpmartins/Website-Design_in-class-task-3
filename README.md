The best way to learn how to code web pages is by actually doing it! Let's practice and create three pages: home page (index.html) with two content pages: services page (services.html) and contact page (contact.html).

1. If you had printed papers to organize you would probably store them in a paper folder. Web designers store and organize their computer files by creating a folder on a hard drive (or portable storage such as an SD card or Flash drive) for each website. This helps them to be efficient as they work with many different websites. You will organize your own web design work by creating a new folder for each website and storing your files for that website in the new folder. Use your operating system to create a new folder named mypractice for your new website.

2. Create the Home Page. Use the Trillium Media Design web page (Figure 2.19) as a starting point for your new home page (shown in Figure 2.25). Copy the sample file (structure.html) from the In-ClassTask3.zip file into your mypractice folder. Change the file name of structure.html to index.html. It’s common practice to use the file name index.html for the home page of a website.
Figure 2.25 New index.html web page
Launch a text editor or IDE, and open the index.html file.
a)	The navigation hyperlinks will be located within the nav element. You will edit the code within the nav element to configure three hyperlinks:
	The text “Home” will hyperlink to index.html
	The text “Services” will hyperlink to services.html
	The text “Contact” will hyperlink to contact.html
Modify the code within the nav element as follows:
<nav>
      <b><a href="index.html">Home</a>  &nbsp;
         <a href="services.html">Services</a>  &nbsp;
         <a href="contact.html">Contact</a> 
      </b>
</nav>
b)	Save the index.html file in your mypractice folder. Test your page in a browser. It should look similar to Figure 2.25. You can compare your work to the sample in the student files (chapter2/2.14/index.html).

3. Create the Services Page. It is common practice to create a new web page based on an existing page. You will use the index.html file as a starting point for the new services page, shown in Figure 2.26.
Figure 2.26 The services.html web page
Open your index.html file in a text editor and save the file as services.html. 
Edit the code as follows:
a)	Modify the title of the web page by changing the text between the <title> and </ title> tags to “Trillium Media Design - Services”. In order to create a consistent header, navigation, and footer for the web pages in this website, do not change the code within the header, nav, or footer elements.
b)	Position your cursor in the body section and delete the code and text between the opening and closing main tags. Code the main page content (heading 2 and description list) for the services page between the main tags as follows:
<h2>Our Services Meet Your Business Needs</h2>
  <dl>
    <dt><strong>Website Design</strong></dt>
      <dd>Whether your needs are large or small, Trillium can
      get you on the Web!</dd>
    <dt><strong>E-Commerce Solutions</strong></dt>
      <dd>Trillium offers quick entry into the e-commerce
      marketplace.</dd>
    <dt><strong>Search Engine Optimization</strong></dt>
      <dd>Most people find new sites using search engines.
      Trillium can get your website noticed.</dd>
  </dl>
c)	Save the services.html file in your mypractice folder. Test your page in a browser. It should look similar to Figure 2.26. You can compare your work to the sample in the student files (chapter2/2.14/services.html).

4. Create the Contact Page. Use the index.html file as a starting point for the new Contact page, shown in Figure 2.27. Open your index.html file in a text editor and save the file as contact.html. Edit the code as follows:
Figure 2.27 The contact.html web page
a)	Modify the title of the web page by changing the text between the <title> and </ title> tags to “Trillium Media Design – Contact”. In order to create a consistent header, navigation, and footer for the web pages in this website, do not change the code within the header, nav, or footer elements.
b)	Position your cursor in the body section and delete the code and text contained between the opening main tag and the closing main tag. Code the main page content for the contact page between the main tags:
<h2>Contact Trillium Media Design Today</h2>
   <ul>
     <li>E-mail: contact@trilliummediadesign.com</li>
     <li>Phone: 555-555-5555</li>
   </ul>
c)	Save the contact.html file in your mypractice folder. Test your page in a browser. It should look similar to Figure 2.27. Test your page by clicking each link. When you click the “Home” hyperlink, the index.html page should display. When you click the “Services” hyperlink, the services.html page should display. When you click the “Contact” hyperlink, the contact.html page will display. You can compare your work to the sample in the student files (chapter2/2.14/contact.html). 

5. In this part of the In-Class Task, you will modify the contact page (contact.html) and configure an e-mail link in the page content area.
Configure the e-mail address as an e-mail hyperlink as follows, but type the entire anchor element on a single line.:
<li>E-mail:
<a href="mailto:contact@trilliummediadesign.com">
contact@trilliummediadesign.com</a>
</li>
Save and test the page in a browser. 
The browser display should look similar to the page shown in Figure 2.28.
