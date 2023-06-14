---
header: Freelance content writer
layout: main
---
![Tatiana](./assets/photo.jpg)
From childhood hobby to professional career

## About me
Hi, I’m __Tatiana__, your __content writer__ with User Experience Design background.
I learned how to write and read when I was 5 years old; since then, it’s been my biggest passion. From creating stories to maintaining my personal journal, words have been my way of expressing myself and sharing my thoughts with others.
Recently, I’ve decided to combine my skills and passion with generating an income and started my career at content writing. 
I approach every project with enthusiasm and a commitment to deliver __high-quality work__. 

As a UX designer, I understand the importance of tailoring communication to different audiences. I leverage my knowledge of user analysis to create texts that resonate with specific __target audiences__.

I complement my innate talent with continuous learning, diving into books by writing experts and taking courses like the Location Rebel Academy by Sean Ogle.

Besides writing, I have a passion for dance, essential oils, and travel. I've explored 17 countries with my daughter who's just 5 years old. I've gained loads of knowledge in these areas too. You can read my article on traveling with a young child in the Portfolio section below, but I can write texts for any area. 

I’m excited to embark on this journey and collaborate with __individuals__ and __businesses__ alike. Whether you need compelling blog posts, captivating website content, or engaging social media material, I’m here to bring your ideas to life through the power of the written word. Let’s work together to create content that speaks to your audience, evokes emotion, and achieves your desired outcomes. I can’t wait to get started!



## Services
I've got you covered with a range of essential services. Here are the key services I provide:


1. __Blog Post Creation__:
    - Engaging and informative blog posts that your audience will love.
    - Thorough research on the topic to make sure your content is accurate and on point.
    - Optimizing your posts for search engines.


2. __Website Content Development__:
    - Compelling website content that showcases your brand's personality and values.
    - Clear and concise writing that conveys your message effectively.
    - Plus, I'll make sure your website is user-friendly and keeps people hooked.


3. __Copywriting__:
    - Crafting persuasive copy that drives conversions and gets results.
    - Attention to grammar, style, and tone to maintain a professional image.


These services lay a solid foundation for your content needs, helping you establish an engaging online presence and connect with your audience. As a beginner content writer, my goal is to deliver top-notch work and ensure that the writing reflects your unique brand voice.

## Portfolio
For the samples of my work please refer to the following posts:
{% for post in site.posts %}

### {{post.title}}

{{post.excerpt}}

[read more]({{post.url}})

{%- if forloop.last == false %}

---

{% endif -%}
{% endfor %}

## Contact me
Ready to bring your content to life?

Email me at [{{ site.author.email }}](mailto:{{ site.author.email }})