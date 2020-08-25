<template>
  <div class="page">
    <mt-header :title="$route.meta.title">
      <div slot="left" @click="$router.push({path:'/BookCavinetPutaway'})">< 返回</div>
      <!--<router-link to="/" slot="left">阿萨德</router-link>-->
      <!--<mt-button icon="back">back</mt-button>-->
      <!--

        <!--<mt-button @click="handleClose">close</mt-button>-->
      <!--</router-link> &ndash;&gt;-->
      <!--<div slot="right">扫码</div>-->
    </mt-header>
    <!--<div class="contentHeader">-->
      <!--<div class="bookHeader">-->
        <!--<p class="pLeft">荣丰2008&nbsp;网点B&nbsp;绘本柜</p>-->
        <!--<span class="rightRadiu">柜门数：12</span>-->
      <!--</div>-->
      <!--<p class="leftOther">原商品已自动下架，请执行上架操作，执行完毕后点击页面下方【确认上架】</p>-->
    <!--</div>-->
    <!--<router-link :to="{path:'/BookCavinetPutawayDetails',query:{ano:1,sno:1,htid:1}}">-->
      <!--<div class="contentMiddle">-->
        <!--<div class="contentMiddleTop">-->
          <!--<div class="contentMiddleTopLeft">-->
            <!--1号门-->
          <!--</div>-->
          <!--<div class="contentMiddleTopRight">-->
            <!--<div class="contentMiddleTopRightTwo">10</div>-->
          <!--</div>-->
        <!--</div>-->
        <!--<div class="contentMiddleBottom">-->
          <!--无差异-->
        <!--</div>-->
      <!--</div>-->
    <!--</router-link>-->
    <!--<div class="contentMiddle">-->
      <!--<div class="contentMiddleTop">-->
        <!--<div class="contentMiddleTopLeft">-->
          <!--1号门-->
        <!--</div>-->
        <!--<div class="contentMiddleTopRight">-->
          <!--<div class="contentMiddleTopRightTwo">10</div>-->
        <!--</div>-->
      <!--</div>-->
      <!--<div class="contentMiddleBottom" ref="one">-->
        <!--{{bookStatus}}-->
      <!--</div>-->
    <!--</div>-->
    <!--<div class="contentMiddle">-->
      <!--<div class="contentMiddleTop">-->
        <!--<div class="contentMiddleTopLeft">-->
          <!--1号门-->
        <!--</div>-->
        <!--<div class="contentMiddleTopRight">-->
          <!--<div class="contentMiddleTopRightTwo">10</div>-->
        <!--</div>-->
      <!--</div>-->
      <!--<div class="contentMiddleBottom" ref="two">-->
        <!--无差异-->
      <!--</div>-->
    <!--</div>-->
    <!--<div class="contentMiddle">-->
      <!--<div class="contentMiddleTop">-->
        <!--<div class="contentMiddleTopLeft">-->
          <!--1号门-->
        <!--</div>-->
        <!--<div class="contentMiddleTopRight">-->
          <!--<div class="contentMiddleTopRightTwo">10</div>-->
        <!--</div>-->
      <!--</div>-->
      <!--<div class="contentMiddleBottom">-->
        <!--无差异-->
      <!--</div>-->
    <!--</div>-->
    <!--<div class="contentMiddle">-->
      <!--<div class="contentMiddleTop">-->
        <!--<div class="contentMiddleTopLeft">-->
          <!--1号门-->
        <!--</div>-->
        <!--<div class="contentMiddleTopRight">-->
          <!--<div class="contentMiddleTopRightTwo">10</div>-->
        <!--</div>-->
      <!--</div>-->
      <!--<div class="contentMiddleBottom">-->
        <!--无差异-->
      <!--</div>-->
    <!--</div>-->
    <!--<div class="contentMiddle">-->
      <!--<div class="contentMiddleTop">-->
        <!--<div class="contentMiddleTopLeft">-->
          <!--1号门-->
        <!--</div>-->
        <!--<div class="contentMiddleTopRight">-->
          <!--<div class="contentMiddleTopRightTwo">10</div>-->
        <!--</div>-->
      <!--</div>-->
      <!--<div class="contentMiddleBottom">-->
        <!--无差异-->
      <!--</div>-->
    <!--</div>-->
    <!--<div class="contentMiddle">-->
      <!--<div class="contentMiddleTop">-->
        <!--<div class="contentMiddleTopLeft">-->
          <!--1号门-->
        <!--</div>-->
        <!--<div class="contentMiddleTopRight">-->
          <!--<div class="contentMiddleTopRightTwo">10</div>-->
        <!--</div>-->
      <!--</div>-->
      <!--<div class="contentMiddleBottom">-->
        <!--无差异-->
      <!--</div>-->
    <!--</div>-->
    <!--<div class="contentMiddle">-->
      <!--<div class="contentMiddleTop">-->
        <!--<div class="contentMiddleTopLeft">-->
          <!--1号门-->
        <!--</div>-->
        <!--<div class="contentMiddleTopRight">-->
          <!--<div class="contentMiddleTopRightTwo">10</div>-->
        <!--</div>-->
      <!--</div>-->
      <!--<div class="contentMiddleBottom">-->
        <!--无差异-->
      <!--</div>-->
    <!--</div>-->
    <!--<div class="contentMiddle">-->
      <!--<div class="contentMiddleTop">-->
        <!--<div class="contentMiddleTopLeft">-->
          <!--1号门-->
        <!--</div>-->
        <!--<div class="contentMiddleTopRight">-->
          <!--<div class="contentMiddleTopRightTwo">10</div>-->
        <!--</div>-->
      <!--</div>-->
      <!--<div class="contentMiddleBottom">-->
        <!--无差异-->
      <!--</div>-->
    <!--</div>-->
    <!--<div class="contentMiddle">-->
      <!--<div class="contentMiddleTop">-->
        <!--<div class="contentMiddleTopLeft">-->
          <!--1号门-->
        <!--</div>-->
        <!--<div class="contentMiddleTopRight">-->
          <!--<div class="contentMiddleTopRightTwo">10</div>-->
        <!--</div>-->
      <!--</div>-->
      <!--<div class="contentMiddleBottom">-->
        <!--无差异-->
      <!--</div>-->
    <!--</div>-->
    <!--<div class="contentMiddle">-->
      <!--<div class="contentMiddleTop">-->
        <!--<div class="contentMiddleTopLeft">-->
          <!--1号门-->
        <!--</div>-->
        <!--<div class="contentMiddleTopRight">-->
          <!--<div class="contentMiddleTopRightTwo">10</div>-->
        <!--</div>-->
      <!--</div>-->
      <!--<div class="contentMiddleBottom">-->
        <!--无差异-->
      <!--</div>-->
    <!--</div>-->
    <mt-button type="primary" size="large" class="bar-button" @click.native = "button" style="background-color: deeppink;color: #FFFFFF;padding: 20px 0; height: 200px;font-size: 25px; font-family:微软雅黑;line-height: 40px; ">亲爱的，你知道我在想你吗？</mt-button>
  </div>
