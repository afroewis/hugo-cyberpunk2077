# Cyberpunk 2077 theme for hugo

Based on the Cyberpunk 2077 CSS styles from: https://github.com/gwannon/Cyberpunk-2077-theme-css

## Features

### Cyberpunk images
Use the `img` shortcode to display a cyberpunk frame around the image.

Example: 

`{{< img "/foo.png" "Image's alternative text" >}}`

### Cyberpunk videos
Use the `youtube` shortcode to display a cyberpunk frame around a youtube video.

Example:

`{{< youtube u5dstCrR9gM >}}`

### Social icons

You can configure social icons in your site's `config.toml`.

```toml
# Social icons
[[params.social]]
name = "Github"
icon = "fa fa-github"
url = "https://github.com/<your-username>"

[[params.social]]
name = "Email"
icon = "fa fa-envelope"
cmd = "mailto:<your-email>"

[[params.social]]
name = "LinkedIn"
icon = "fa fa-linkedin"
cmd = "https://www.linkedin.com/in/<your-id>"
```

### Navigation

You can configure the navigation buttons in your site's `config.toml`.

```toml
# Navigation
[[menu.main]]
name = "Home"
url = "/"
weight = 1

[[menu.main]]
name = "All Posts"
url = "/posts"
weight = 3

[[menu.main]]
name = "About"
url = "/about"
weight = 2
```

### Title, subtitle, avatar, footer text

Example:
```toml

[params]
	pagetitle = "Rogue Amendiares"
	subtitle = "Night City's top fixer"
	footertext = "Destroy Arasaka"
	avatar = "/foo.jpg"
```