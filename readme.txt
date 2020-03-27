=== Copy Delete Posts ===
Contributors: CopyDeletePosts, copydelete
Tags: Copy posts, Delete posts, Copy pages, Delete pages, Duplicate pages
Requires at least: 4.9
Tested up to: 5.3.2
Stable tag: 1.0.0
License: GPLv3
Requires PHP: 7.0

Copy and delete posts quickly & easily

== Description ==

This plugin makes it easy to copy and delete posts or pages.

After installation you'll see a new copy link which, on mouse-over, shows you a tooltip (see screenshot) which allows you to:

- Copy the page or post instantly with one click
- Specify how often you want to duplicate the page or post
- Choose to see more options and define specifically what elements should be copied for this page or post

The new copy post option will be visible on:

- Your overview of pages and posts
- Edit screens (post or pages)
- Admin bar (at the top)
- Bulk-option on your list of pages and posts
- Gutenberg editor

The plugin also offers an intuitive tool to define how the new posts or pages should be named (e.g. you can add a counter, or the date of copying etc.).

Other options available if you copy or delete posts:

- Define where you should be navigated to after you copy a page or post
- Define which users (roles) should be allowed to copy posts or pages
- Define which content types should be allowed to be copied, i.e. posts, pages, and custom post types
- Define to show a reference to the original copied page or post

Not only can you copy a page or post quickly, but the plugin also offers a sophisticated tool to delete duplicate post or pages.

As part of that process, you can define:

- Where the plugin should look for duplicates (posts, pages or custom posts)
- What should count as duplicate (i.e. have same title, slug, excerpt or word count)
- Which version you want to keep (oldest version or newest version)

You can select to throttle the deletion of posts or pages (in case you're on a slow server).

The free plugin offers a lot of options - if you want even more, then check out the premium plugin (currently under development) which will offer the following additional features:

- Use several configuration sets & import / export them
- Also include information from third party plugins when copying (e.g. Yoast-information linked to pages/posts)
- Copy pages/posts to other sites in a multisite set-up
- Automatically delete pages/posts
- Apply automatic redirects for deleted pages/posts

Just try it out! You'll love it :)


== Installation ==

= Admin Installer via search =
1. Visit the Add New plugin screen and search for "Copy & Delete Posts".
2. Click the "Install Now" button.
3. Activate the plugin.
4. The plugin should be shown below settings menu.

= Admin Installer via zip =
1. Visit the Add New plugin screen and click the "Upload Plugin" button.
2. Click the "Browse..." button and select zip file of our plugin.
3. Click "Install Now" button.
4. Once uploading is done, activate Copy & Delete Posts.
5. The plugin should be shown below settings menu.

== Frequently Asked Questions ==
= Why doesn't the deletion process work correctly? =
If the deletion process seems to not work please append your wp-config.php with this line of code:
`define('ALTERNATE_WP_CRON', true);`
It should fix the issue :)


== Screenshots ==
1. This is the description for the first screenshot

== Changelog ==

= 1.0.0 =
* Initial release

== Upgrade Notice ==
= 1.0.0 =
* Initial release