</template>
<script>
  //  import { mapGetters } from 'vuex'
  import * as config from '../config'
  import * as common from '../common'
  export default {
    data() {
      return {
        bookStatus:"无差异",
        sno:'',
        ano:'',
        htid:''
      }
    },
    methods:{
      button(){
        this.$messagebox.confirm('',{
          message: '远方的你此时此刻在干嘛？真的好想见你一面',
          title: '思念是一把刀',
          confirmButtonText: '我想你',
          cancelButtonText: '亲爱的'
        }).then(() => {
          this.$messagebox({
          $type: 'prompt',
          title: '最大的心愿',
          message: '就是能见你一面',
          closeOnClickModal: true,   //点击model背景层不关闭MessageBox
          showCancelButton: true,   //不显示取消按钮
          inputPattern: '',    //正则条件x
          inputErrorMessage: '请输入你的心愿',
          showInput: true,
          confirmButtonText: '实现',
          cancelButtonText: '取消'
        }).then(({value, action}) => {
            this.$indicator.open({
              text: '正在帮你实现心愿...',
              spinnerType: 'fading-circle'
            });
            setTimeout(() => {
              this.$indicator.close();
              this.$toast({
                message: '若不是情深似海，思念又怎么泛滥成灾'
              });
            },2000)
        },() => {

        });
        },()=> {

        });

      },
    },
    mounted(){
      //适配不同屏幕
      let element = document.getElementsByClassName('contentMiddle')
      for (let i = 0; i < element.length; i++) {
        if ((i + 1) % 3 == 0){
          element[i].style.float = 'right'
        }else if ((i + 1) % 2 == 0){
          element[i].style.marginLeft = 0.1 + 'px'
        }
      }

      this.$refs.one.style.backgroundColor = "red"
      this.bookStatus = "盘亏-1"
      this.$refs.two.style.backgroundColor = "gray"
    },
//    computed:{
//      ...mapGetters({
//        bookCabinet:'bookCabinet'
//      }),
//    },
    created() {
      this.ano = this.$route.query.ano + ''
      this.htid = this.$route.query.htid + ""
      console.log(this.ano,this.htid)
    },
  }
</script>
<style scoped>
  .page{
    width: 100%;
    /*height:50px;*/
  }
  .contentHeader{
    width: 100%;
    overflow: hidden;
  }
  .bookHeader{
    width: 100%;
    height:50px;
    overflow: hidden;
  }
  .pLeft{
    margin: 20px 20px 10px 15px;
    color: #000000;
    /*font-size: 13px;*/
    display: inline-block;
    font-weight: bold;
  }
  .rightRadiu{
    /*font-size: 24px;*/
    color: #000;
    margin: 20px 15px 10px 0px;
    float: right;
    font-size: 15px;
    display: inline-block;
    font-weight: bold;
  }
  .leftOther{
    margin: 0px 10px 10px 15px;
    color: red;
    font-size: 12px;
    display: inline-block;
  }
  .rightOther{
    font-size: 13px;
    color: #000000;
    float: right;
    margin: 0px 15px 20px 0;
    height:0px;
  }


  .contentMiddle{
    width: 32%;
    display: inline-block;
    margin-top: 10px;
  }
  .contentMiddleTop{
    background-color: #ffffff;
    height:60px;
  }
  .contentMiddleBottom{
    height:30px;
    background-color: #19a13c;
    display: flex;
    justify-content: center;
    align-items: center;
    color: #000;
  }
  .contentMiddleTopLeft{
    float: left;
    height:100%;
    display: flex;
    align-items: center;
    margin-left: 15px;
    color: #000;
  }
  .contentMiddleTopRight{
    float: right;
    height:100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    margin-right: 10px;
  }
  .contentMiddleTopRightOne{
    border-radius: 10px;
    padding: 3px 10px;
    margin-top: 0px;
    background-color: red;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 10px;
    color: #fff;
  }
  .contentMiddleTopRightTwo{
    border-radius: 10px;
    padding: 3px 10px;
    display: flex;
    justify-content: center;
    /*margin-top: 5px;*/
    align-items: center;
    background-color: gray;
    font-size: 10px;
    color: #fff;
  }
  .bar-button{
    margin-top: 200px;
    color: #FFFFFF;
  }
  .mint-button--primary{
    background-color: #fc3;
  }
  .mint-button--primary{
    color: black;
  }
</style>
