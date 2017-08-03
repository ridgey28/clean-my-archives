# Clean My Archives

An easy-to-use shortcode for displaying post archives on your site.

The Clean My Archives plugin was developed because so many archives plugins were overly complicated.  I wanted something extremely simple to use that simply got the job done on my own [site's archives](http://justintadlock.com/archives).

Therefore, I created a simple `[clean-my-archives]` shortcode that you can place on any page (or any shortcode-ready area) and list your post archives by month and year.

This plugin also integrates with WordPress caching plugins.  So, long lists of archives can be cached for later use and loaded quickly.  If you have many years of blog posts, I highly recommend some sort of persistent caching or paginating your archives (see FAQ).

## Usage

Add the `[clean-my-archives]` shortcode to a shortcode-ready area, such as the page editor. That's it.  You have nothing more to do.

However, there are some parameters you can use.  The following are examples of these parameters in use.

#### Limit the number of posts with the `limit` parameter:

    [clean-my-archives limit="100"]

#### Reverse the order with the `order` parameter (default is `DESC`):

    [clean-my-archives order="ASC"]

    [clean-my-archives order="DESC"]

#### Use the `year` parameter to limit to a year:

    [clean-my-archives year="2013"]

#### Use the `month` parameter to limit by month:

    [clean-my-archives month="12"]

#### Load specific post types with the `post_type` parameter

    [clean-my-archives post_type="post"]

    [clean-my-archives post_type="post, page"]

#### Pagination (via the post/page editor):

    [clean-my-archives year="2013"]
    <!-- nextpage -->
    [clean-my-archives year="2012"]
    <!-- nextpage -->
    [clean-my-archives year="2011"]

#### Added bootstrap ul styling (default false - display ordinary ul)

[clean-my-archives bootstrap=true]

#### To remove comment count (default true - show)

[clean-my-archives comment_count=false]

## Professional Support

If you need professional plugin support from me, the plugin author, you can access the support forums at [Theme Hybrid](http://themehybrid.com/support), which is a professional WordPress help/support site where I handle support for all my plugins and themes for a community of 60,000+ users (and growing).

## Copyright and License

This project is licensed under the [GNU GPL](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html), version 2 or later.

2008&thinsp;&ndash;&thinsp;2015 &copy; [Justin Tadlock](http://justintadlock.com).
