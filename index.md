<!-- This is just random text, testing -->
# Hi, I'm Marty
## Let's learn together!

# My Projects
Here is a list of projects I am working on:

<ul>
    <li>
        <a href="https://cyber1boss.github.io/GitHub-Site-Testing/">GitHub Website</a>
    </li>
    <li>
    <a href="https://">Project B Filler</a>
    </li>
</ul>
# Get in Touch
<ul>
    <li>
    <a href="https://x.com/{{ site.twitter_username }}">Twitter/X</a>
    </li>
    <li>
    <a href="https://github.com/{{ site.github_username }}">GitHub</a>
    </li>
</ul>


# My Interests
I am interested in helping people connect with technology

# My Blog
I am really excited to blog my journey on GitHub.com
<ul>
{% for post in site.posts %}
    <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
    {% endfor %}
</ul>
# Get in Touch
<ul>
    <li>
    <a href="https://x.com/{{ site.twitter_username }}">Twitter/X</a>
    </li>
    <li>
    <a href="https://github.com/{{ site.github_username }}">GitHub</a>
    </li>
</ul>