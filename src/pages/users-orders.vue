<template>
  <div class="container-wrap">
      <div class="orders" v-show="!isPing">
         <div class="order-top">
           <ul>
             <li>全部</li>
             <li class="on">已完成</li>
             <li>待付款 <i class="icon iconsfont icons-yuanjiao1">1</i></li>
             <li>待收货</li>
           </ul>
         </div>
         <div class="order-box">
          <div class="pro-list">
            <ul>
              <li class="flex-w">
                <div class="pro-box flex-h">
                  <div class="pro-img"><img src="../style/images/car-img.jpg" alt="" ></div>
                  <div class="content">
                    <p><h2>订单编号 10700234230</h2></p>
                    <p>cookies au beurre <br>
                      云顶小花曲奇（抹茶味）1111</p>
                    <div class="o-time">
                      <p><i class="icon iconsfont icons-clock"></i>下单时间：2017-07-14 18:14:46</p>
                    </div>
                  </div>
                  <div class="edit">
                    <p><i class="icon iconsfont icons-lajixiang"></i>删除</p>
                    <p class="price"><em>￥</em>299</p>
                  </div>
                </div>
                <div class="pro-btns">
                  <ul>
                    <li><i class="icon iconsfont icons-test"></i>订单详情</li><em></em>
                    <li @click="goComment"><i class="icon iconsfont icons-pop"></i>去评价</li><em></em>
                    <li class="share"><i class="icon iconsfont icons-money1"></i>分享优惠券</li>
                  </ul>
                </div>
              </li>
              <li class="flex-w">
                <div class="pro-box flex-h">
                  <div class="pro-img"><img src="../style/images/car-img.jpg" alt="" ></div>
                  <div class="content">
                    <p><h2>订单编号 10700234230</h2></p>
                    <p>cookies au beurre <br>
                      云顶小花曲奇（抹茶味）</p>
                    <div class="o-time">
                      <p><i class="icon iconsfont icons-clock"></i>下单时间：2017-07-14 18:14:46</p>
                    </div>
                  </div>
                  <div class="edit">
                    <p>取消</p>
                    <p class="price"><em>￥</em>299</p>
                  </div>
                </div>
                <div class="pro-btns2">
                  <dl>
                    <dd class="cancel"><span><i class="icon iconsfont icons-test"></i>订单详情</span></dd>
                    <dd><span><i class="icon iconsfont icons-pop"></i>去支付</span></dd>
                  </dl>
                </div>
              </li>

            </ul>
          </div>
        </div>
         <div class="order-box" style="display: block;">
           <div class="pro-list">
             <ul>
               <li class="flex-w">
                 <div class="pro-box flex-h">
                     <div class="pro-img"><img src="../style/images/car-img.jpg" alt="" ></div>
                     <div class="content">
                       <p><h2>订单编号 10700234230</h2></p>
                       <p>cookies au beurre <br>
                         云顶小花曲奇（抹茶味）</p>
                       <div class="o-time">
                         <p><i class="icon iconsfont icons-clock"></i>下单时间：2017-07-14 18:14:46</p>
                       </div>
                     </div>
                     <div class="edit">
                       <p><i class="icon iconsfont icons-lajixiang"></i>删除</p>
                       <p class="price"><em>￥</em>299</p>
                     </div>
                 </div>
                  <div class="pro-btns">
                    <ul>
                      <li><i class="icon iconsfont icons-test"></i>订单详情</li><em></em>
                      <li><i class="icon iconsfont icons-pop"></i>去评价</li><em></em>
                      <li class="share"><i class="icon iconsfont icons-money1"></i>分享优惠券</li>
                    </ul>
                  </div>
               </li>
               <li class="flex-w">
                 <div class="pro-box flex-h">
                   <div class="pro-img"><img src="../style/images/car-img.jpg" alt="" ></div>
                   <div class="content">
                     <p><h2>订单编号 10700234230</h2></p>
                     <p>cookies au beurre <br>
                       云顶小花曲奇（抹茶味）</p>
                     <div class="o-time">
                       <p><i class="icon iconsfont icons-clock"></i>下单时间：2017-07-14 18:14:46</p>
                     </div>
                   </div>
                   <div class="edit">
                     <p><i class="icon iconsfont icons-lajixiang"></i>删除</p>
                     <p class="price"><em>￥</em>299</p>
                   </div>
                 </div>
                 <div class="pro-btns">
                   <ul>
                     <li><i class="icon iconsfont icons-test"></i>订单详情</li><em></em>
                     <li><i class="icon iconsfont icons-pop"></i>去评价</li><em></em>
                     <li class="share"><i class="icon iconsfont icons-money1"></i>分享优惠券</li>
                   </ul>
                 </div>
               </li>

             </ul>
           </div>
         </div>
         <div class="order-box">
          <div class="pro-list">
            <ul>
              <li class="flex-w">
                <div class="pro-box flex-h">
                  <div class="pro-img"><img src="../style/images/car-img.jpg" alt="" ></div>
                  <div class="content">
                    <p><h2>订单编号 10700234230</h2></p>
                    <p>cookies au beurre <br>
                      云顶小花曲奇（抹茶味）</p>
                    <div class="o-time">
                      <p><i class="icon iconsfont icons-clock"></i>下单时间：2017-07-14 18:14:46</p>
                    </div>
                  </div>
                  <div class="edit">
                    <p>取消</p>
                    <p class="price"><em>￥</em>299</p>
                  </div>
                </div>
                <div class="pro-btns2">
                  <dl>
                    <dd class="cancel"><span><i class="icon iconsfont icons-test"></i>订单详情</span></dd>
                    <dd><span><i class="icon iconsfont icons-pop"></i>去支付</span></dd>
                  </dl>
                </div>
              </li>
              <li class="flex-w">
                <div class="pro-box flex-h">
                  <div class="pro-img"><img src="../style/images/car-img.jpg" alt="" ></div>
                  <div class="content">
                    <p><h2>订单编号 10700234230</h2></p>
                    <p>cookies au beurre <br>
                      云顶小花曲奇（抹茶味）</p>
                    <div class="o-time">
                      <p><i class="icon iconsfont icons-clock"></i>下单时间：2017-07-14 18:14:46</p>
                    </div>
                  </div>
                  <div class="edit">
                    <p>取消</p>
                    <p class="price"><em>￥</em>299</p>
                  </div>
                </div>
                <div class="pro-btns2">
                  <dl>
                    <dd class="cancel"><span><i class="icon iconsfont icons-test"></i>订单详情</span></dd>
                    <dd><span><i class="icon iconsfont icons-pop"></i>去支付</span></dd>
                  </dl>
                </div>
              </li>
            </ul>
          </div>
        </div>
         <div class="order-box">
          <div class="pro-list">
            <ul>
              <li class="flex-w">
                <div class="pro-box flex-h">
                  <div class="pro-img"><img src="../style/images/car-img.jpg" alt="" ></div>
                  <div class="content">
                    <p><h2>订单编号 10700234230</h2></p>
                    <p>cookies au beurre <br>
                      云顶小花曲奇（抹茶味）</p>
                    <div class="luyin"><i class="icon iconsfont icons-luyin1"></i><span>录音传情</span></div>
                    <div class="o-time">
                      <p><i class="icon iconsfont icons-clock"></i>下单时间：2017-07-14 18:14:46</p>
                    </div>
                  </div>
                  <div class="edit">
                    <p class="price"><em>￥</em>299</p>
                  </div>
                </div>
                <div class="pro-btns">
                  <ul>
                    <li class="cancel"><span><i class="icon iconsfont icons-test"></i>订单详情</span></li><em></em>
                    <li><span><i class="icon iconsfont icons-pop"></i>查看配送信息</span></li>
                  </ul>
                </div>
              </li>
              <li class="flex-w">
                <div class="pro-box flex-h">
                  <div class="pro-img"><img src="../style/images/car-img.jpg" alt="" ></div>
                  <div class="content">
                    <p><h2>订单编号 10700234230</h2></p>
                    <p>cookies au beurre <br>
                      云顶小花曲奇（抹茶味）</p>
                    <div class="luyin"><i class="icon iconsfont icons-luyin1"></i><span>录音传情</span></div>
                    <div class="o-time">
                      <p><i class="icon iconsfont icons-clock"></i>下单时间：2017-07-14 18:14:46</p>
                    </div>
                  </div>
                  <div class="edit">
                    <p class="price"><em>￥</em>299</p>
                  </div>
                </div>
                <div class="pro-btns">
                  <ul>
                    <li class="cancel"><span><i class="icon iconsfont icons-test"></i>订单详情</span></li><em></em>
                    <li><span><i class="icon iconsfont icons-pop"></i>查看配送信息</span></li>
                  </ul>
                </div>
              </li>
            </ul>
          </div>

        </div>
      </div>
      <div class="pinglun" v-show="isPing">
        <ul>
          <li>
            <div class="order-num"><span>订单编号: 10700234230</span>   <span class="textRight">交易完成</span></div>
            <div class="ping-box">
                  <div class="ping-top flex-h">
                    <div class="pro-img">
                      <img src="../style/images/car-img.jpg" alt="" >
                      <p>Napoléon vanille <br> 经典香草拿破仑</p>
                      <div class="bangshu">2磅</div>
                    </div>
                    <div class="content">
                        <div class="textbox">
                          <textarea rows="3" cols="20" class="ping-text" v-show="isEdit"></textarea>
                        </div>
                        <p>
                          <span class="on">好吃</span>
                          <span>口感细腻</span>
                          <span>配送快</span>
                          <span>服务好</span>
                        </p>
                        <div class="edit" v-show="!isEdit">
                          <i class="icon iconsfont icons-gaixie" @click="edit"></i>
                        </div>
                    </div>
                  </div>
            </div>
            <div class="ping-box">
              <div class="ping-top flex-h">
                <div class="pro-img">
                  <img src="../style/images/car-img.jpg" alt="" >
                  <p>Napoléon vanille <br> 经典香草拿破仑</p>
                  <div class="bangshu">2磅</div>
                </div>
                <div class="content">
                  <div class="textbox">
                    <textarea rows="3" cols="20" class="ping-text" v-show="isEdit"></textarea>
                  </div>

                  <p>
                    <span>好吃</span>
                    <span>口感细腻</span>
                    <span>配送快</span>
                    <span>服务好</span>
                  </p>
                  <div class="edit" v-show="!isEdit">
                    <i class="icon iconsfont icons-gaixie" @click="edit"></i>
                  </div>
                </div>
              </div>
            </div>
            <div class="ping-box">
              <div class="ping-top flex-h">
                <div class="pro-img">
                  <img src="../style/images/car-img.jpg" alt="" >
                  <p>Napoléon vanille <br> 经典香草拿破仑</p>
                  <div class="bangshu">2磅</div>
                </div>
                <div class="content">
                  <div class="textbox">
                    <textarea rows="3" cols="20" class="ping-text" v-show="isEdit"></textarea>
                  </div>

                  <p>
                    <span>好吃</span>
                    <span>口感细腻</span>
                    <span>配送快</span>
                    <span>服务好</span>
                  </p>
                  <div class="edit" v-show="!isEdit">
                    <i class="icon iconsfont icons-gaixie" @click="edit"></i>
                  </div>
                </div>
              </div>
            </div>
            <div class="ping-box">
              <div class="ping-top flex-h">
                <div class="pro-img">
                  <img src="../style/images/car-img.jpg" alt="" >
                  <p>Napoléon vanille <br> 经典香草拿破仑</p>
                  <div class="bangshu">2磅</div>
                </div>
                <div class="content">
                  <div class="textbox">
                    <textarea rows="3" cols="20" class="ping-text" v-show="isEdit"></textarea>
                  </div>

                  <p>
                    <span>好吃</span>
                    <span>口感细腻</span>
                    <span>配送快</span>
                    <span>服务好</span>
                  </p>
                  <div class="edit" v-show="!isEdit">
                    <i class="icon iconsfont icons-gaixie" @click="edit"></i>
                  </div>
                </div>
              </div>
            </div>
          </li>
          <li>
            <div class="order-num"><span>订单编号: 10700234230</span>   <span class="textRight">交易完成</span></div>
            <div class="ping-box">
              <div class="ping-top flex-h">
                <div class="pro-img">
                  <img src="../style/images/car-img.jpg" alt="" >
                  <p>Napoléon vanille <br> 经典香草拿破仑</p>
                  <div class="bangshu">2磅</div>
                </div>
                <div class="content">
                  <div class="textbox">
                    <textarea rows="3" cols="20" class="ping-text" v-show="isEdit"></textarea>
                  </div>

                  <p>
                    <span>好吃</span>
                    <span>口感细腻</span>
                    <span>配送快</span>
                    <span>服务好</span>
                  </p>
                  <div class="edit" v-show="!isEdit">
                    <i class="icon iconsfont icons-gaixie" @click="edit"></i>
                  </div>
                </div>
              </div>
            </div>
          </li>
        </ul>
      </div>
    <div class="btns fixed">
      <ul >
        <li @click="comment"><span>提交评价</span></li>

      </ul>
    </div>
    <my-dialog :is-show="isShowDialog">
      <!--<p class="dialog-close" @click="closeDialog"  slot="close"> <i class="icon iconsfont icons-guanbi"></i></p>-->
      <div class="tip-txt">
        <i class="icon iconsfont icons-dui"></i>
        <p>评价提交成功</p>
      </div>
    </my-dialog>
    <div class="marginBottom"></div>
  </div>

</template>

<script>
  import dialogTips from '../components/dialog-tips'
export default {
  name: 'orders',
  props: [],
  components: {
    myDialog: dialogTips
  },
  data () {
    return {
      msg: '我的订单',
      isPing:false,
      isEdit:false,
      isShowDialog:false
    }
  },
  mounted(){
    this.tabSlide();
  },
  methods:{
    tabSlide: function (event) {
        $(".orders").find(".order-top li").click(function () {
            $(this).addClass("on").siblings().removeClass("on");
            var index = $(this).index();
          $(".order-box").eq(index).show().siblings('.order-box').hide(0);
        });
     // console.log($(".order-box"));

    },
    edit:function (event) {
      this.isEdit = true;
    },
    goComment:function () {
      this.isPing = true;
    },
    comment: function (event) {
     this.isShowDialog = true;
     var self = this;
     setTimeout(function () {
       self.isShowDialog = false;
     },2000);
    }
  }
}



</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  @import '../style/css/orders.css';
</style>
