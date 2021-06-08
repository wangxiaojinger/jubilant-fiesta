# jubilant-fiesta
test
*{
	margin: 0;
	padding: 0;
}
ul li{
	list-style: none;
}
a{
	text-decoration: none;
}
.yuan{
	background: #4b3c39 url('https://i.h2.pdim.gs/613137182163879dbc9c2595a50ee220.jpg') 
	no-repeat center -10px;
    height: 310px;
    overflow: hidden;
/*    margin-bottom: 10px;*/
    min-width: 980px;
}
.yuan .content{
	width: 980px;
	margin: 0 auto;
}
.yuan .content .title{
	height: 70px;
	margin-top: 12px;
	text-align: center;
}
.yuan .content .title img{
    width: 388px;
    height: 46px;
    margin: 0 auto;
}
.yuan .stars{
	height: 240px;
	margin-top: -12px;
	/*background-color: red;*/
	position: relative;
}
.yuan .content .stars .wall-left{
	position: absolute;
    width: 100%;
    height: 240px;
    background-color: #000;
    opacity: .7;
    z-index: 1;
    left: -100%;
    top: 0;
    border-bottom: 4px solid #000;
}
.yuan .content .stars .wall-right{
	position: absolute;
    width: 100%;
    height: 240px;
    background-color: #000;
    opacity: .7;
    z-index: 1;
    right: -100%;
    top: 0;
    border-bottom: 4px solid #000;
}
.yuan .content .stars .stars-list{
    height: 240px;
    width: 800%;
    overflow: hidden;
    float: left;
    position: relative;
    margin-left: -400%;
    transition-timing-function: ease-in;
    transition-duration: 0.5s;
    /*transition: all .6s ease;*/
   /* transition-timing-function: ease-in;
    transition-duration: 0s;
    transform: translate3d(-2336px, 0px, 0px);*/
}
.yuan .content .stars .stars-list .list-unit{
	position: relative;
	width: 245px;
	height: 240px;
	float: left;
}
.yuan .stars .list-unit .des-stars{
	height: 100%;
    position: relative;
    text-align: center;
}
.yuan .stars .list-unit .des-stars img{
	width: 100%;
}
.yuan .stars .list-unit .des-stars .cover{
	position: absolute;
    z-index: 0;
    left: 0;
    right: 0;
    top: 0;
    bottom: 0;
	height: 100%;
	background-color: #000;
	opacity: .3;
	transition: all linear 300ms;
}
.yuan .stars .list-unit .des-stars .line{
	height: 4px;
    width: 100%;
    position: absolute;
    bottom: 0;
    opacity: 1;
    transition: all linear 300ms;
    background-color: #1dd388;
}
.yuan .stars .stars-info{
	height: 110px;
    position: absolute;
    bottom: 0;
    text-align: center;
    width: 100%;
    transition: all linear 250ms;
    color: #fff;
}
.yuan .stars .stars-info .name{
	font-size: 20px;
    height: 26px;
    line-height: 26px;
    overflow: hidden;
    text-overflow: ellipsis;
    white-space: nowrap;
}
.yuan .stars .stars-info .intro{
    padding: 0 10px;
    font-size: 14px;
    height: 18px;
    line-height: 18px;
    margin: 5px 0 30px;
    color: rgba(255,255,255,.7);
    overflow: hidden;
    text-overflow: ellipsis;
    white-space: nowrap;
}
.yuan .stars .stars-info .incon-live{
	position: absolute;
    left: 50%;
    bottom: 38px;
    width: 29px;
    height: 9px;
    margin-left: -15px;
    background: url('https://i.h2.pdim.gs/77e7f6d74c435eedc456e67dd537789f.png') no-repeat;
    opacity: 1;
    transition: all linear 250ms;
}
.yuan .stars .stars-info .number{
	display: inline-block;
    overflow: hidden;
    transition: all linear 250ms;
    height: 20px;
    line-height: 20px;
    width: 245px;
    position: absolute;
    bottom: 8px;
    left: 0;
}
.yuan .stars .stars-info .number i{
	width: 16px;
    height: 12px;
    display: inline-block;
    background: url(https://i.h2.pdim.gs/a5ca2334f735817e0dc1268b26f5eb82.png) no-repeat center;
    margin-right: 8px;
}
.yuan .stars .list-unit .des-stars:hover .stars-info .name{
	margin-top: 5px;
}
.yuan .stars .list-unit .des-stars:hover .stars-info .intro{
    margin: 5 auto 5px;
    overflow: hidden;
    transition:  all .4s ease;
}
.yuan .stars .list-unit .des-stars:hover .stars-info .incon-live{
	opacity: 0;
	transition: all .4s ease;
}
.yuan .stars .list-unit .des-stars:hover .stars-info{
    height: 95px;
    transition: all .4s ease;
}
.yuan .stars .list-unit .des-stars:hover  .line{
	height: 95px;
	opacity: 0.7;
	background-color: #1dd388;
	transition: all .4s ease;
}
.yuan .stars .list-unit .des-stars:hover .cover{
	opacity: 0;
	transition: all .4s ease;
}
.yuan .stars .button .btn-left{
	left: -35px;
    position: absolute;
    width: 35px;
    height: 80px;
    top: 105px;
    z-index: 2;
    font-style: normal;
}
.yuan .stars .button .a-left{
	left: 0;
    background: url('https://i.h2.pdim.gs/9a8d46095edb3487a4ef4918140a5892.png') 
    no-repeat 0 0;
	width: 35px;
    height: 80px;
    position: absolute;
    z-index: 3;
    display: block;
    top: 0;
}
.yuan .stars .button .btn-right{
	right: -35px;
    position: absolute;
    width: 35px;
    height: 80px;
    top: 105px;
    z-index: 2;
    font-style: normal;
}
.yuan .stars .button .a-right{
	right: 0;
    background: url('https://i.h2.pdim.gs/9a8d46095edb3487a4ef4918140a5892.png') 
    no-repeat -35px 0;
	width: 35px;
    height: 80px;
    position: absolute;
    z-index: 3;
    display: block;
    top: 0;
}
