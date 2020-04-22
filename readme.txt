=== Copy Delete Posts ===
Contributors: CopyDeletePosts, copydelete
Tags: Copy posts, Copy pages, Duplicate posts, Duplicate pages, Clone posts, Clone pages, Delete posts, Delete pages, Duplicate post, Duplicator, copy post, copy page
Requires at least: 4.9
Tested up to: 5.4
Stable tag: 1.0.5
License: GPLv3
Requires PHP: 7.0

Duplicate posts and delete posts

== Description ==

Massively increase your WordPress productivity!

This plugin makes it easy to duplicate posts or copy pages - and delete them again!

And why is it important to duplicate posts? Some use cases:

- Duplicate posts to save you the work to enter again the same elements you repeatedly use (e.g. content, excerpt, featured image, etc.)
- Create a different version of a page or post quickly to modify them and compare side by side (for yourself, or your client or boss)
- Create one stellar set of templates and then re-use them for different projects or clients
- Give your product page a facelift but keep the old version if you want to switch back to it later
- Create a "holiday special" template and use it for the various holidays with some adjustments
- Make duplicates for pages used in page builders with their various settings

You can also load-test your server by duplicate posts by a factor of 1,000, and see how it behaves. The plugin also allows you to easily bulk delete posts again later!

**How to use it**

For all you visual people out there:

[youtube https://youtu.be/lX8UbDy62Do]

After installation you'll see a new copy post link which, on mouse-over, shows you a tooltip (see screenshot) which allows you to copy posts or copy pages with different options:

- Copy page or duplicate post instantly with one click
- Specify how often you want to duplicate pages or clone posts
- Choose to see more copy post options and define specifically what elements should be copied for this copy page or copy post operation

The new copy post option will be visible on:

- Your overview of pages and posts
- Edit screens (duplicate post or duplicate page on the respective edit post or page screens)
- Admin bar (at the top)
- Bulk-option to copy posts or copy pages on your list of pages and posts
- Gutenberg editor


You can remove copy post or copy pages button on any of these places from the plugin menu (Other options). Copy post function on the editor screen can help you quickly multiply post you are working on currently (and open it in the new tab immediately, too), so you can quickly create two variations, pick the one you like better, and later use the remove duplicates capabilities to trash duplicate that you didn’t like.

The copy posts plugin also offers an intuitive tool to define how the new posts or pages should be named (e.g. you can add a counter or the time/date of copying, etc.). So you can replicate post that will have a simple name, e.g. “ExamplePost - #4” - where number at the end will increase with each copy made; or you can replicate page with much more detailed copy-name such as: “ExamplePage created at 12:15:01 on Saturday, July 4th, 2020” - thanks to PHP date/time shortcodes being supported in custom date settings. Long name always help to spot the clone post more easily, either for further use or to remove duplicate.

Need to multiply page but also it’s child-page(s)? You can multiply pages all together with child-pages with all the copy settings that are applied to the parent page copy.

Other options available if you copy posts:

- Define where you should be navigated to after you copy posts or copy pages
- Define which users (roles) should be allowed to copy posts or copy pages
- Define which content types should be allowed to be copied, i.e. copy posts, copy pages, and copy custom post types
- Define to show a reference to the original copied page or post

Not only can you clone posts or clone pages quickly, but the plugin also offers a sophisticated tool to delete duplicate posts or delete pages.

As part of the cleanup process, you can define:

- Where the plugin should look for duplicates (i.e. delete posts, delete pages or delete custom posts)
- What should count as duplicate post or duplicate page (i.e. have the same title, slug, excerpt or word count)
- Which version you want to keep (oldest version - original or newest version - latest clone)

Even if you used this replicator tool to multiply pages or multiply posts in huge numbers, and you want to use this tool to trash duplicates every now and then, but leave out a few specific ones - you will be able to easily find duplicates when you use our duplicates scanner. After setting the parameters to find duplicates, you can use a search box to make sure you don’t delete duplicates you don’t want to, or remove duplicates to the last one (original included!). The duplicate checker tool can help you find duplicate and immediately visually check the clone page by clicking on the URL/slug link, in case you can’t tell by the name or the date clone page was created.

You can select to throttle the delete posts or delete pages process - which you may want to do when you’re on a slow server (note however: the plugin codes to delete posts or delete pages are already optimized, so usually there shouldn’t be an issue).

Copy Delete Posts is a cloner tool with a beautiful, modern design and features going beyond today’s post duplicator tools. Hopefully this will make it your favorite posts duplicator tool :)

The free copy posts plugin offers a lot of options - if you want even more options to copy posts or copy pages, then check out the premium copy posts plugin (currently under development) which will offer the following additional features:

- Use several configuration sets to copy posts or delete posts - useful when you want to quickly switch between the copy types, without having to go to the settings page.
- Export and import configuration sets - a handy tool for all of us who manage multiple sites and regularly replicate posts.
- Also include information from third party plugins when you copy posts (e.g. Yoast-information linked to pages/posts)
- Replicate pages across multisite will also prove to be a real time-saver for multisite administrators
- Automatically delete pages or posts - extremely useful for users that multiply posts or pages at high levels.
- Apply automatic redirects for deleted pages or posts

