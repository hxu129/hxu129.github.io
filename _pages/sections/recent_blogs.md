# 📝 Recent Blog Posts

<div class="recent-blogs">
  <div class="blog-container">
    {% for post in site.data.blog_posts.posts limit:3 %}
      <div class="blog-card">
        <h3 class="blog-title">
          <a href="{{ post.url }}" target="_blank">{{ post.title }}</a>
        </h3>
        <div class="blog-meta">{{ post.date | date: "%B %d, %Y" }}</div>
        <div class="blog-summary">{{ post.summary }}</div>
        <a href="{{ post.url }}" class="blog-read-more" target="_blank">Read more</a>
      </div>
    {% endfor %}
  </div>
  
  <div class="blog-footer">
    <a href="https://hxu129.github.io/blogs" class="blog-view-all" target="_blank">View all posts →</a>
  </div>
</div> 