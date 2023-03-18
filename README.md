# <p style="text-align: center; font-size: 40px;">**Woofing Walks**</p>
[View the Woofing Walks live website here](https://abz2489.github.io/woofing-walks/)

Woofing Walks is a dog walking service based in the Rhondda Valleys. The aim of the website is to promote Woofing Walks' services and attract new customers to the business. Woofing Walks is aimed at dog owners looking for trusted dog walkers in their local area. 
The website provides in depth information of what new customers can expect from their services. It also inludes walk times, prices & contact information.

______________
## **User Experience (UX)**
### **User Stories**

#### **First Time Visitor Goals**
- To easily identify what Woofing Walks is.
- To easily navigate the Woofing Walks website for more information.
- Easily find contact information to book.
- To access Woofing Walks' social media.

#### **Returning Visitor Goals**
- To find a price list or hourly rate for walks.
- To see testimonials from recent customers of Woofing Walks.

#### **Frequent Visitor Goals**
- To find information on other services Woofing Walks offers.

## **Design**
### Colour Scheme
### Typography

## Wireframes

-------------------------------------
## **Features**

### Existing Features
### Future Features

-------------------------------------
## Technologies Used

### Languages Used
- HTML5
- CSS3

### Frameworks, Libraries & Programs used
- Balsamiq
- Git
- GitHub
- Bootstrap 5.3
- Font Awesome
- Google Fonts

-------------------------------------
## **Testing**
### W3C Validator Testing
[Index Page HTML](https://github.com/abz2489/woofing-walks/blob/main/docs/readme/testing/w3c/w3cindex.png)
### Solved Bugs
1. Footer has small gap at the bottom and cuts off bottom content on mobile devices. Content cut off fixed by switching from fixed-bottom to sticky-bottom. 

2. W3C validator showed error with nav buttons including a tags. I fixed this by removing the button tag, adding a button class and styling the button using CSS. Fixing this error affected my "more info" button in my hero image section. This was easily fixed by adding the button class previously used.

3. Whitespace showing to the right of index page. I used Chrome dev tools and found that the bootstrap row class was adding unwanted gutter. I removed this by using g-0 class alongside the row class.

4. Contact Form page has whitespace to the right. Using dev tools, I could see that one of my row divs was creating thing but wasn't sure which one. I added background-color: red to one and background-color: blue to another to identify. I then added margin:auto to the problem div in CSS.

5. Nav buttons are showing too large on medium screens (768px) on the Index Page and Contact Page. Bug fixed by removing larger font size in the 768px media query.
### Unfixed Bugs
-------------------------------------
## **Deployment**

Woofing Walks' live website was deployed using GitHub Pages.

**Deployment Instructions:**
1. Sign in to [GitHub](https://github.com/login) or [Sign Up](https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home) for an account.
2. Find the [woofing-walks](https://github.com/abz2489/woofing-walks) repository.
3. Click settings.
4. Click the Pages link, found on the left hand navigation bar.
5. In the Build and Deployment section select the main branch and root folder.
6. Click Save, the live website is now deployed.

-------------------------------------
## **Credits**

https://www.joshwcomeau.com/animation/css-transitions/ - His article helped me with my transitions.
### Content
### Media

All images for Woofing Walks were sourced from [Pexels](https://www.pexels.com).
#### Index Page
-[Hero Image](https://www.pexels.com/photo/two-adult-harrier-dogs-standing-beside-river-1144410/)

-[About Page, Our Story section](https://www.pexels.com/photo/english-cocker-spaniel-puppy-sitting-on-ground-beside-grass-1254140/)

https://www.pexels.com/photo/two-adult-black-and-tan-german-shepherds-running-on-ground-1633522/
https://www.pexels.com/photo/a-dog-biting-a-branch-12729351/

-------------------------------------

