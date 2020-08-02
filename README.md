# Urban Octo Telegram website 
## Code Refactor Starter Code
### HTML file changes
    head changes
        Updated title to reflect company name.

    Body changes
    header section changes
        Removed Class and used element <header> instead.
        Removed extra </div> 

    hero section changes
        removed class from <div>
        added <img> with link to the image in teh assets folder
        added alt tag to <img>
        added hero class to <img>

    content section changes
        added <article> instead of just using <div> 
        changed class to ID for search-engineoptimization, online-reputation-management, and social-media-marketing 
        Added alt tags for each image

    benefits section changes
        removed class for "benefit-lead, benefit-brand, and benefit-cost

    footer section changes
        removed class and used element <footer> instead

### CSS file Changes
    changed .header to header
    changed height on .her froom 800px to 100%
    removed background-image url
    changed .content to article
    removed .benefit-lead, .benefit-brand, and .benefit-cost replaced with .benefits div
    removed .benefit-lead h3, .benefit-brand h3, and .benefit-cost h3 replaced with .benefits h3
    removed .benefit-lead img, .benefit-brand img, and .benefit-cost img replaced with .benefits img
    removed .search-engine-optimization img, .online-reputation-management img, and social-media-marketing img replaced with article img
    removed .search-engine-optimization h2, .online-reputation-management h2, and social-media-marketing h2 replaced with article h2
    changed .footer to footer

