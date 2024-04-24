<template>
    <div>
        <h1>Hi.</h1>
        <p style="font-weight: 500; font-size: 2.2em">My name is Liu Ziting.</p>
        <p>
            作为一名有着丰富创造力的前端开发工程师，我对于探索互联网的未知角落充满热情。近三年来，我热衷于AI领域，享受将想法通过代码实现，并成功部署上线的过程。
        </p>
        <p>我熟悉使用VUE, JavaScript, Python以及一点React和NextJS，并且对Astro和Tailwindcss框架情有独钟。</p>
        <p>
            在过去的两年里，我开发了一系列与AI相关的网站项目。例如，一个汇集AI产品的平台：<a
                href="https://www.smartai.wtf/"
                target="_blank"
                >SmartAI</a
            >，一个展现sora视频创意的网站：<a href="https://www.soradesign.top/" target="_blank">SoraDesign</a
            >，以及一个利用Gemini开发的，能够通过上传照片来解析宠物想法的有趣工具：<a
                href="https://iknowwhatyourcatisthinking.netlify.app/"
                target="_blank"
                >我知道你的宠物在想什么</a
            >。
        </p>
        <p>
            此外，我还会在<a href="https://juejin.cn/user/870468937854734/posts" target="_blank">Juejin</a
            >分享我对技术的见解和写作。
        </p>
        <p>
            我的更多项目可以在<a href="https://github.com/liu-ziting" target="_blank">GitHub</a
            >上找到。我喜欢在业余时间写作教程、分享技术文章或参与开源项目的开发。欢迎Follow我，了解我的最新动态。
        </p>
        <p>除了编程，我还对骑行和滑板充满热情。</p>
    </div>
</template>

<script>
export default {
    name: 'App',
    components: {}
}
</script>

<style>
body {
    font-family: 'Rubik', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans',
        'Helvetica Neue', sans-serif;
    font-size: calc(10px + 0.33vw);
    -webkit-font-smoothing: antialiased;
    padding: 5vh 10vw;
    color: #121314;
}
h1 {
    font-size: 4.5em;
    font-weight: 500;
    margin-bottom: 0;
}
p {
    font-size: 1.6em;
    font-weight: 300;
    line-height: 1.4;
    max-width: 28em;
}
a {
    text-decoration: none;
    white-space: nowrap;
    color: #121314;
    position: relative;
}
a:after {
    content: '';
    position: absolute;
    z-index: -1;
    top: 66%;
    left: -0.1em;
    right: -0.1em;
    bottom: 0;
    transition: top 200ms cubic-bezier(0, 0.8, 0.13, 1);
    background-color: rgba(79, 192, 141, 0.5);
}
a:hover:after {
    top: 0%;
}
</style>
