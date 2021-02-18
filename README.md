# Test Spike Results

site    : https://upbeat-edison-337641.netlify.app
cms     : https://upbeat-edison-337641.netlify.app/admin

1. Updated existing content and clicked publish 
    - no developers needed
    - build times are radically quicker (will save money and time)
2. Updated new content for existing template and clicked publish 
    - no developers needed
    - tested out the preview mode (should be available for gatsby also)
3. Create new component/layout for content
    - Hugo GO templating is a bit complicated - reminds me of picking up Ember
4. Local development environment setup
    - Successful but had some sporadic build issues (sass broken on example site maybe)
    - Site and CMS code are local but content is pulled from and committed to the master branch
5. PR creates a deploy preview of the site including the CMS
    - Again the content is pulled from and committed to the master branch
6. Developers experience
    - Very snappy, feels like instant reload of content for the small test site
    - Gotta fix the dev environment committing to master
7. Build from multiple sources
    - Requires we roll our own solution, I would hate to write anything in JS but not sure how to include GO commands/modules

Calling it quits - sourced data is a blocker but I may come back if there are no other options
