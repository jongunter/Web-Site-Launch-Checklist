# Web Site Launch Checklist
A checklist I use when publishing marketing sites, mainly with WordPress, but often with other systems like DocPad.

Want to add/edit something? Feel free to submit a pull request!

## Deisgn Checks
1. Menus still look good when you add/remove links (your client might do this!)
2. *If WordPress or other CMS:* Your widget areas still look good when widgets are added/removed (again, the client might do this!)
3. Design works and looks good on phones, tablets, laptops and large screens (TVs)
4. Site has favicon and touch icons for iOS devices
5. Print stylesheet looks good (or page just looks good when printed)
6. Design looks good on older version of IE
7. Design looks good on Chrome, Firefox, IE, Opera, Safari
8. Lightbox is installed for photo galleries

## Accessibility
1. Site is readable for colorblind users
2. Images have `alt` attribute
3. ARIA enhancements added (see [this article on MDN](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA))

## Site Behavior
1. External links open in a new window
2. `www` domain 301 redirects to `non-www` domain (no duplicate content)
3. Contact form works (test it twice!)

## Technical Stuff
1. HTML Validates
2. CSS Validates
3. No JavaScript errors in console
4. No Google-hosted assets (Jquery/Angular/fonts): won't work in countries where Google is blocked.
5. Code is tidy and properly documented

## Content
1. Add humans.txt file
2. Add robots.txt file
3. Site has Error 404/403 pages
4. Add any credits (for images or resources like Glyphicons)
5. Site has privacy policy/statement
6. Site map web page created
7. Search feature works
8. Spell check pages
9. Links to social media pages

## Performance Tweaks
1. Compile LESS/SASS into CSS, and minify
2. Compile CoffeScript into JS, and minify
3. Optimize images for the web
4. Caching is turned on
5. CDN is set up (if using a CDN)

## Security
1. Site has HTTPS
2. Backup plugin/service is running

## SEO/Analytics Checklist
1. Old URLs 300 redirect to the new URLs
2. Google/Bing Webmaster tools set up
3. Google Analytics installed
4. Social media sharing buttons
5. *If WordPress:* WordPress SEO plugin installed
6. Google site map
7. Submit site to Google and Bing

## If using WordPress
1. Unnessary themes are removed
2. Unnessary plugins are removed (goodbye, Dolly!)
3. Install WordFence (set up scans, password rules, and brute force protection)
4. Database tables have a prefix other than the standard `wp_`
5. There is no default `admin` username
6. Update everything
7. Setup multi-factor authentication
8. Auto-update enabled
9. Placeholder pages/posts and comments are removed
10. Placeholder images removed from media library
11. If custom theme, run ThemeChecker plugin
12. Permissions on server are set up propertly (can install/update plugins)

## Client Sign-Off
1. Pass on hosting credentials
2. Pass on CMS credentials (if there is a CMS)
3. Give access to Google/Bing Webmaster tools
4. Give access to Google Analytics
5. Remind them to change their WordPress password every 3 months