**CSS Fundamentals, Selectors, Specificity, Cascade**

**Topic Introduction/Overview**



**Cascading Style Sheets (CSS)**is a stylesheet language used to describe the presentation of documentswritten in HTML or XML. 

CSS controls the layout, colors, fonts, spacing, and visual effects of web pages,separating content (HTML) from presentation (CSS). 

The term "cascading" refers to the priority schemedetermining which style rules apply when multiple rules could affect the same element.



The core concepts that govern how CSS applies styles include selectors (how to target elements),specificity(which rule wins when conflicts arise), 

and the cascade (the overall algorithm that determines the final appliedstyles).



**Uses:**

Styling text, links, and images

Creating responsive layouts

Animating elements

Theming applications

Print stylesheets and accessibility adaptations





**Advantages:**

Separation of concerns (content vs. presentation)

Consistent styling across multiple pages

Reduced code duplication

Better accessibility and user experience

Easier maintenance and updates

Smaller file sizes through reuse





**Syntax \& its Explanation**

**Basic CSS Syntax:**



selector { 

property: value;

property: value;

}





**Cascade Order (when specificity is equal):**

1.Source order (last rule wins)

2.Importance (!important)

3.Origin (user agent < user < author)

4.Specificity



**Example Programs \& their Explanation**





**<!doctype html>**

**<html lang="en">**

&#x20; **<head>**

&#x20;   **<meta charset="UTF-8" />**

&#x20;   **<meta name="viewport" content="width=device-width, initial-scale=1.0" />**

&#x20;   **<title>Example</title>**

&#x20;   **<style>**

&#x20;     **.demo {**

&#x20;       **background-color: black;**

&#x20;     **}**

&#x20;     **h1 {**

&#x20;       **color: gold;**

&#x20;     **}**

&#x20;     **p {**

&#x20;       **color: red;**

&#x20;     **}**

&#x20;   **</style>**

&#x20; **</head>**

&#x20; **<body>**

&#x20;   **<div class="demo">**

&#x20;     **<h1>Welcome to KGCAS</h1>**

&#x20;     **<p>**

&#x20;       **Lorem ipsum dolor sit amet consectetur adipisicing elit. Ex nulla**

&#x20;       **voluptas facilis quia non, tenetur quo molestiae reiciendis, eveniet**

&#x20;       **odio aut illum incidunt nostrum esse fuga repellat saepe commodi vitae?**

&#x20;     **</p>**

&#x20;   **</div>**

&#x20; **</body>**

**</html>**







**Conclusion :** 



**CSS fundamentals form the bedrock of web styling. Mastering selectors allows you to precisely target elements,while** 

**understanding specificity and the cascade ensures you can predict and control which styles apply incomplex scenarios.** 

**The cascade is not just a feature but a well-defined algorithm that resolves conflictsdeterministically.**









































