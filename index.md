---
header: Freelance content writer
layout: main
---

## Here are the key services I provide


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

I’m excited to embark on this journey and collaborate with individuals and businesses alike. Whether you need compelling blog posts, captivating website content, or engaging social media material, I’m here to bring your ideas to life through the power of the written word. Let’s work together to create content that speaks to your audience, evokes emotion, and achieves your desired outcomes. I can’t wait to get started!


____



## A little bit about me

![Tatiana](./assets/photo.jpg)
From childhood hobby to professional career

Hi there,

I am __Tatiana,__ a generalist content writer based in Sydney, Australia.

Before my freelance content writing, I was working in the IT area, as an HTML developer and then UX/UI Designer. This background helps me to present information and create texts that __resonate with specific target audiences.__

Besides writing, I have a passion for dance, the magic of essential oils, and travel. I've explored 27 countries, and 17 of them with my daughter who's just 5 years old. I've gained loads of knowledge in these areas. You can read my article on traveling with a young child in the portfolio section.

____


## Some examples of my work
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