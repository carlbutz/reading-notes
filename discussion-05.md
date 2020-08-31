# Summary of Chapter 18

Chapter 18 talks about the **process** of creating a web site and how to **design** web site. 

Before one even starts to create a web site, there are a number of questions they _must_ know the answers to:
1. **Who is my target audience?** Even though I would like to think it is everyone, that is not reality. We need to figure if it is an individual or a company I am targeting. We need to look at age, gender, marital status, number of kids... when looking at individuals. We need to look at size of company, position of people inside the company, and what budget control do they have when looking at companies?
2. **Why are they visiting the site?** Is it for entertainment? Are they trying to accomplish something? Is this for relaxation? Is it essential they are here?
   - What are the visiters trying to achieve?
   - What information do they need?
3. **How often will the vistor return?**
   - Do I need to set a schedule to do updates to the site? For information?  For inventory?
   - Are there parts of the site that need to be updated more frequently?

Once you are able to answer the above questions, it is time to organize your site.
1. **Sitemap** - This will help organize where the pages need to go based on categories.

Home | Contact Info | History | Inventory
---- | ------------ | ------- | ---------
Welcome |  Email, Phone, Address | Beginning | Product Category 1
| | | Last 5 Years | Product Category 2
| | | | Product Category 3
        
2. **Wireframe** - Helps layout how the pages in the site will look<br>
_____________
    Logo         
_____________
_______________________________________
Link 1    Link 2     Link 3     Link 4 
_______________________________________
Content
_______________________________________
Footer Information Goes Here           
_______________________________________

Once you have the basic design, it is now time to get your message out there using some design ideas
1. **Content** - What the visitors are looking for
2. **Priotitizing** - By using these tools, what are you trying to get the visitor to look at?
3. **Organizing** - By using these tools, the site will look pleasing and convey the message in a nice and friendly manner
4. **Visual Hierarchy** - 
   - Size - by using different sizes, the visitor's eyes will be drawn to different areas of the screen
   - Color - by using different colors, you can brand your product by having similar colors. Different colors also help draw a visitor's eyes to certain areas. You do have to be careful so there are not so many colors that the site becomes difficult to read.
5. **Grouping and Similarity** - 
   - Proximity - When items are placed close together, they appear to be more related then items spread out more.
   - Closure - This is a complicated arangement of items, but still in an organized, recognisable pattern.
   - Continuance - When items are placed in line or a curve, just like proximity, they appear to be related. But this also leads from one area to the next.
   - White Space - This is the area that seperates items that are grouped together, giving the appearance that each of the groupings are realated to other items in the group, but not to the other groups.
   - Color - Using a colored back ground brings items together and inter-relates them.
   - Borders - Using a border to outling a group brings items together and inter-relates them.
   
Now that we have the who, the why, the look we need to be able to get visitors from one page to another. To do this, we use **site navigation**. In site navigation, the visitor is able to get back and forth between pages. In order to do this we must be
1. **Be Concise** - Limit the number of options
2. **Be Clear** - Let the visitor know where they are going
3. **Be Selective** - Not everything needs to be in the navigation, maybe have multiple items on a page, if it makes sense
4. **Have Context** - Remind the visitor not only where they are going, but where they currently are in the site
5. **Be Interactive** - Have the links big enough to click on, and have some sort of indication the link is being hovered over and being clicked
6. **Be Consistent** - Try to keep the navigation as simiar from page to page. There may be minor differences, but the majority should be matching.

# Skiming Chapter 1
I took the Code 101 class, so just skimmed this chapter. The big take away is you need _tags_ to make a web site to look the way you want it to. Typically the are starting and ending tags. A starting tag will look something like this < body > (spaces added so it did not code). An end tag will look something like this < /body >(spaces added so it did not code). 

# Summary of Chapter 17
Chapter 17 talks about tags that are used to layout the basic structure of an HTML 5 page. This has changed with HTML 5 not needing to use the div tag as often. These tags will need an open tag <> and a close tag</>. When discussing these tags below, I will be using the key word only and not the tag markers, this is for simplicty as I am not trying to design a page.

Tag | What it does
--- | ---
header | Can be used as part of the overall body of the site, or inside an article or section. This will be used at the top of each page/article/section, and will make the areas look uniform. Logos, menus and items like that may appear here.
footer | Can be used as part of the overall body of the site, or inside an article or section. This will be used at the bottom of each page/article/section, and will make the areas look uniform. Copywrite information or contact information may appear here.
nav | Is used to contain the navigational blocks for the site.
article | Groups content that stands alone.
aside | There are two ways this is used. When inside an article, it contains information related to the article, but not essential to the article. An example would be a quote from the article. When not inside an article, It is content that is related to the entire page. An example would be a list of additoinal posts by a blog author.
section | These are groupings of information that are not articles, but small chunks of data like related links or contact information. Typically they will have their own header (not an H2) telling what the section is.
hgroup | Groups other headers (2-6) together. This has mixed reception and is not used by all.
figure | This is information or an image that is referenced in the main flow of the page. 
figcaption | The text description of the figure
div | Even though this is not used as much in HTML 5, it is still used to group content together
a | This is an anchor, and can be used to make everything in the tag to be an HTML link

We must remember that HTML 5 is new, and may not be usable by older browsers. We should create a CSS that will work with older browsers to ensure their usability with HTML 5.
