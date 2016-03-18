## How to Blog with Tappsi

1. Clone the repository

    git@github.com:tappsi/tappsi.github.io.git

2. Switch to ``source` branch.

3. [Create a new post](http://octopress.org/docs/blogging/)

    rake new_post["title"]

4. Generate & Preview

    rake generate   # Generates posts and pages into the public directory
    rake watch      # Watches source/ and sass/ for changes and regenerates
    rake preview    # Watches, and mounts a webserver at http://localhost:4000

5. Deploy

    rake deploy

6. Don't forget to commit the source for your blog

    git add .
    git commit -m 'your message'
    git push origin source