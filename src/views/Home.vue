<template>
  <div id="home">
    <Header></Header>
    <div>
      <h1>知乎专栏</h1>
      <h2>随心写作，自由表达</h2>
      <button>开始写文章</button>
      <button>申请开通专栏
        <span style="display:inline-flex;align-items:center">​<svg class="Zi Zi--ArrowRight" fill="currentColor" viewBox="0 0 24 24" width="1.2em" height="1.2em"><path d="M9.218 16.78a.737.737 0 0 0 1.052 0l4.512-4.249a.758.758 0 0 0 0-1.063L10.27 7.22a.737.737 0 0 0-1.052 0 .759.759 0 0 0-.001 1.063L13 12l-3.782 3.716a.758.758 0 0 0 0 1.063z" fill-rule="evenodd"></path></svg></span>
      </button>
    </div>
    <div>
      <h3>专栏 · 发现</h3>
      <div>
        <a>
          <img width="48" height="48" src="https://pic4.zhimg.com/v2-463d6baa72be45c295632a968d0e4053_xs.jpg" srcset="https://pic4.zhimg.com/v2-463d6baa72be45c295632a968d0e4053_l.jpg 2x" alt="专栏图像">
          <div>
            <div>外汇的逻辑</div>
            <div>我曾在芬兰央行任职宏观研究助理，长期以来对外汇研究和交易都是充满了热爱。不管从理论还是到实战交易，我都希望能写出来跟大家讨论。</div>
          </div>
          <div>
            1,785
            人关注 |
            3
            篇文章
          </div>
          <button>进入专栏</button>
        </a>
      </div>
      <button>
        <span style="display:inline-flex;align-items:center">​<svg class="Zi Zi--Refresh Button-zi" fill="currentColor" viewBox="0 0 24 24" width="1.2em" height="1.2em"><path d="M20 12.878C20 17.358 16.411 21 12 21s-8-3.643-8-8.122c0-4.044 3.032-7.51 6.954-8.038.034-1.185.012-1.049.012-1.049-.013-.728.461-1.003 1.057-.615l3.311 2.158c.598.39.596 1.026 0 1.418l-3.31 2.181c-.598.393-1.08.12-1.079-.606 0 0 .006-.606-.003-1.157-2.689.51-4.675 2.9-4.675 5.708 0 3.21 2.572 5.822 5.733 5.822 3.163 0 5.733-2.612 5.733-5.822 0-.633.51-1.148 1.134-1.148.625 0 1.133.515 1.133 1.148" fill-rule="evenodd"></path></svg></span>
        换一换
      </button>
    </div>
    <div>
      <h3>在知乎创作</h3>
      <button>申请专栏</button>
      <footer class="ColumnHomeBottom-footer">
        <span>
          ©
          2020
          知乎
        </span>
        <span> · </span>
        <a target="_blank" href="/" rel="noopener noreferrer">知乎专栏</a>
        <span> · </span>
        <a target="_blank" href="https://www.zhihu.com/roundtable" rel="noopener noreferrer">圆桌</a>
        <span>·</span>
        <a target="_blank" href="https://www.zhihu.com/explore" rel="noopener noreferrer">发现</a>
        <span> · </span>
        <a target="_blank" href="https://www.zhihu.com/app" rel="noopener noreferrer">移动应用</a>
        <span> · </span>
        <a href="https://www.zhihu.com/signin?no_qrcode=1">使用机构帐号登录</a>
        <span> · </span>
        <a href="https://www.zhihu.com/contact">联系我们</a>
        <span> · </span>
        <a target="_blank" href="https://www.zhihu.com/careers" rel="noopener noreferrer">来知乎工作</a>
        <br>
        <a href="https://tsm.miit.gov.cn/dxxzsp/" target="_blank" rel="noopener noreferrer">京 ICP 证 110745 号</a>
        <span> · </span>
        <a href="http://www.beian.miit.gov.cn" target="_blank" rel="noopener noreferrer">京 ICP 备 13052560 号 - 1</a>
        <span> · </span>
        <a target="_blank" rel="noopener noreferrer" href="http://www.beian.gov.cn/portal/registerSystemInfo?recordcode=11010802020088">
          <img src="https://pic3.zhimg.com/80/v2-d0289dc0a46fc5b15b3363ffa78cf6c7.png">
          京公网安备 11010802010035 号
        </a>
        <span> · </span>
        <a href="http://zhstatic.zhihu.com/assets/zhihu/publish-license.jpg" target="_blank" rel="noopener noreferrer">出版物经营许可证</a>
      </footer>
    </div>
  </div>
</template>

<script>
  import Header from "../components/Header";

  export default {
    name: "Home",
    components: {Header}
  }
</script>

<style scoped lang="less">

</style>
