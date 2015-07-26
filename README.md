# html-wireframes
HTML Wireframes Starter Kit

This is a kit I built using HTML, CSS, and a touch of jQuery for web design and development teams that want to build in-browser wireframes or prototypes but may have team members who have gaps in their HTML and CSS knowledge. This kit does not use Sass, Less, or other preprocessors because, like I noted above, this tool is meant for everyone to understand.

There is a simple, percentage-based grid system included that only goes as small as 25-percent but allows for nesting. There is also a generic global.css file, but I encourage you to put your themed or extended CSS in other files and link to them in the <head>.

Creating templates utilizes the jQuery .load() method to include HTML partials where needed. This is only for quick-and-dirty prototyping and should not be used on a production-level site. Please use a true templating engine or language, such as Jekyll, PHP, and the like.
