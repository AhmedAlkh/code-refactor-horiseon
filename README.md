# code-refactor-horiseon
HTML CSS Git Challenge: Code Refactor

Objective
Refactor an existing site to make it more accessible and optimized for search engines.

!screenshot(https://github.com/AhmedAlkh/code-refactor-horiseon/blob/main/Horiseon - Onlin.png.raw=true)

Step 1: Modify HTML

Added comments to organise different sections of code in the index.html file.

<!-- Head section -->

1. <title></title> changed from "website" to "Horiseon - Online Buisness Developement".

<!-- Header/Navigation-->

1. Changed <div class="header"> to <header>.

2. Changed <div> to <nav>.

3. Fixed "Search Engine Optimization" navigation link by adding "id" to the related portion in the content section.

<!-- Content section -->

1. Added alt attributes to images.

<!-- Benefits section -->

1. Deleted unessescary </img> for cost management line 88.

2. Added alt attributes to images.

<!-- Footer -->

1. Changed <div class="footer"> to <footer>.

2. Changed the year 2019 to 2021 in line 102.

Step 2: Modify CSS

1. Adding comments to organize different sections.

2. Adjusting code the match changes to HTML. EX. <div> to <nav>

3. Moving selectors that are out of place into correct sections. 

4. Compressing code by removing duplicates. (Keep it DRY).

ADDITIONAL HTML CHANGES

1. Changed classes in content section to all be class="content-section"

2. Changed classes in benefits section to all be class="benefits-section"