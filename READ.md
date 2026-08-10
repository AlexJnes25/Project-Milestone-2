Personal Portfolio

This project is a three-page HTML portfolio website created for my web development course.

Pages
Home
Projects
About
I tested the Home, Projects, and About pages with WAVE. All three pages passed with zero accessibility errors, zero contrast errors, and zero alerts.
I added proper labels, a fieldset and legend, required fields, and accessible error descriptions to the contact form.

Missing or uninformative page title
WAVE initially reported that the page title was missing or not informative. This affected the <title> element. Page titles matter because screen-reader users and people with multiple browser tabs open need a clear way to identify each page. I fixed this by adding descriptive titles such as <title>Alex | Portfolio</title>.
Missing or invalid page language
WAVE reported that the page language was missing or invalid. This affected the <html> element. The language setting is important because screen readers use it to pronounce words correctly. I fixed this by using <html lang="en"> on the pages.
Low color contrast
WAVE reported a contrast problem between text and its background. Low contrast can make content difficult to read for users with low vision or color-vision differences. I used darker text and teal colors with white or light backgrounds and retested the site until WAVE showed no contrast errors.
