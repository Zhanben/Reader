<template>
  <div class="card">
    <div class="card-header" align="center">
      <form class="form-inline">
        <input class="form-control mr-sm-2 wide" type="text" placeholder="搜索公众号/文章">
        <i class="fa fa-search btn btn-lg btn-outline-success" @click=""></i>
      </form>
    </div>
    <div class="card card-block">
      <div class="media  border p-3">
        <img src="http://wx.qlogo.cn/mmhead/Q3auHgzwzM5VP8rbv4fBibDLRoibcezeC7aMx2qs4hfUWtw8Cp6PDZ7Q/0"
               alt="John Doe" class="align-self-center mr-3" style="width:100px">
        <div class="media-body">
        <h4>这个导演的新片，每一部我必二刷</h4>
          <p class="text-muted" style="margin-bottom: 0px;">
            11月的时候，鱼叔采访了自己的偶像——蒂姆·波顿。并有机会提前看到了他的新片，然后写了一篇推文。今天电影上映，鱼叔去电影院二刷。这一次，又
          </p>
          <p><small class="text-muted s1">
            <span>    <i class="fa fa-star-o fa-lg float-xs-right text-danger"></i></span>
            <i class="fa fa-eye"></i> 2348 </small>
            <small class="text-muted">  独立鱼电影</small>
            <small class="text-muted s2"> 1小时前</small>
          </p>
        </div>
      </div>

      <div class="media border p-3">
        <img src="http://wx.qlogo.cn/mmhead/Q3auHgzwzM5VP8rbv4fBibDLRoibcezeC7aMx2qs4hfUWtw8Cp6PDZ7Q/0"
             alt="John Doe" class="align-self-center mr-3" style="width:100px">

        <div class="media-body">
          <h4>现在的段子，不动脑子根本就看不懂</h4>
          <p class="text-muted" style="margin-bottom: 0;">
            周末，姑妈让我帮忙表照顾5岁的表弟，晚上我给他洗澡的时候，女票打来电话。因为手不方便拿，就开了免提，她问:在做什么呢？我说...
          </p>
          <p><small class="text-muted s1">
          <span>    <i class="fa fa-star-o fa-lg float-xs-right text-danger"></i></span>
          <i class="fa fa-eye"></i> 1181 </small>
          <small class="text-muted s1"> 凤凰网 </small>
          <small class="text-muted s2"> 3小时前</small>
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
  .form-inline .wide {
    width: 80%;
  }
  .imgbox {
    width: 110px;
    height: 130px;
    overflow: hidden;
  }
  .imgbox img{
    max-width: 100px;
    /*max-height: 120px;*/
  }
  .s1 {
    margin-right: 20px;
  }
  .s2 {
    margin-left: 20px;
  }
</style>
