---
title: Hello World
hide: true
---
Welcome to [Hexo](https://hexo.io/)! This is your very first post. Check [documentation](https://hexo.io/docs/) for more info. If you get any problems when using Hexo, you can find the answer in [troubleshooting](https://hexo.io/docs/troubleshooting.html) or you can ask me on [GitHub](https://github.com/hexojs/hexo/issues).

## Quick Start

### Create a new post

``` bash
$ hexo new "My New Post"
```

More info: [Writing](https://hexo.io/docs/writing.html)

### Run server

``` bash
$ hexo server
```

More info: [Server](https://hexo.io/docs/server.html)

### Generate static files

``` bash
$ hexo generate
```

More info: [Generating](https://hexo.io/docs/generating.html)

### Deploy to remote sites

``` bash
$ hexo deploy
```

More info: [Deployment](https://hexo.io/docs/one-command-deployment.html)



``` cpp

class MyClass {
public:
    MyClass() {}
    ~MyClass() {}

    virtual const bool Initialize() = 0;

    MyClass(const MyClass& lhs) = delete;
    MyClass(MyClass&& lhs) = delete;

    
};


```


{% note [class] [no-icon] [summary] %}
Any content (support inline tags too).
{% endnote %}

- [class] : Optional parameter. Supported values: default | primary | success | info | warning | danger.
- [no-icon] : Optional parameter. Disable icon in note.
- [summary] : Optional parameter. Optional summary of the note.


## Note Samples

{% note %}
Default Notes
{% endnote %}

{% note default %}
Default Notes with default
{% endnote %}


[NOTE演示](https://blog.17lai.site/posts/cf0f47fd/#tag-note)


## Button Samples

[Button演示](https://blog.17lai.site/posts/cf0f47fd/#tag-button)