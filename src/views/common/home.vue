<template>
  <div class="mod-home">
    <h3>管理端介绍</h3>
    <ul>
      <li>前后端分离，通过token进行数据交互，可独立部署</li>
      <li>主题定制，通过scss变量统一一站式定制</li>
      <li>动态菜单，通过菜单管理统一管理访问路由</li>
      <li>数据切换，通过mock配置对接口数据／mock模拟数据进行切换</li>
      <li>发布时，可动态配置CDN静态资源／切换新旧版本</li>
    </ul>
    <h3>mark介绍</h3>
    <ul>
      <li>前后端动静分离</li>
      <li>各个服务划分为各自微服务，其中微服务做负载均衡，可独立、多地部署</li>
      <li>各个服务使用Nacos进行配置、注册，发布时可使用Nacos进行资源以及版本的的切换</li>
      <li>使用网关同一管理访问路由</li>
      <li>版本控制使用GitHub以及Git进行</li>
      <li>文件存储使用云存储</li>
    </ul>


  </div>
</template>

<script>

  export default {
  }
</script>

<style>
  .mod-home {
    line-height: 1.5;
  }
</style>

