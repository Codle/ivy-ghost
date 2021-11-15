# Ivy-Ghost

A clean ghost theme.

Live Demo: [https://codle.net](https://codle.net)

## Comment

Ivy-Ghost used [utteranc.es](https://utteranc.es/) as blog comment system. You can add and modify
following codes to display it on blog.

```javascript
<script type="text/javascript">
    (function() {
        // 匿名函数，防止污染全局变量
        var utterances = document.createElement('script');
        utterances.type = 'text/javascript';
        utterances.async = true;
        utterances.setAttribute('issue-term','pathname')
        utterances.setAttribute('theme','github-light')
        utterances.setAttribute('repo','[YOUR REPO ADDRESS]')
        utterances.crossorigin = 'anonymous';
        utterances.src = 'https://utteranc.es/client.js';
        // content 是要插入评论的地方
        document.getElementById('comment').appendChild(utterances);
    })();
</script>
```
