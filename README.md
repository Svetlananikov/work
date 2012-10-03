
/*-------css------------*/


html {
    overflow-y: scroll;
}
html, body {
    height:100%;
    width:100%;
    margin: 0;
    padding: 0;
}
body {
    background: #FFFFFF;
    font-family: Arial, Helvetica, sans-serif;
    font-size:13px;
    color:#000000;
}
a {
    color:#ea0404;
    text-decoration:none;
}
a:hover {
    text-decoration:underline;
}
img { border:0 none}
ul{ list-style: none; padding: 0; margin: 0;}
table, tr, td, th {
    border:0 none;
    border-collapse:collapse;
}
.clearfix:after {content:"."; display:block; height:0px; clear:both; visibility:hidden;}
.clear { clear:both; font-size:0px; overflow:hidden}
.float-l { float:left}
.float-r { float:right}
.align-center { text-align:center}
.align-left { text-align:left}
.align-right { text-align: right}


.example-pie-css3 {
    border: 1px solid #696;
    padding: 60px 0;
    text-align: center; width: 200px;
    -webkit-border-radius: 8px;
    -moz-border-radius: 8px;
    border-radius: 8px;
    -webkit-box-shadow: #666 0px 2px 3px;
    -moz-box-shadow: #666 0px 2px 3px;
    box-shadow: #666 0px 2px 3px;
    background: #EEFF99;
    background: -webkit-gradient(linear, 0 0, 0 bottom, from(#EEFF99), to(#66EE33));
    background: -moz-linear-gradient(#EEFF99, #66EE33);
    background: linear-gradient(#EEFF99, #66EE33);
    -pie-background: linear-gradient(#EEFF99, #66EE33);
    behavior: url(css/PIE.htc);

    -pie-lazy-init: true
}

.rounded-img {
    display: inline-block;
    overflow: hidden;
    -webkit-border-radius: 8px;
    -moz-border-radius: 8px;
    border-radius: 8px;
}
h1, h2, h3, h4, h5, h6 {
    margin:0;
    padding:8px 0;
    color:#ea0404
}
p {
    margin:0;
    padding:0;
    text-align:justify;
}


/*---------Wrapper----------*/
.wrapper { width: 960px; margin: 0 auto;}

/*---------Header----------*/
.header { position: relative; margin-bottom: 20px; border: 1px solid #000000;}
.header-i { padding: 15px 15px 77px 15px;}
.header-i__logo {width: 192px; height: 94px; float: left; margin-right: 15px}
.header-i__logo a {text-indent: -9999px; overflow: hidden;}

.header-i__menu { width: 295px; float: left;margin-right: 34px;}
.header-i__menu ul  li {display: inline; float: left;  padding-right: 20px;}
.header-i__menu ul  li:first-child { padding-left: 10px;}
.header-i__menu ul  li a.active, .header-i__menu ul  li a:hover { color:#f24510;}

.header-i__login-box { width: 410px; float: left;}
.header-i__login-box li { display: inline; float: left; padding-right: 15px;}
.header-i__login-box li:first-child{ padding-left: 15px;}
.header-i__login-box li a.item-link1 { background: url(../img/element/icon1.png) no-repeat 0 50%; padding-left: 25px}
.header-i__login-box li a.item-link2  { background: url(../img/element/icon2.png) no-repeat 0 50%; padding-left: 25px}
.header-i__login-box li a.item-link3 { background: url(../img/element/icon3.png) no-repeat 0 50%; padding-left: 25px}


/*---------Container----------*/
.container{ position:relative;z-index: 10;}

/*---------Sidebar----------*/
.sidebar {width: 200px; float: left; border: 1px solid #000000;}
.sidebar-i {padding: 45px 23px;}
.sidebar-i ul li {padding-bottom: 9px;}
.sidebar-i ul li ul li {padding-left: 8px; padding-top: 9px;}
.sidebar-i ul li:nth-child(2) li {color:#72bb53;}


/*---------Content----------*/
.content { width: 660px; float:right;}



/*---------tab-box----------*/

.tab-box { position: relative; padding: 18px 57px 33px 30px; margin-bottom: 30px; border: 1px solid #000000;}
.tab-box__menu {
    margin-bottom: 23px;
    border: 1px solid #000000;
    -webkit-border-radius: 4px;
    -moz-border-radius: 4px;
    border-radius: 4px;
    behavior: url(css/PIE.htc);
}
.tab-box__menu li { padding: 7px 18px; float: left;}
.tab-box__menu li:hover, .tab-box__menu li.active {background: #e6e6e6;}
.tab-box__menu li:first-child {
    -webkit-border-radius: 4px 0 0 4px;
    -moz-border-radius:  4px 0 0 4px;
    border-radius: 4px 0 0 4px;
    behavior: url(css/PIE.htc);
}
.tab-box__menu li:last-child {
    -webkit-border-radius: 0px 4px 4px 0px;
    -moz-border-radius: 0px 4px 4px 0px;
    border-radius:  0px 4px 4px 0px;
    behavior: url(css/PIE.htc);
}
.tab-box__info { padding: 24px 35px; clear: both; border: 1px solid #000000;}

/*---------block-info----------*/
.block-info { clear: both;}
.block-info__map-box { width: 306px; float: left; border: 1px solid #000000;}
.block-info__map-box-i{ padding:22px 43px 22px 9px; }
.block-info__map-box-i h4, .block-info__calendar-box {font-weight: normal; padding: 0 0 36px 17px;}
.block-info__map-box-i img { width: 259px; height: 159px; border: 1px solid #000000;}

.block-info__calendar-box { width: 272px; float: right; border: 1px solid #000000;}
.block-info__calendar-box-i {padding:22px 31px 22px 18px;}


/*---------text-box----------*/
.text-box{ clear: both; margin-bottom: 20px; border: 1px solid #000000;}
.text-box-i{ padding: 12px 28px 17px 53px;}
.text-box__title { width:42px; float: left; margin-right: 22px; }
.text-box__info { width: 765px; float: left; }
.text-box__info p { font-size: 13px; line-height: 16px;}



/*---------Footer----------*/
.footer { clear: both;border: 1px solid #000000;}
.footer-i { padding: 14px 22px;}
.footer-i__menu {float: left; width: 470px;border: 1px solid #000000;}
.footer-i__menu li {  float: left; display: inline;}
.footer-i__menu li a { padding: 3px 18px; display: block;}
.footer-i__menu li a:hover, .footer-i__menu li a.active{
    background: #e6e6e6;
    border-left: 1px solid #000000;
    border-right: 1px solid #000000;}
.footer-i__menu li:first-child a:hover { border-left:0}
.footer-i__menu li:last-child a:hover { border-right:0}
.footer-i__copyright { width: 325px; float: right;}