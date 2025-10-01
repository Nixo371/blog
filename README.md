megascript.sh and image_script.sh slightly modified from NetworkChuck's video: https://www.youtube.com/watch?v=dnE7c0ELEH8

You have to change `sourcePath`, `destinationPath`, and `myrepo` in the megascript.sh to your own directories

You have to change `posts_dir`, `attachments_dir`, and `static_images_dir` in the image_script.sh to your own directories as well

And you have to set up the appropriate webhook in the git repository to wherever you're hosting the blog. I had to set mine up manually and make my own custom webhook handler on my server to automatically pull the changes on my server.
