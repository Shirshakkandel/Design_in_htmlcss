# Design_in_htmlcss
# 1)Trypography
```css
h1 {
  margin-bottom: 24px;
  font-size: 44px;
  /* for normal 16 to 32 px for heading above 32px */
  line-height: 1.1;
/*  for heading below 1.5 and for normal text use 1.5 to 2  */
  letter-spacing: -1px;
  /* For heading letter spacing should be less */
}
```

# 2)Color
 [open color](https://yeun.github.io/open-color/)
 [tailwind css](https://tailwindcss.com/docs/customizing-colors)
 [Flat ui](https://flatuicolors.com/)
 [Cooler](https://coolors.co/contrast-checker/)
 1. main and gray color (at least 2 color in website)
 2. secondary color(or Accent color)
 3. light and dark version of this color
## 72)Implementing colors
```css
:root {
  --green: #087f5b;
  --gray: #343a40;
  --light-gray: #343a40;
}
```

# 3)Images
1. Unplash
2. Pexels
3. Drawkit
4. unDraw

## Methods for using text in images
1. darker or brighten image using gradient
2. Position text into neutal image area
3. put text into box
4. use squoosh to compress image upto 96%
   
# 4)Icons
1. Use icons to provides visual assistance to text
2. use icons for product feature blocks
3. associated with actions,and label them 
 
 ## implementing of icons


# 5)shadow
1. dont add shadows to every element
2. dont make shadow too dark
3. draw attention
4. medium-sized shadows(card.)
5. large shadow(navigation and popover)
6. changing shadows on mouse interaction.
7. glows(colored shadows)

## implementation of shadows in css
```css
.chair {
  box-shadow: 0px 20px 30px 0px rgba(0, 0, 0, 0.178);
}

h1 {
  margin-bottom: 24px;
  font-size: 44px;
  line-height: 1.1;
  letter-spacing: -1px;
  text-shadow: 0 2px 3px rgba(0, 0, 0, 0.2);
}

```




# 6)Border radius

```css
.chair img {
  /* border radius of bottom to be 0 */
  border-bottom-left-radius: 0;
  border-bottom-right-radius:0;
}
.btn:link,
.btn:visited {
  background-color: var(--green);
  color: white;
  text-decoration: none;
  display: inline-block;
  font-weight: 500;
  text-transform: uppercase;
  display: inline-block;
  border-radius: 999px;
  /* to make round 50% only work on square but for other we have to give bigger size then element height */
}

```

# 7)Whitespace
1. between group of elements and betweeen elements.

# 8)visual hierachy 
1. visual hierachy is establishing which elements are most imp.
2. drawing attention
3. imp element closer to the top of the page.

# 9)User Experience(Ux)
1. how it works not how it looks and feels
2. use patterns that users know
3. make call to action the most prominent element
4. Use blue text and underline text only for links
5. animation should be purpose and fase between 200 and 500ms
6. place action buttons where they will create an effect

# 10)The website personalities-framework
1. **serius/elegant**=> design for luxury,base on thin serif. font, no shadow and border radius with big image.
2. **Minimalist/simple** => few images and icons and san serif, no shadow and border.
3. **Plain/neutral**=>



Chair selling sites(pratice of designing in htmlcss)
# 1)Trypography
```css
h1 {
  margin-bottom: 24px;
  font-size: 44px;
  /* for normal 16 to 32 px for heading above 32px */
  line-height: 1.1;
/*  for heading below 1.5 and for normal text use 1.5 to 2  */
  letter-spacing: -1px;
  /* For heading letter spacing should be less */
}
```

# 2)Color
 [open color](https://yeun.github.io/open-color/)
 [tailwind css](https://tailwindcss.com/docs/customizing-colors)
 [Flat ui](https://flatuicolors.com/)
 [Cooler](https://coolors.co/contrast-checker/)
 1. main and gray color (at least 2 color in website)
 2. secondary color(or Accent color)
 3. light and dark version of this color
## 72)Implementing colors
```css
:root {
  --green: #087f5b;
  --gray: #343a40;
  --light-gray: #343a40;
}
```

# 3)Images
1. Unplash
2. Pexels
3. Drawkit
4. unDraw

## Methods for using text in images
1. darker or brighten image using gradient
2. Position text into neutal image area
3. put text into box
4. use squoosh to compress image upto 96%
   
# 4)Icons
1. Use icons to provides visual assistance to text
2. use icons for product feature blocks
3. associated with actions,and label them 
 
 ## implementing of icons


# 5)shadow
1. dont add shadows to every element
2. dont make shadow too dark
3. draw attention
4. medium-sized shadows(card.)
5. large shadow(navigation and popover)
6. changing shadows on mouse interaction.
7. glows(colored shadows)

## implementation of shadows in css
```css
.chair {
  box-shadow: 0px 20px 30px 0px rgba(0, 0, 0, 0.178);
}

h1 {
  margin-bottom: 24px;
  font-size: 44px;
  line-height: 1.1;
  letter-spacing: -1px;
  text-shadow: 0 2px 3px rgba(0, 0, 0, 0.2);
}

```




# 6)Border radius

```css
.chair img {
  /* border radius of bottom to be 0 */
  border-bottom-left-radius: 0;
  border-bottom-right-radius:0;
}
.btn:link,
.btn:visited {
  background-color: var(--green);
  color: white;
  text-decoration: none;
  display: inline-block;
  font-weight: 500;
  text-transform: uppercase;
  display: inline-block;
  border-radius: 999px;
  /* to make round 50% only work on square but for other we have to give bigger size then element height */
}

```

# 7)Whitespace
1. between group of elements and betweeen elements.

# 8)visual hierachy 
1. visual hierachy is establishing which elements are most imp.
2. drawing attention
3. imp element closer to the top of the page.

# 9)User Experience(Ux)
1. how it works not how it looks and feels
2. use patterns that users know
3. make call to action the most prominent element
4. Use blue text and underline text only for links
5. animation should be purpose and fase between 200 and 500ms
6. place action buttons where they will create an effect

# 10)The website personalities-framework
1. **serius/elegant**=> design for luxury,base on thin serif. font, no shadow and border radius with big image.
2. **Minimalist/simple** => few images and icons and san serif, no shadow and border.
3. **Plain/neutral**=>


