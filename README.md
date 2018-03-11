# Customizer: Static Vs. Content Front Page

## Description

WordPress allows you to display either a static page or a feed of the latest posts on the front page of your website. Using the Theme Customizer, you can first preview how pages or posts will appear, then save and publish the settings.

## Objectives

At the end of this lesson, you will be able to:

*   Distinguish between a static and dynamic front page
*   Apply options for the front page display
*   Practice previewing front page options
*   Choose to save and publish front page options

##  Prerequisite Skills

You will be better equipped to work through this lesson if you have experience in and familiarity with:

*   The [WordPress Dashboard](https://make.wordpress.org/training/handbook/user-lessons/overview-of-the-dashboard/)
*   Able to [install a theme](https://make.wordpress.org/training/handbook/user-lessons/choosing-and-installing-a-theme/)
*   Understand how to use [pages vs. posts](https://make.wordpress.org/training/handbook/user-lessons/pages-vs-posts/)
*   Understand basic [WordPress Settings](https://make.wordpress.org/training/handbook/user-lessons/settings/)
*   Optionally, understand using the [Theme Customizer](https://make.wordpress.org/training/handbook/user-lessons/theme-customizer/)

## Assets

*   Working WordPress website with a theme along with content in pages and posts
*   [Twenty Sixteen](https://wordpress.org/themes/twentysixteen/) theme
*   [Theme Unit Test Data](https://wpcom-themes.svn.automattic.com/demo/theme-unit-test-data.xml)

## Screening Questions

*   Do you understand that WordPress uses both pages and posts?
*   Are you able to navigate the WordPress Dashboard?
*   Are you ready to customize some features of a WordPress theme?

## Teacher Notes

*   **Time Estimate:** 30 minutes
*   Students need to use a sandbox site where they can safely make changes.
*   Or, if using a production site, they need to have backup and restore capability, and they need to understand that they will be modifying the home page of their website.
*   Describe how web designers and developers toggle between back-end settings and front-end viewing, while the Customizer provides side-by-side panels for both.
*   Explain how the Customizer provides a visual preview of the front page setting, while the same task can be handled in the Reading Settings of the Dashboard.
*   This lesson is very similar to [Setting a Static Page as Your Homepage](https://make.wordpress.org/training/handbook/user-lessons/setting-a-static-page-as-your-homepage/), but uses the Customizer rather than the Settings section.

## Hands-on Walkthrough

Websites may employ different modes for a front page (aka home page). Originally on the web, most sites had a simple static page showing the same information over time, unless the content for that page was edited. Blogs, on the other hand, have a feed of the latest posts that changes over time. This dynamic mode makes it easy to keep the front page of a website updated with the latest news and information. WordPress started as a blogging system, and the default setup is still set to show the latests posts on the front page. However, WordPress offers a simple means to toggle between the static and dynamic mode, and WordPress themes can offer more options to mix content types on the front page.

### Determine your Current Front Page Mode

What mode is your site currently using—a static page or dynamic posts? View your website on the front end as a visitor sees it and decide which setting you think is currently used. Different themes do display content in various ways. If you are using the Twenty Sixteen theme, you will see either a single top heading for the content or multiple top headings down through the content. If you see a top heading of "Hello World," that's the default post in a dynamic mode. ![Default Front Page with Hello World post](https://make.wordpress.org/training/files/2016/10/DefaultFrontPageHelloWorld.png) Before you adjust the front page mode of your website, you should be sure to have both a static page to use as the front page, and a page to use for your blog, along with multiple posts and (optionally) some categories with your posts. Any content is fine to use; you only need to be able to easily recognize the two types of content that you'll preview in this lesson.

### Determine your Static Page

If you are using the theme unit test data, a page has already been designated for this purpose and is titled "Front Page." If you are using another theme, you may have a similar page, such as one titled "Home." Or, you can create a new page and give it any title, such as "Home" or "Front Page." ![Unit Test Front Page](https://make.wordpress.org/training/files/2016/10/UnitTestFrontPage.png)

### Determine your Posts Page

You need to designate a Posts page for displaying a feed of your posts. That may seem confusing to have a page for your posts. If you set your front page to a static page, then this will provide a default alternate location for displaying your posts. If you set your front page to a dynamic posts mode, you aren't required to set a Posts page, but it's a good practice to have one; and you do want to have it for this lesson. When using the theme unit test data, a page called "Blog" is provided. If you using another theme, you can create a page titled "Blog" to use as your Posts page. ![Unit Test Blog Page](https://make.wordpress.org/training/files/2016/10/UnitTestBlogPage.png)

### Use the Customizer to Preview Static and Dynamic Modes

#### What is the Customizer?

Typically, designers and developers toggle between back-end coding and front-end viewing in their work. The WordPress Theme Customizer allows you to change many aspects of the look and feel of your WordPress site, without having to toggle between backend and front end, nor having to modify the code of theme files. You can use the Customizer to preview and modify many of your site’s Appearance settings with ease and safety. [tip]Themes may either use or not use certain features of the Customizer, as well as add new features depending upon the theme developer. If your theme does support the Customizer settings for this lesson, apply the standard Twenty Sixteen theme for practice. Afterwards, you can switch back to your original theme.[/tip]

#### Launch the Theme Customizer

There are two ways to launch the Customizer, from the front end or back end of the WordPress site. On the front end of the site, when you are logged in, you'll see the Customize icon and link in the Admin bar, which is the toolbar at the top of the website. ![WordPress Admin Bar Customize](https://make.wordpress.org/training/files/2016/10/WordPressAdminBarCustomize.png) When you launch the Customizer on the front end, you'll be able to see previews of how customization will affect whichever particular page or post is being viewed. After you launch the Customizer, you can navigate the website, just as on the front end of the website, in order to preview changes in other contexts. To launch the Customizer in the WordPress Dashboard, use Appearance > Customize. You may also see a big blue Customize Your Site button in the Welcome to WordPress section, if that screen option is turned on. When you launch the Customizer from the Dashboard, the front page of the website is displayed in the preview pane by default. ![WordPress Customizer Static Front Page](https://make.wordpress.org/training/files/2016/10/WordPressCustomizerStaticFrontPage.png)

#### Customize the Static Front Page setting

Select **Static Front Page** from the Customizer menu. If your theme does not support the Customizer's Static Front Page setting, you may see a notification of that in the menu or in the setting. There are three settings for the Static Front Page section:

*   **Front page displays**: designates either a dynamic or a static mode:
    *   Your latest posts
    *   A static page
*   **Front page**: designates a page to use for the static mode
*   **Posts page**: designates a page to use for displaying the latest posts, if not in dynamic mode

By default, WordPress uses "Your latest posts" as the setting for the **Front page display**, and if you use that setting, there are no other settings to choose. When you change the Front Page display setting to "A static page," you'll see the additional settings for **Font page** and **Posts page**. ![WordPress Customizer Front Page Extra Settings](https://make.wordpress.org/training/files/2016/10/WordPressCustomizerFrontPageExtraSettings.png) You can select any page in your site as the Front page, but the best practice is to have a page named "Front page" or "Home," so that it's easy to remember the critical purpose of that page. Select the page that you want to use for your **Front page** setting. Notice that the customizer automatically displays that page in the right-hand preview pane. When you use a static front page, you should then set a **Posts page** as the alternate location for your blog posts. Select the page that you want to use for your **Posts page** setting.

#### Save & Publish your Customizer Settings

After previewing your Static Front Page settings and are satisfied with the results, you should Save & Publish your Customizer settings by clicking the button at the top of the menu. When you see the button indicate "Saved," you can exit the Customizer by clicking the X in the upper left corner. ![WordPress Customizer Save & Publish](https://make.wordpress.org/training/files/2016/10/WordPressCustomizerSavePublish.png)

## Exercises

_No additional exercises are required, though students may practice toggling between static and dynamic modes for the front page._

## Quiz

**What is the default setting for a WordPress front page?**

1.  Hello World
2.  Dynamic feed of your latest posts
3.  Static page
4.  Home page

**Answer:** 2\. Dynamic feed of your latest posts **Why use the Customizer to set a front page?**

1.  It's required by WordPress.
2.  Themes do not support front page settings.
3.  Dynamic blogs are better than static pages.
4.  It's easy to preview the results of the Static Front Page setting.

**Answer:** 4\. It's easy to preview the results of the Static Front Page setting. **Why should you set a Posts page?**

1.  It's the alternate blog location, when a static page is set.
2.  Otherwise you cannot display posts.
3.  Posts should always appear on the front page.
4.  Because posts and pages are different

**Answer:** 1\. It's the alternate blog location, when a static page is set.

## Additional Resources

_None_
