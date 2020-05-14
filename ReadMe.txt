Learning HTML fundamentals from pluralsight and practise html files will be committed


1. Creating a basic html document with Doctype, html, head, title and body tag

2. using validator.w3.org site, validating the html and warning message came to specify the language in html document. so adding language in html tag

3. adding meta data to the html file with attributes as name and content. this meta doesnt require closing tag like other elements

4. adding link tag with reference link to css style sheet
and change the body content with class=lead to apply style to content in body

5. adding javascript

6. Inside body we can have 
     Text
     List
     Tables
     images
     links

7. Adding id and name attribute to body element. both id and name should be unique. 
we can use this id and name for apply a style to specfic element and used in javascript prgrammes as weell



Module 2: Displaying Text

2.1 i have added heading tage h1 and h2. in browser, it shows different in size

2.2 Difference between heading, paragraph tag, text with out paragraph

2.3 Block elements <div>
    <div> tag is used to combine few elements into one segment. 
    web page might have <div id= header> and <div id=body>. so this means header div contains few elements part of header. 
    you can <p> tag elements in <div>
    you can <div> tag inside <div>
    Adding div tag , you wont see much differene in html rendering. but it help in segrate the set of elements while applyig style

2.4 Line breaks, whitespace, &nbsp, &gt , &lt , &copy
   &nbsp --> this tells the browser the space between two words should not be broken into seprate Line
   &gt, &lt --> introduce greater than and lower than symbole in the browser
   &copy --> shows copywright symbol on the browser

2.5 Reference text:
     <blockquote> --> This will display the text in block letter
     <q> - This will display text with added double quatation
     <cite> - This will display text in different style.
     <abbr> - This will display text as it is. when you mouseover to text, it will display the title of the abbrevation.

2.6 Semantic Tags

    From HTML 5 onwards this semantic elements is introducted. with help of semantic tag we can manage elements easily.
     Like in a web page we are having header and footer and with older HTML we use <div> tags for those. 
     but in HTML 5, there is semantic tag available as <header> , <footer> and <section>



3. List in HTML
      There are 3 types of list in HTML
       * Unordered List
       * ordered List
       * Mordern List

 3.1 Unordered List:
      <ul> 
      <li> </li>
      <li> <li>
      </ul>

      above is basic mark up syntax for unordered list. It is shows with bullet ordered

3.2 Ordered List
  <ol> 
  <li> </li>
  <li  </li>
  </ol>

  above is basic markup syntax for ordered list 

4. Linking in HTML
    There are two basic linking 
      1. Relative link ==> a html which is available in site itself. like pointing to another html iniside the project
      2. Absolute link ==> a link which point to external website

      For Relative link:
      <a href="./content/abc.html"> ABC </a>

      For Absolute link:
      <a href ="http://www.pluralsight.com"> pluralsight </a>

  4.1 Linking to Targets:
        Linking target means, if you a click a link it will take to you to specfic section within document.   
        we need to use # symbol, to specify the target.

        <a href="#demo"> Demo </a>

        above code will navigate to section which is have id as demo.

        <a href="./contents/recepies.html#demo"> receipes demo </a>

  4.2 Link Attributes
     There are many attributes available to <a>  tag elemnet
     one of them is "target"

     <a href="www.youtube.com" target="_blank"> youtube </a>

     above code will open youtube in seprate window or tab

5. Table
      We use HTML table to display data not for display content of page or any other things
There are 4 basic things for table
 1. <caption> TableName </caption>
 2. <thead> </thead> ==> Headers of the table
 3. <Tbody></tBody> ==> Body of the table
 4. <tfoot></tfoot> ==> footer of the table to display sum or aggregate value.

 Now for every table has rows and columns 
  <tr> </tr> ==> Table row
  <th> </th> ==> head of the table. usually first row in the table
  <td> </td> ==> is for table data in the cell.

6. Images
 To insert images on webpages 

 <img src="dhonix.jpg">  
     