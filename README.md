# Smart-Banners
iOS &amp; Android

The "meta-data" is the header meta that is placed within the website.

Notice that the "css & js" files are hosted on another server.

The following line ensures that the smart banner is not displayed within the mobile app (iOS & Android). Add a user-agent with the title "OD Applications" within your iOS & Android applications.

meta name="smartbanner:exclude-user-agent-regex" content="^.*OD Applications$"