Just try it out! You'll love it :)


== Installation ==

= Admin Installer via search =
1. Visit the Add New plugin screen and search for "Copy & Delete Posts".
2. Click the "Install Now" button.
3. Activate the plugin.
4. The plugin should be shown below settings menu.

= Admin Installer via zip =
1. Visit the Add New plugin screen and click the "Upload Plugin" button.
2. Click the "Browse..." button and select the zip file of our plugin.
3. Click "Install Now" button.
4. Once uploading is done, activate Copy & Delete Posts.
5. The plugin should be shown below the settings menu.

== Frequently Asked Questions ==

= It seems the post deletion process doesn’t work. Why? =
If you are trying to delete posts and it doesn’t work try to append your wp-config.php with this line of code:
`define('ALTERNATE_WP_CRON', true);`
Does it work if you try to delete posts then? If not, please reach out to us in the support forum.

= When I copy post or copy page, why is title of the duplicate not the same?  =
If you copy posts or copy pages and want the new versions to have exactly the same title as the original post, make sure that prefix and suffix fields are blank in the “What name(s) should the copies have?” section of the Copy Delete Posts plugin area in the WordPress Dashboard.

= If I duplicate posts, how do I know what their original page was?  =
It can be a challenge to keep track of the original content if you duplicate posts.To prevent this we suggest to not leave the prefix and suffix fields empty (which define the name of the new posts) if you duplicate posts. However, even if you want to duplicate posts without any prefix or suffix, you can solve the issue as follows: Go to section “Other options” (on the duplicate post plugin configuration page), and at the bottom of this section you will find the option “Show reference to original item?”. Check this to ensure you can always keep track of original posts when duplicate pages or posts.

= Can I limit who can duplicate posts on my site? =
By default only Administrators can access the plugin and copy posts or copy pages. You can extend these permissions to other user roles by going to the section “Other options”, and then tick boxes next to WP user roles that you want to give permission to. Then also those roles can duplicate posts (or delete posts).

= I want to duplicate posts *only*, i.e. not duplicate pages. Is that possible? =
You can limit the features to duplicate posts only by going to the “Other options”-chapter and select where it says “Content types which can be copied” to only copy posts, copy pages, copy custom posts or all of these.

= How can I make bulk copies? =
If you want to duplicate posts en masse, select the copy posts option in the “Bulk actions” menu. You’ll see the lightbox asking you to specify your duplicate post options (i.e. which elements to copy).

= I can duplicate posts but it takes a long time. Why? =
If you duplicate posts and it takes long, then you may have selected to include attachments in the duplicate posts configurations. Go to the second chapter titled “Which elements should be copied?” and de-select the attachments option to exclude those when you duplicate posts.

= Can I bulk delete posts created by this plugin?  =
To easily clean posts or delete duplicate pages that were created by this plugin, go to ”Delete duplicate posts or pages” section, tab “Manual cleanup”. Select Posts, Pages and Custom Posts, and uncheck all other filters, then hit the Scan button. In the empty results list, you will see the message “Click here to show all copies…” - “here” link will show you all posts and pages created by our multiplier plugin.

= Which dupicate post features do you have which the other plugins don’t?  =
Other duplicate post plugins mostly only allow you to duplicate post to the same site. With the Copy Delete Posts plugin (premium version) you can duplicate post to other sites, e.g. duplicate post to a multisite, or duplicate post to a site on a different domain altogether (we’re currently working on this duplicate post functionality). Also, other duplicate post plugins don’t give you the granularity to define how to duplicate post, e.g. which elements specifically should appear on the cloned posts.

= Is this plugin GDPR friendly? =
Copy Delete Posts WordPress plugin doesn’t store any site visitor information so it is completely GDPR friendly.


== Screenshots ==
1. Plugin settings page
2. Copy preset settings
3. Customizable naming system
4. Global settings & permission system
5. Manual clean up
6. Quick-copy tooltip
7. Tooltip individual copy
8. Copy from Gutenberg editor

== Changelog ==

= 1.0.5 =
* Auto-refresh list of notifications
* Fixed issue when notification wasn't updated correctly
* Improvement search engine (Deletion Section)
* Scrollbar fix on plugin configuration page

= 1.0.4 =
* This is Hotfix
* Fixed issue during activation which shows "Header Error"

= 1.0.3 =
* Tested with new version of WordPress
* Fixed visual issue with deletion process

= 1.0.2 =
* Added new cool GIF inside the intro
* Added photos to the screenshots library
* Removed unnecessary stuff in code

= 1.0.1 =
* Improved deletion process above 800 posts
* Fixed sorting issues
* Fixed specified copies options (via tooltip)
* Fixed tooltip (flashing) issues on smaller screens

= 1.0.0 =
* Initial release

== Upgrade Notice ==
= 1.0.0 =
* Initial release
