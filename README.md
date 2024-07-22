# ADLP-Corp Recognition Test: Mini Report

## Introduction

This report documents the steps taken and techniques used to discover seven out of nine flags hidden within the adlp-corp.com website. The flags serve as proof of passage during the passive recognition test. Each flag was identified using various web reconnaissance techniques, which are detailed below.

## Flags Discovered

### Flag 1: CSS File

**Method Used:** Inspection of CSS files.

**Description:** While inspecting the stylesheets linked to the website using the browser’s developer tools, the flag was found embedded within a CSS comment. CSS files often contain comments which can sometimes be overlooked, making them a good place to hide information.

**Flag:** `QURMTHtDU1NfSFNCVVNHWUlHNTY5ODE2fQ==`

### Flag 2: Robots.txt

**Method Used:** Checking the `robots.txt` file.

**Description:** The `robots.txt` file is used by websites to provide crawling instructions to web robots and search engines. By navigating to `https://adlp-corp.com/robots.txt`, the flag was found within this file, which often contains information that web crawlers should avoid indexing.

**Flag:** `QURMTHtST0JPVFNfVFhUX0c1Njk4MTZ9`

### Flag 3: Sitemap.xml

**Method Used:** Examination of sitemap files.

**Description:** Sitemaps provide information about the pages, videos, and other files on a site, and the relationships between them. The sitemap file `https://adlp-corp.com/sitemap.xml` was examined, and the flag was found embedded within it.

**Flag:** `QURMTHtTSVRNNFBBU19YTUxfRzU2OTgxNn0=`

### Flag 4: HTML Comments

**Method Used:** Viewing HTML source code.

**Description:** By right-clicking on the website and selecting "View Page Source," HTML comments were inspected. These comments, which are not visible on the rendered webpage, contained the flag.

**Flag:** `QURMTHtIVE1MX0NPTU1FTlRfRkw0R19HNDU2Njg4fQ==`

### Flag 5: JavaScript Cookies

**Method Used:** Inspection of JavaScript files.

**Description:** JavaScript files can be inspected using the browser’s developer tools. A flag was found within a JavaScript file related to cookie management. This required searching through the scripts linked to the main page for any suspicious or commented-out code.

**Flag:** `QURMTHtKU19DT09LSUVTX0c3ODk0NTQ2NTY5ODE2fQ==`

### Flag 6: JavaScript Console

**Method Used:** Checking the browser console.

**Description:** By opening the browser’s developer tools and navigating to the Console tab, the flag was discovered. Some websites print debug information or other messages to the console, which can be a subtle place to hide a flag.

**Flag:** `QURMTHtKU19DT05TT0xFX0c3ODk0NDE5ODE2fQ==`

### Flag 7: Descriptive Text

**Method Used:** Examination of descriptive texts and metadata.

**Description:** This flag was found within the descriptive text or metadata associated with the domain. By examining the content on the main page and meta tags in the HTML source, the flag was located.

**Flag:** `QkN7REVTQ1JJUFRJVkUtRE9NQUlOLVRYVH0=`

## Conclusion

Each of these flags was found using a combination of basic web reconnaissance techniques. The process involved methodically inspecting various elements of the website, such as CSS files, JavaScript files, HTML comments, sitemaps, and the `robots.txt` file. These methods collectively ensured a thorough passive recognition test, helping to uncover hidden information.

Further steps will involve deeper reconnaissance to locate the remaining flags.
