<template>
  <div id="app">
    <div class="container">
      <nav class="navbar navbar-expand-md navbar-dark fixed-top bg-dark">
        <a class="navbar-brand" href="#">简读</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarCollapse" aria-controls="navbarCollapse" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarCollapse">
          <ul class="navbar-nav mr-auto">
            <li class="nav-item active">
                <router-link to="/home" class="nav-link"><i class="fa fa-home"></i> 主页</router-link>
            </li>
            <li class="nav-item active">
              <router-link to="/home" class="nav-link"><i class="fa fa-book"></i> 论坛</router-link>
            </li>
          </ul>
          <form class="form-inline mt-2 mt-md-0">
            <input class="form-control mr-sm-2" type="text" placeholder="搜索公众号/文章">
            <router-link to="/search"><i class="fa fa-search btn btn-outline-success" @click=""></i></router-link>
          </form>
        </div>
      </nav>
    </div>
    <div class="container" style="margin-top: 80px">
      <div class="row">
        <div class="col-xs-12 col-md-3 push-md-9 col-xl-3 push-xl-9">
          <sidebar></sidebar>
        </div>
        <div class="col-xs-12 col-md-9 pull-md-3 col-xl-9 pull-xl-3">
          <router-view></router-view>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
    import Siderbar from './components/Siderbar.vue'

    export default {
        components: {
            'sidebar': Siderbar
        }
    }
</script>
