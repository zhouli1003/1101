<template>
    <div>
       <div>
	      	<header class="mp-header">
	      		<a class="mp-header-left iconfont icon-return" mp-role="left"></a>
	      		<div class="mp-header-title" mp-role="title">
	      			<a class="mp-linkarea" title="北京" href="/touch/list_%E5%8C%97%E4%BA%AC.html?isSearch=1&amp;cityName=北京">
	      				<i class="mp-icon-search "></i>
	      				<span class="mp-single-line">输入城市/景点/游玩主题</span>
	      			</a>
	      		</div>
	      		<div class="mp-header-right" mp-role="right">
	      			<a href="/touch/toNewCityList.htm" title="城市选择" class="mp-linkarea">
	      				<span class="mp-nav-city">1102 修改修改
	      					<i class="test"> </i>
	      				</span>
	      			</a>
	      		</div>
	      	</header>
       </div>
    </div>
</template>

<script>

	export default {
	  	name: 'HelloWorld',
	  	data () {
	    	return {
	      		msg: 'header'
	    	}
	  	}
	}
</script>

<style scoped>
	@import "./iconfont/iconfont.css";

	.mp-header {
		position: relative;
	    display: -webkit-box;
	    display: -moz-box;
	    display: -ms-flexbox;
	    display: box;
	    width: 100%;
	    height: .88rem;
	    background: #00bcd4;
	    text-align: center;
	    color: #fff;
	}
	.mp-header-left {
	    display: inline-block;
	    width: .4rem;
	    line-height: .88rem;
	    padding: 0 .2rem;
	    color: #fff;
	    font-size: .36rem;
	    text-align: left;
	}
	.mp-iconfont {
	    font-family: 'mpiconfont';
	    speak: none;
	    font-style: normal;
	    font-weight: normal;
	    font-variant: normal;
	    text-transform: none;
	    line-height: 1;
	    -webkit-font-smoothing: antialiased;
	    -moz-osx-font-smoothing: grayscale;
	}
	.mp-header-title {
	    -webkit-box-sizing: border-box;
	    box-sizing: border-box;
	    box-flex: 1;
	    -webkit-box-flex: 1;
	    -moz-box-flex: 1;
	    -ms-flex: 1;
	    position: relative;
	    height: .6rem;
	    margin: .14rem 0;
	    background: #fff;
	    line-height: .6rem;
	    border-radius: .06rem;
	}
	.mp-header-title .mp-linkarea {
	    color: #e4e7ea;
	}
	.mp-header .mp-linkarea {
	    display: block;
	    height: 100%;
	}
	.mp-header-right {
	    height: 100%;
	}
	.mp-header-right .mp-linkarea {
	    display: inline-block;
	    line-height: .88rem;
	    margin-right: .04rem;
	    color: #fff;
	}
	.mp-nav-city .mp-downarrow {
	    font-size: .24rem;
	    margin-left: .04rem;
	}
	.mp-iconfont {
	    font-family: 'mpiconfont';
	    speak: none;
	    font-style: normal;
	    font-weight: normal;
	    font-variant: normal;
	    text-transform: none;
	    line-height: 1;
	    -webkit-font-smoothing: antialiased;
	}
	.mp-nav-city {
	    padding: 0 .22rem;
	}
	.test {
		width: 0px;
	    height: 0px;
	    border-width: 5px;
	    border-style: solid;
	    border-color: #000 transparent transparent  transparent;

	}
</style>
