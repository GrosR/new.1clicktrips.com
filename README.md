# new.1clicktrips.com
New WebSite for 1ClickTrips
This repository is made to explain the website structure and thoughts behind the content strcuture and usage as well as to track all open issues and changes to the website built on the Avada Theme.

Items tracked are changes to the Sitestructure as well as to posts and content that is connected to other content or connected to the structure of the site. 

Examples for such content are especially blog posts that are used as content inside the core pages that a user can reach from 
the main menue. 

In the content areas of these sites, e.g. in boxes or flipboxes, we use shortcodes to display Blog-posts in these content boxes as we try to manage the whole blog as far as possible through blog posts organized by categories.

A detailed description on shortcodes of the Avada theme can be found here: 
https://theme-fusion.com/knowledgebase/avada-shortcode-list/

The shortcode used to render a blog post into a content item of a page allows to define looks like this: 
[blog number_posts="1" offset="0" cat_slug="cfeatures" exclude_cats="" title="no" title_link="" thumbnail="yes" excerpt="yes" excerpt_length="35" strip_html="no" meta_all="no" meta_author="no" meta_categories="no" meta_comments="no" meta_date="no" meta_link="no" meta_tags="no" paging="no" scrolling="pagination"  blog_grid_columns="1" blog_grid_column_spacing="" layout="grid" class="" id=""][/blog]

Only the following parameters are varied to access the right post and it is important to understand what the following parameters mean and how they are used:

- blog number_posts is the post count you want to display, '1' means: display not more than one post
- offset is the most important filter, the offset counter starts at '0' which is the first post created in the category filtered by cat_slug. To identify the correct offset, you must filter the posts by the category, sort the posts ascending by date and start to manually count the posts. The one you want has the offset '# counted - 1'
- cat_Slug is the category filter. All category names start with 'c' to avoid naming conflicts with pages or posts

Special categories have been structured according to the following pattern. Be careful when using these categories:
- cfeatures is attached to posts that are meant to be used on the 'travel booking' page in the tiles that describe our service features
- cintegrations is attached to posts that are meant to be used on the 'integrations' page in the tiles that describe our integration options
- canalytics is attached to posts that are meant to be used on the 'analytics' page in the tiles that describe our analytics features

There are 3 other categories which shall be explained here:
- ctargetgroup is attached to posts that describe the profiles and needs of our typical target groups. On the 'home' page, we use a slideshow to show the target group posts
- cPublications is used for posts that contain more profound materials like whitepapers or studies. These posts are displayed on the 'News' page in the upper right content section
- cPress is meant for material that had press coverage. These posts are displayed on the 'public relations' page

All other categories are used to structure the blog section. 


