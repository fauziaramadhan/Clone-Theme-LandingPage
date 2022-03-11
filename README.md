<?xml version="1.0" encoding="UTF-8" ?>
<!DOCTYPE html>
<HTML expr:dir='data:blog.languageDirection'>
  <head>
    <link href='http://fonts.googleapis.com/css?family=Kreon:light,regular' rel='stylesheet' type='text/css'/>
    <link href='http://fonts.googleapis.com/css?family=Oswald' rel='stylesheet' type='text/css'/>
    <link href='http://fonts.googleapis.com/css?family=Bree%20Serif:400,700' rel='stylesheet' type='text/css'/>
    <link href='http://fonts.googleapis.com/css?family=Open+Sans:400' rel='stylesheet'/>
    <meta content='width=device-width, initial-scale=1, maximum-scale=1' name='viewport'/>
    <b:if cond='data:blog.pageType == &quot;error_page&quot;'>
      <title>
        Page Not Found! 
      </title>
    </b:if>
    <b:if cond='data:blog.pageType == &quot;index&quot;'>
      <title>
        <data:blog.pageTitle/>
      </title>
      <b:else/>
      <title>
        <data:blog.pageName/>
        - 
        <data:blog.title/>
      </title>
    </b:if>
    <meta content='Your Keywords Here' name='keywords'/>
    <b:skin><![CDATA[
      
/*
-----------------------------------------------
Blogger Template Style
Name:   Active Mag
Designer Url - http://www.favoritebtemplates.com - http://themeforest.net/user/fbtemplates/portfolio
----------------------------------------------- */
html, body, div, span, applet, object, iframe, h1, h2, h3, h4, h5, h6, p, blockquote, pre, a, abbr, acronym, address, big, cite, code, del, dfn, em, img, ins, kbd, q, s, samp, small, strike, strong, sub, sup, tt, var, b, u, i, center, dl, dt, dd, ol, ul, li, fieldset, form, label, legend, table, caption, tbody, tfoot, thead, tr, th, td, article, aside, canvas, details, embed, figure, figcaption, footer, header, hgroup, menu, nav, output, ruby, section, summary, time, mark, audio, video {
border: 0;
padding:0;
font-size: 100%;
font: inherit;
vertical-align: baseline;
}
article, aside, details, figcaption, figure, footer, header, hgroup, menu, nav, section { display: block }
ol, ul { list-style: none }
blockquote, q { quotes: none }
blockquote:before, q:before {
content: '';
content: none;
}
article, aside, details, figcaption, figure, footer, header, hgroup, menu, nav, section { display: block }
.picfooter ol, .picfooter ul { list-style: none }
blockquote, q { quotes: none }
blockquote:before, q:before {
content: '';
content: none;
}
table {
border-collapse: collapse;
border-spacing: 0;
}
:focus { outline: 0 }
a:link { -webkit-tap-highlight-color: #FF5E99 }
video, object, embed {
max-width: 100%;
height: auto!important;
}
iframe { max-width: 99% }
blockquote {
width: 93%;
font-style: italic;
font-weight: normal;
font-family: Georgia,Serif;
font-size: 13px;
padding: 15px 10px 20px 27px;
position: relative;
margin-top: 25px;
margin-bottom: 10px;
background: #f0f0f0;
text-align: center;
}
blockquote:before {
position: absolute;
content: '"';
font-size: 40px;
width: 50px;
left: -5px;
font-family: arial;
}
blockquote p { margin-bottom: 10px }
strong, b { font-weight: bold }
em, i, cite {
font-style: italic;
font-family: georgia;
}
small { font-size: 100% }
figure { margin: 10px 0 }
code, pre {
font-family: monospace,consolas,sans-serif;
font-weight: normal;
font-style: normal;
}
pre {
margin: 5px 0 20px 0;
line-height: 1.3em;
padding: 8px 10px;
overflow: auto;
}
code {
padding: 0 8px;
line-height: 1.5;
}
mark {
padding: 1px 6px;
margin: 0 2px;
color: black;
background: #FFD700;
}
address { margin: 10px 0 }
.item-thumbnail img{
max-width: 9999px
}
.widget,.section {
padding:0;
margin:0
}
.item-thumbnail  {
overflow: hidden;
display: block;
}
.item .widget  {
overflow: hidden;
display: block;
}
.Attribution {
display: none
}
.navbar .widget {
display: none! important
}
body#layout #box {
overflow:visible;
float:left;
width:390px;
}
body#layout #box1{
overflow:visible;
float:right;
width:390px;
}
body#layout #box3{
overflow:visible;
float:left;
width:250px;
}
body#layout .bigslider{
overflow:visible;
float:right;
width:590px;
}
/* Use this with templates/template-twocol.html */
body, .body-fauxcolumn-outer {
background-image: url(http://2.bp.blogspot.com/-DCUEhIyNw7c/Uv8TB3HHkUI/AAAAAAAAFhg/SxcjuVzOjD0/s1600/pattern_bg.png);
margin:0;
color:#777;
}
a {
color:#222;
text-decoration:none;
}
a:link {
color:#222;
text-decoration:none;
}
a:hover {
color:#000;
text-decoration:none;
}
#header-wrapper {
width:1180px;
height:120px;
background-color: rgb(37, 37, 37);
margin:0 auto;
}
#header-inner {
background-position: center;
margin-left: auto;
margin-right: auto;
}
#header {
margin: 5px;
float:left;
width:400px;
text-align:left;
}
#header2 {
float:right;
width:470px;
padding:30px 30px 12px 0;
text-align:left;
}
#header h1 {
margin:5px 5px 0;
padding:10px 20px 5px 18px;
text-transform:none;
font-family: 'Bree Serif', sans-serif;
color: #999;
font-size:40px;
font-weight:normal
}
#header a {
color:#999;
text-decoration:none;
}
#header a:hover {
color:#777;
}
#header .description {
margin:-10px 0 0 23px;
padding:0;
max-width:400px;
text-transform:none;
line-height: .4em;
font:normal 13px Oswald;
color: #999;
}
#header img {
margin-left: auto;
margin-right: auto;
}
#outer-wrapper {
width: 1140px;
background:#fff;
margin:0 auto;
padding:5px 20px 15px 20px;
text-align:left;
font:normal 14px Arial;
}
#box3{
max-width:180px;
float:left;
}
#main-wrapper {
width: 820px;
float: left;
word-wrap: break-word;
overflow: hidden;
}
#sidebar-wrapper {
width: 300px;
float: right;
word-wrap: break-word;
}
h2.date-header {
display:none;
}
.post {
margin:0 0 20px 0;
font-size:15px;
font-family:Open Sans;
color:#393939;
}
.post h2 {
margin:15px 0 10px 0;
padding:0 0 4px;
font:lighter 39px Kreon;
line-height:1.4em;
color:#333;
}
.post h2 a, .post h2 a:visited, .post h2 strong {
display:block;
text-decoration:none;
font-weight:normal;
}
.post-body {
}
.post-body blockquote {
line-height:1.3em;
}
.post-footer {
}
.comment-link {
}
.post img, table.tr-caption-container {
margin: 0 0 20px;
}
.tr-caption-container img {
border: none;
padding: 0;
}
.post blockquote {
}
.post blockquote p {
}
.post-meta{ 
padding-bottom:9px; 
padding-top: 9px; 
font-family: 'Kreon', Arial, sans-serif; 
font-weight: lighter; 
font-size: 16px; 
color: #000; 
border-top: 1px solid #ddd; 
border-bottom: 1px solid #ddd; 
margin-bottom: 20px; 
}
.post-meta a{ 
color: #000; 
text-decoration: none; 
}
.post-meta a:hover { 
color: #111; 
}
.showpageOf {
display: none;
}
.showpagePoint {
padding: 10px 14px;
background: #222;
float: left;
color: #fff;
font-size: 14px;
font-weight: bold;
}
.showpage a, .showpageNum a {
padding: 10px 14px;
background: #ff9900;
float: left;
color: #fff;
font-size: 14px;
font-weight: bold;
text-decoration: none;
}
.showpage a:hover {
background: #222;
color:#fff
}
.showpageNum a:hover {
background: #222;
color:#fff
}
.showpageArea {
text-align:center;
}
#comments{
font-size:13px;
background: #efefef;
margin:0;
padding:15px;
}
#comments h4{display:inline;padding:10px;line-height:40px}
#comments h4,.comments .comment-header,.comments .comment-thread.inline-thread .comment{position:relative}
#comments h4,.comments .continue a{background:#333}
#comments h4,.comments .user a,.comments .continue a{font-size:16px}
#comments h4,.comments .continue a{font-weight:normal;color:#fff}
#comments h4:after{content:"";position:absolute;bottom:-10px;left:10px;border-top:10px solid #333;border-right:20px solid transparent;width:0;height:0;line-height:0}
#comments .avatar-image-container img{border:0}
.comment-thread{color:#111}
.comment-thread a{color:#777}
.comment-thread ol{margin:0 0 20px}
.comment-thread .comment-content a,.comments .user a,.comments .comment-thread.inline-thread .user a{color:#E74C3C}
.comments .avatar-image-container,.comments .avatar-image-container img{
width:48px;
max-width:48px;
height:48px;
max-height:48px
}
.comments .comment-block,.comments .comments-content .comment-replies,.comments .comment-replybox-single{
margin-left:60px
}
.comments .comment-block,.comments .comment-thread.inline-thread .comment{
border:1px solid #ddd;
background:#fff;
padding:10px
}
.comments .comments-content .comment{
margin:15px 0 0;
padding:0;
width:100%;
line-height:1em
}
.comments .comments-content .icon.blog-author{
position:absolute;
top:-12px;
right:-12px;
margin:0;
background-image: url(http://3.bp.blogspot.com/-L40LQSkg1qY/UelHlVcMJzI/AAAAAAAAEn0/DhSUnAzEE4c/s1600/author.png);
width:36px;
height:36px
}
.comments .comments-content .inline-thread{padding:0 0 0 20px}
.comments .comments-content .comment-replies{margin-top:0}
.comments .comment-content{padding:5px 0;line-height:1.4em}
.comments .comment-thread.inline-thread{
border-left:1px solid #ddd;
background:transparent
}
.comments .comment-thread.inline-thread .comment{width:auto}
.comments .comment-thread.inline-thread .comment:after{
content:"";
position:absolute;
top:10px;
left:-20px;
border-top:1px solid #ddd;
width:10px;height:0px
}
.comments .comment-thread.inline-thread .comment .comment-block{
border:0;
background:transparent;
padding:0
}
.comments .comment-thread.inline-thread .comment-block{margin-left:48px}
.comments .comment-thread.inline-thread .user a{font-size:13px}
.comments .comment-thread.inline-thread .avatar-image-container,.comments .comment-thread.inline-thread .avatar-image-container img{
width:36px;
max-width:36px;
height:36px;
max-height:36px
}
.comments .continue{border-top:0;width:100%}
.comments .continue a{padding:10px 0;text-align:center}
.comment .continue{display:none}
#comment-editor{width:103%!important}
.comment-form{width:100%;max-width:100%}
.comments .comments-content .loadmore,.comments .comments-content {margin:0}
#blog-pager-newer-link {
float: left;
}
#blog-pager-older-link {
float: right;
}
#blog-pager {
text-align: center;
padding-top:20px;
margin-bottom:-25px;
}
.feed-links {
display:none;
}
.sidebar {
line-height: 1.3em;
}
.sidebar h2 {
background: #151515;
border-bottom:5px solid #ff9900;
padding:12px 0;
font:normal normal 18px Oswald;
text-transform: uppercase;
text-align:center;
font-weight: normal;
font-size: 18px;
color:#fff;
}
.sidebar ul {
padding: 0;
margin: 0;
list-style: none;
}
.sidebar li {
display:block;
}
.sidebar .widget, .main .widget {
margin:0 0 1.5em;
padding:0 0 1.5em;
}
.main .Blog {
border-bottom-width: 0;
}
.cloud-label-widget-content {
float:left;
margin-bottom:8px;
padding:10px 0px 0px 0px;
border:0;
}
.cloud-label-widget-content li, .cloud-label-widget-content a {
background:#151515;
border-bottom:2px solid #ff9900;
color:#FFFFFF;
float:left;
font-family: 'Open Sans', sans-serif;
font-size:13px !important;
margin:4px 4px 0 0;
padding:7px 7px;
text-decoration:none;
-webkit-transition:all 0.4s ease 0s;
-moz-transition:all 0.4s ease 0s;
-ms-transition:all 0.4s ease 0s;
-o-transition:all 0.4s ease 0s;
transition:all 0.4s ease 0s;
}
.cloud-label-widget-content a:hover {
background: #333;
border-bottom:2px solid #0099cc;
color:#fff;
}
.status-msg-wrap{
display:none;
}
.BlogArchive #ArchiveList ul li{
list-style: none;
display: block;
padding: 5px 0 5px 15px;
text-decoration: none;
text-shadow: -1px -1px 0 #EEEEEE;
}
#BlogArchive1_ArchiveMenu {
width: 100%;
border: 1px solid #ddd;
background: #eee;
padding: 10px;
}
.FollowByEmail .follow-by-email-inner {
position: relative;
margin-top:10px;
}
.follow-by-email-inner:before {
content: &quot;Enter Your Email and Join Our Email Subscriber List, Its Spam Free Secuer Email System&quot;;
font-size: 13px;
}
.button:hover,a.button:hover,#main-content input[type=&quot;submit&quot;]:hover{background:#444!important;text-decoration:none!important}
.FollowByEmail .follow-by-email-inner .follow-by-email-address {
border: 1px solid #ddd;
border-radius: 0;
font-size: 13px;
height: 35px;
padding-left: 10px;
width: 95%
}
.FollowByEmail .follow-by-email-inner .follow-by-email-submit {
background: #d01f3c;
border: 0 none;
border-radius: 0;
color: #FFF;
cursor: pointer;
font-size: 13px;
height: 38px;
margin: 5px 3px;
width: 70px;
z-index: 0;
}
.FollowByEmail .follow-by-email-inner .follow-by-email-submit:hover {
background: #333333;
}
.container {
background-color: #151515;
border-top:5px solid #ff9900;
width: 1180px;
overflow:hidden;
margin: 0 auto;
}
footer p { color: #fff }
.footer-widgets {
overflow: hidden;
padding: 20px 2.8% 10px 3.1%;
width: 94.6%;
margin: 0;
}
.footer-widgets ul li a {
color:#fff;
font-family: Open Sans;
font-size:13px;
font-style:italic;
}
.footer-widgets h2 {
background:none;
color:#999;
font-size:17px;
letter-spacing: 1px;
font-weight:400;
font-family: Oswald;
text-transform: uppercase;
margin-bottom: 16px;
}
.footer-widgets ul li a:visited {
color:#fff;
}
.f-widget {
width: 23%;
float: left;
position: relative;
color: #fff;
font-family: Oswald;
font-size:13px;
margin-bottom: 30px;
margin-right: 2.5%;
border-right:1px solid #292929;
padding-bottom:20px;
}
.footer-widgets .last {
float: left;
position: relative;
margin-right: 0;
border:none;
overflow:hidden;
}
.footer-widgets .last .widget a {
color:#fff;
}
.social-icons{
text-align:center;
}
.social-icons a{
position:relative;
margin:0; 
opacity:.7;
}
.social-icons a:hover{ opacity:1;}
.social-icons.icon_24 img{
width:24px; 
height:24px;
}
.social-icons.icon_16 img{
width:16px; 
height:16px;
}
.social-icons.icon_flat{
float:left; 
margin:4px 0 0 0;
}
.social-icons.icon_flat a{
background:url(http://1.bp.blogspot.com/-YfwvUwnNgLA/Uv8TBoTlrCI/AAAAAAAAFhY/8XXssXTvk7c/s1600/social-icons.png) no-repeat top left; 
width: 20px;
height: 20px; 
opacity:.3;
}
.social-icons.icon_flat a:hover{ opacity:.6;}
.icon_flat a.google-tieicon{background-position:-38px 1px;}
.icon_flat a.facebook-tieicon{background-position:left 0;}
.icon_flat a.twitter-tieicon{background-position:-76px 1px;}
.icon_flat a.youtube-tieicon{background-position:-38px -82px;}
.icon_flat a.dribbble-tieicon{background-position:-121px -82px;}
.icon_flat a.rss-tieicon{background-position:left -123px;}
.icon_flat a.pinterest-tieicon{background-position:-76px -123px;}
.icon_flat a.instagram-tieicon{background-position:left -209px;}
a.ttip, a.tooldown{display:inline-block;}
.contact-form-button{
border-radius:3x !important;
width:95%;
margin-top:10px;
}
.contact-form-name,.contact-form-email,.contact-form-email-message{
max-width:95%;
margin-bottom:5px;
color:#333;
}
.contact-form-email:hover,.contact-form-name:hover,.contact-form-email-message:hover{
box-shadow:none
}
input:focus,.contact-form-email-message{
box-shadow:none
}
.contact-form-email-message{
border:none !important;
border-top:0px;
border:0px
}
.contact-form-email, .contact-form-name{
border:none;
background:#fff;
border:none !important;
padding:5px;
}
.contact-form-name, .contact-form-email, .contact-form-email-message{
background:#fff;
padding:5px;
}
.contact-form-button-submit{
background:#ff9900;
background-color:#ff9900!important;
border:none !important;
box-shadow:none !important;
border-radius:none !important
}
#credit{
width: 1180px;
background:#252525;
border-top:1px solid #353535;
z-index:9999;
font-family: 'Open Sans', sans-serif;
font-size:14px;
color: #ddd;
overflow:hidden;
margin:0 auto;
clear:both;
padding:10px 0;
line-height:20px;
}
#credit .left{
float:left;
text-align:left;
margin-left:30px;
margin-top:5px;
}
#credit .right{
float:right;
text-align:right;
margin-right:30px;
}
#credit a{
color:#fff;
text-decoration:none;
}
#credit a:hover{
color:#fc0;
text-decoration:none
}
#PopularPosts1 img {
float:left;
margin:0 5px 0 0;
}
.item-thumbnail img {
width: 60px;
height: 60px;
}
#PopularPosts1 .item-title {
font: normal 15px Oswald;
}
#PopularPosts1 dd {
border-bottom: 1px solid #eee;
padding: 8px 0 4px;
}
#menu{
background: #151515;
border-top:1px solid #393939;
border-bottom:5px solid #ff9900;
color: #999;
height: 50px;
z-index:9;
width:1180px;
margin:0 auto;
}
#menu ul,#menu li{margin:0 auto;padding:0 0;list-style:none}
#menu ul{height:50px;width:1180px}
#menu li{float:left;display:inline;position:relative;font:normal 0.9em Oswald; text-transform:uppercase;}
#menu a{display: block;
line-height: 50px;
padding: 0 30px;
text-decoration: none;
color: #fff;
}
#menu li a:hover{
color: #fff;
background: #444;
}
li.home a{background:#444; color:#fff;}
#menu input{display:none;margin:0 0;padding:0 0;width:80px;height:30px;opacity:0;cursor:pointer}
#menu label{font:bold 30px Oswald;display:none;width:35px;height:36px;line-height:36px;text-align:center}
#menu label span{font-size:16px;position:absolute;left:35px}
#menu ul.menus{
height: auto;
overflow: hidden;
width: 190px;
background: #000;
position: absolute;
z-index: 99;
display: none;
}
#menu ul.menus li{
display: block;
width: 100%;
font:bold 12px Arial;
text-transform: none;
text-shadow: none;
}
#menu ul.menus a{
color: #FFF;
line-height: 35px;
}
#menu li:hover ul.menus{display:block}
#menu ul.menus a:hover{
background: #222;
color: #FFF;
-webkit-transition: all .1s ease-in-out;
-moz-transition: all .1s ease-in-out;
-ms-transition: all .1s ease-in-out;
-o-transition: all .1s ease-in-out;
transition: all .1s ease-in-out;
}
@media screen and (max-width: 800px){
#menu{position:relative}
#menu ul{background:#111;position:absolute;top:100%;right:0;left:0;z-index:3;height:auto;display:none}
#menu ul.menus{width:100%;position:static;padding-left:20px}
#menu li{display:block;float:none;width:auto; font:normal 0.8em Arial;}
#menu input,#menu label{position:absolute;top:0;left:0;display:block}
#menu input{z-index:4}
#menu input:checked + label{color:white}
#menu input:checked ~ ul{display:block}
}
.headline-wrapper{
background: #292929;
border-bottom:1px solid #393939;
width: 1180px;
height: 39px;
color:#fff;
margin:0 auto;
}
.headline{
width: 1180px;
line-height: 1.9em;
text-align: left;
font-family: 'Oswald', sans-serif;
font-weight: normal;
color: #111;
text-transform: none;
overflow: hidden;
clear: both;
margin: 0 auto;
padding: 10px auto
}
.headline a{
color: #fff;
font-size: 13px;
font-weight: normal;
text-decoration: none;
margin-left: 20px
}
.headline a:hover{
color: #fc0;
text-decoration: none
}
.headline-left{
float:left;
width:59%;
padding:2px 0;
position:relative;
overflow:hidden;
}
.part2 {
width:300px;
float:left;
margin-bottom:10px;
}
.part2 .opinion .cont h2{
color:#fff;
width:300px;
font-size:14px;
text-align:left;
padding:0 0;
overflow:hidden;
}
.part2 h2{
background: #151515;
border-bottom:5px solid #ff9900;
padding:12px 0;
font:normal normal 18px Oswald;
text-transform: uppercase;
text-align:center;
font-weight: normal;
font-size: 18px;
color:#fff;
}
.part2 .opinion .cont{
width:300px;
overflow:hidden;
}
.cont.topLists{
margin-top:0px;
}
.cont.topLists .topimages .images{ margin:10px 0;}
.toptext{ width:300px; text-align:left; }
.toptext a{ font:normal 18px Oswald, sans-serif; color:#555}
figure figcaption .toptext a span{font:normal 14px Oswald, Arial, sans-serif !important;}
.topimages{padding-bottom:4px; margin-bottom:0px;}
.topListimages{ height:160px; overflow:hidden; text-align:center; margin-bottom:10px;}
.topListimages a { display:block; margin:0 auto;}
.author{ margin-top:3px; text-align:center; font:10px Arial, Helvetica, sans-serif;}
.author a{color:#fff; font-weight:normal; font-style:italic;}
.author span{color:#9f9f9f;}
.topimages .author a{color:#0099ff;}
.cont.topLists figure{width:300px; float:left; position:relative;}
img.cover {
display:inline;
position:relative;
left:0;
top:9px;
right:0;
bottom:0;
opacity:1;
filter:progid:DXImageTransform.Microsoft.Alpha(Opacity=100);
-webkit-transition: all 0.3s ease-out;    /* Saf3.2+, Chrome */
-moz-transition: all 0.3s ease-out;  /* FF4+ */
-ms-transition: all 0.3s ease-out;  /* IE10 */
-o-transition: all 0.3s ease-out;  /* Opera 10.5+ */
transition: all 0.3s ease-out;
}
img.cover:hover {opacity:1;filter:progid:DXImageTransform.Microsoft.Alpha(Opacity=100);}
.latestpost{
font-family: Oswald;
font-size:18px;
text-transform:uppercase;
overflow:hidden;
color:#fff;
margin-bottom:9px;
}
.latestpost h4{
background:#151515;
border-bottom:5px solid #ff9900;
padding:12px 0;
text-align:center;
margin:0;
font-weight:normal;
}
.latestpost h4 a{
color:#fff;
}
#thumb-wrapper {
width: 820px;
overflow: hidden;
margin-bottom:15px;
}
#box {
width:400px;
float:left;
padding: 3px 5px 5px 0;
overflow:hidden
}
#box1 {
width:400px;
float: right;
padding: 3px 0px 5px 0px;
overflow: hidden;
}
.box .widget h1, .box1 .widget h1{
background:#151515;
border-bottom:5px solid #ff9900;
padding:12px 0;
text-align:center;
margin-bottom: 10px;
margin-left:0px;
position:relative;
color:#fff;
text-transform:uppercase;
font-size:18px;
font-family: Oswald;
font-weight: 400;
}
.box .widget, .box1 .widget, a {
color:#393939;
margin: 0 auto;
}
.mastoras{
width: 820px;
overflow:hidden;
margin:5px 0;
padding:0
}
.mastoras .left{
float:left;
font-size: 13px;
font-family:Open Sans;
padding:10px 0
}
.mastoras .right{
float:right;
font-size: 12px;
padding:10px 5px
}
.mastoras_wide{
width:400px
}
.mastoras_wide .thumb{
padding-bottom:-25px;
width:400px;
height:220px;min-height:220px;
overflow:hidden;
}
.mastoras_wide img{
display:block;
width:400px;
}
.mastoras_narrow{
width:400px;
padding-bottom:6px
}
.mastoras_narrow .thumb{
float:left;
margin-right:7px;
margin-bottom: 5px;
height:80px;
overflow:hidden;
}
.mastoras_narrow .featuredTitle{
font:normal 16px Oswald;
color:#555
}
.mastoras_narrow .featuredTitle a:hover{
color:#000
}
.mastoras_wide .featuredPostMeta{
float:right
}
.mastoras h2 a,.mastoras h2 a:visited{
color:#333;
font-family: Oswald;
font-weight:400;
font-size: 23px;
}
.mastoras_narrow .featuredTitle a{
color:#555
}
.mastoras1{
width: 400px;
overflow:hidden;
margin: 0;
padding:0
}
.mastoras1 .left{
float:none;
font-size: 13px;
font-family:Open Sans;
padding:10px 0
}
.mastoras1 .right{
float:none;
font-size: 12px;
padding: 0px
}
.mastoras1_wide{
width:400px;
}
.mastoras1_wide .thumb{
padding-bottom:5px;
}
.mastoras1_wide img{
display:block
}
.mastoras1_narrow{
width:390px;
padding-bottom:6px
}
.mastoras1_narrow .thumb{
float:left;
margin-right:7px;
}
.mastoras1_narrow .featuredTitle{
font:normal 16px Oswald;
color:#333
}
.mastoras1_narrow .featuredTitle a:hover{
color:#000
}
.mastoras1_wide .featuredPostMeta{
float:left;
}
.mastoras1 h2 a,.mastoras1 h2 a:visited{
color:#333;
font-family: Oswald;
font-weight:300;
font-size: 23px;
}
.mastoras1_narrow .featuredTitle a{
color:#555
}
.news_pictures {
margin-bottom:20px;
}
.news_pictures .news_pictures_list {
overflow: hidden;
margin-right:-13px;
}
.news_pictures .news_pictures_list li {
float: left;
margin-right: 9px;
margin-bottom: 9px;width:268px; height:160px;
list-style:none;
overflow:hidden;
}
.news_pictures .news_pictures_list li a {
display: block;
}
.news_pictures .news_pictures_list li img {
padding: 0px;
border: 0px solid #eee;
}
.news_pictures .news_pictures_list li img {
width:267px; height:auto; min-height:160px;
}
.box6{
width: 820px;
}
.box6 h1{
background:#151515;
border-bottom:5px solid #ff9900;
padding:12px 0;
text-align:center;
font-family: Oswald;
font-weight: 300;
font-size:18px;
text-transform: uppercase;
color: #fff;
}
#carousel {
width: 820px; 
position: relative; 
margin: 0 auto;
height:270px;
}
#carousel .content {
position: relative;
left: 0px;
width: 820px;
overflow:hidden;
}
.crosscol h1{
background:#151515;
border-bottom:5px solid #ff9900;
padding:12px 0;
text-align:center;
font-family: Oswald;
font-weight: 300;
font-size:18px;
text-transform: uppercase;
color: #fff;
margin-bottom:20px;
}
#carousel ul{
width:10000px;
position: relative;
overflow:hidden;
margin-top:0px;
}
#carousel ul li {
display: block; 
float: left; 
margin:0;
margin-right:12px;  
width: 265px; 
overflow: hidden;
height:155px;
}
#carousel .thumb{
height:80px;
width: 236px;
}
#carousel  #previous_button { 
position: absolute;  
bottom:102px;
left: 10px;
width: 40px;
height: 40px;
cursor: pointer;
background: url(http://2.bp.blogspot.com/-bcayzZsNafc/UvzIUZZ3sjI/AAAAAAAAFhA/MStBJy3TXe8/s1600/slider_direction.png) no-repeat; 
z-index:999;
}
#carousel #next_button { 
position: absolute; 
bottom:102px; 
right:10px; 
width: 40px; 
height: 40px; 
cursor: pointer; 
background: url(http://2.bp.blogspot.com/-bcayzZsNafc/UvzIUZZ3sjI/AAAAAAAAFhA/MStBJy3TXe8/s1600/slider_direction.png) no-repeat; 
background-position:100% 0;
z-index:999; 
}
#carousel #next_button:hover, #previous_button:hover { 
-ms-filter: "progid: DXImageTransform.Microsoft.Alpha(Opacity=80)"; 
filter: alpha(opacity=80); 
opacity: 0.8; 
transition: opacity .25s ease-in-out; 
-moz-transition: opacity .25s ease-in-out; 
-webkit-transition: opacity .25s ease-in-out; 
}
#carousel ul li a.slider_title{
background:#111;opacity:0.7;filter:alpha(opacity = 70);padding:3px 8px;overflow:hidden;
color:#fff;
float:left;
height:50px;
width:220px;
text-align:left;
font:normal 14px Oswald;
margin-top:27px;
width:100%;
}
#carousel ul li a.slider_title:hover{
color:#fc0;
}
.lb-overlay-wrapper {
background: #f8f9f5;
border: 5px solid #f4f5f1;
border-radius: 5px;
margin-bottom: 30px;
position: relative;
text-align: center;
}
.error-404-title {
font-family: 'Bree Serif', sans-serif;
font-weight: normal;
font-size: 60px;
color: #4d4d4d;
text-align: center;
padding: 30px 0px 38px 0px ;
/* responsive phone */
}
@media (max-width: 767px) {
.error-404-title {
font-size: 30px;
line-height: 40px;
}
}
.error-404-sub-title {
font-family: 'Bree Serif', sans-serif;
font-weight: lighter;
font-size: 24px;
line-height: 30px;
color: #a6a6a6;
text-align: center;
padding: 0 0 40px 0;
}
.error-404-sub-sub-title {
text-align: center;
margin-bottom: 70px;
}
.error-404-sub-sub-title a {
color: white;
padding: 7px 14px 8px 14px;
margin-left: 10px;
background-color: #4db2ec;
}
.error-404-sub-sub-title a:hover {
color: white;
background-color: #555555;
text-decoration: none !important;
}
.error-404-head {
text-align: center;
}
.block-grid-1{
font-size:13px;
color:#333;
font-family:Oswald;
margin-top:10px;
padding-top:15px;
list-style:none;
}
#related-posts{
float:left;
width:auto;
margin-bottom:40px;
}
#related-posts h5{
font:18px Oswald;
background-repeat;no-repeat;
color: #fff;
font-weight: normal;
background-color: #ff9900;
text-align: center;
padding: 12px 0;
margin-bottom:5px;
}
#related-posts .related_img {
padding:0px;
width:195px;
height:120px;
}
#related-posts .related_img:hover{
opacity:.7;
filter:alpha(opacity=70);
-moz-opacity:.7;
-khtml-opacity:.7;
}
.box3{
width:180px;
}
.box3 h2{
background: #151515;
border-bottom:5px solid #ff9900;
padding:12px 0;
margin-bottom:-10px;
font:normal normal 18px Oswald;
text-transform: uppercase;
text-align:center;
font-weight: normal;
font-size: 18px;
color:#fff;
}
.block-grid-1{
font-size:14px;
color:#333;
font-family:Oswald;
margin-top:0;
padding-top:5px;
list-style:none;
}
.bigslider{
width:620px;
float:right;
margin-top:1px;
}
@media screen and (max-width:1024px) {
#header-wrapper {
max-width:860px;
height:auto;
}
#header, #header .description{
float:none;
text-align:center;
margin:0 auto;
}
#header2{
max-width:100%;
text-align:center;
float:none;
margin:0 auto;
padding:10px 0;
}
#header h1{
margin:0;
padding:0;
}
.headline-wrapper, .headline{
max-width:860px;
}
.headline-left{
max-width:40%;
}
#menu, #menu ul{
max-width:860px;
}
#carousel, #carousel .content{
max-width:860px;
margin: 0 auto;
}
#outer-wrapper {
max-width: 820px;
margim-bottom:40px;
}
#sidebar-wrapper{
width:100%;max-width:100%;
float:left;
}
.container, #credit {
max-width:860px;
}
.part2 {
width:100%;
}
.part2 .opinion .cont{
margin:0 auto;
}
}
@media only screen and (max-width:768px){
#header-wrapper {
max-width:660px;
height:auto;
}
#header, #header .description{
float:none;
text-align:center;
margin:0 auto;
}
#header2{
max-width:100%;
text-align:center;
float:none;
margin:0 auto;
padding:10px 0;
}
.headline-wrapper, .headline{
max-width:660px;
}
.headline-left{
max-width:38%;
}
#menu, #menu ul{
max-width:660px;
}
#outer-wrapper {
max-width: 620px;
}
#main-wrapper{
width:100%;
}
.post img{
width:100%;
height:auto;
float:left;
}
.container, #credit {
max-width:660px;
}
#box3, #carousel{
display:none;
}
.bigslider{
float:left;
}
#thumb-wrapper, #box6{
width:400px;
margin:0 auto;
}
#box, #box1{
float:none;
margin:0 auto;
}
.mastoras{
width:400px;
margin:0 auto;
}
}
@media only screen and (max-width:600px){
#header-wrapper {
max-width:500px;
height:auto;
}
#header, #header .description{
float:none;
text-align:center;
margin:0 auto;
}
#header2{
max-width:100%;
text-align:center;
float:none;
margin:0 auto;
padding:10px 0;
}
.headline-wrapper, .headline{
max-width:500px;
}
.headline-left{
max-width:100%;
}
#menu, #menu ul{
max-width:500px;
}
#outer-wrapper {
max-width: 460px;
}
#main-wrapper{
float:left;
width:460px;max-width:460px;
padding:0;
margin:0;
}
#thumb-wrapper {
max-width:400px;
margin:0 auto;
}
.container, #credit {
max-width:500px;
}
.search-block{
display:none;
}
.bigslider{
float:left;
width:460px;
}
#box, #box1{
float:none;
margin:0 auto;
}
.box6{
width:400px;max-width:400px;
}
.mastoras{
max-width:400px;
}
.footer-widgets .last {
width:20%;
}
#credit .left, #credit .right{
width:100%;
float:none;
text-align:center;
padding:0;
margin:0 auto;
}
.social-icons.icon_flat{
float:none;
text-align:center;
}
}
@media screen and (max-width:480px){
#header-wrapper {
max-width:400px;
height:auto;
}
#header{
padding-bottom:15px;
}
#header2{
display:none;
}
.headline-wrapper, .headline{
max-width:400px;
}
.headline-left{
max-width:50%;
}
#menu, #menu ul{
max-width:400px;
}
#outer-wrapper {
max-width: 360px;
}
#main-wrapper{
float:left;
width:360px;max-width:360px;
padding:0;
margin:0;
}
.bigslider{
width:360px;
}
#thumb-wrapper {
max-width:360px;
margin:0 auto;
}
.mastoras_wide, .mastoras1_wide, .mastoras1_narrow{
width:360px;
float:none;
}
.mastoras_narrow{
display:none;
}
.container, #credit {
max-width:400px;
}
.box6{
width:360px;max-width:360px;
float:left;
}
}
@media screen and (max-width:384px){
#header-wrapper {
max-width:350px;
height:auto;
}
#header{
max-width:350px;
}
#header h1 {
font-size:30px;
}
#header .description {
}
.headline-wrapper, .headline{
max-width:350px;
}
.headline-left{
max-width:30%;
}
#menu, #menu ul{
max-width:350px;
}
#outer-wrapper {
max-width: 310px;
}
#main-wrapper{
float:left;
width:310px;max-width:310px;
padding:0;
margin:0;
}
#box, #box1{
width:300px;
}
.mastoras_wide, .mastoras1_wide, .mastoras1_narrow{
width:300px;
float:none;
}
#thumb-wrapper {
max-width:310px;
margin:0 auto;
}
.container, #credit {
max-width:350px;
}
.footer-widgets h2 {
font-size:12px;
}
.box6{
width:350px;max-width:350px;
float:left;
}
}

    ]]></b:skin>
    <style>
      .search-block {
        height:40px;
        overflow: hidden;
        float:right;
        position:relative;
        top:0;
        right:0;
      }
      .search-block:after{
        display: block;
        width: 0;
        height: 0;
        position: absolute;
        z-index: 2;
      }
      .search-block #s {
        background:#555;
        float: right;
        font: normal 11px tahoma;
        padding: 11px 12px 11px 12px;
        width: 150px;
        height:16px;
        color:#fff;
        border:0 none;
      }
      .search-block #s:focus {
        color:#fff;
        width:150px;
      }
      .search-block .search-button {
        background:#111;
        cursor: pointer;
        float: right;
        color:#fff;
        height:38px;
        width:40px;
        display: block;
        border:0 none;
        font-family:Oswald;
      }
      .search-block:hover .search-button, .search-block:hover #s {
        opacity:1;
        color:#fff;
      }
    </style>
    <script src='//ajax.googleapis.com/ajax/libs/jquery/1.8.3/jquery.min.js'/>
    <script type='text/javascript'>
      //<![CDATA[
      /**
 * jCarouselLite - jQuery plugin to navigate images/any content in a carousel style widget.
 * @requires jQuery v1.2 or above
 *
 * http://gmarwaha.com/jquery/jcarousellite/
 *
 * Copyright (c) 2007 Ganeshji Marwaha (gmarwaha.com)
 * Dual licensed under the MIT and GPL licenses:
 * http://www.opensource.org/licenses/mit-license.php
 * http://www.gnu.org/licenses/gpl.html
 *
 * Version: 1.0.1
 * Note: Requires jquery 1.2 or above from version 1.0.1
 */
      (function($) {                                          // Compliant with jquery.noConflict()
        $.fn.jCarouselLite = function(o) {
          o = $.extend({
            btnPrev: null,
            btnNext: null,
            btnGo: null,
            mouseWheel: false,
            auto: null,
            speed: 200,
            easing: null,
            vertical: false,
            circular: true,
            visible: 3,
            start: 0,
            scroll: 1,
            beforeStart: null,
            afterEnd: null
          }, o || {});
          return this.each(function() {                           // Returns the element collection. Chainable.
            var running = false, animCss=o.vertical?"top":"left", sizeCss=o.vertical?"height":"width";
            var div = $(this), ul = $("ul", div), tLi = $("li", ul), tl = tLi.size(), v = o.visible;
            if(o.circular) {
              ul.prepend(tLi.slice(tl-v-1+1).clone())
              .append(tLi.slice(0,v).clone());
              o.start += v;
            }
            var li = $("li", ul), itemLength = li.size(), curr = o.start;
            div.css("visibility", "visible");
            li.css({overflow: "hidden", float: o.vertical ? "none" : "left"});
            ul.css({margin: "0", padding: "0", position: "relative", "list-style-type": "none", "z-index": "1"});
            div.css({overflow: "hidden", position: "relative", "z-index": "2", left: "0px"});
            var liSize = o.vertical ? height(li) : width(li);   // Full li size(incl margin)-Used for animation
            var ulSize = liSize * itemLength;                   // size of full ul(total length, not just for the visible items)
            var divSize = liSize * v;                           // size of entire div(total length for just the visible items)
            li.css({width: li.width(), height: li.height()});
            ul.css(sizeCss, ulSize+"px").css(animCss, -(curr*liSize));
            div.css(sizeCss, divSize+"px");                     // Width of the DIV. length of visible images
            if(o.btnPrev)
              $(o.btnPrev).click(function() {
                return go(curr-o.scroll);
              });
            if(o.btnNext)
              $(o.btnNext).click(function() {
                return go(curr+o.scroll);
              });
            if(o.btnGo)
              $.each(o.btnGo, function(i, val) {
                $(val).click(function() {
                  return go(o.circular ? o.visible+i : i);
                });
              });
            if(o.mouseWheel && div.mousewheel)
              div.mousewheel(function(e, d) {
                return d>0 ? go(curr-o.scroll) : go(curr+o.scroll);
              });
            if(o.auto)
              setInterval(function() {
                go(curr+o.scroll);
              }, o.auto+o.speed);
            function vis() {
              return li.slice(curr).slice(0,v);
            };
            function go(to) {
              if(!running) {
                if(o.beforeStart)
                  o.beforeStart.call(this, vis());
                if(o.circular) {            // If circular we are in first or last, then goto the other end
                  if(to<=o.start-v-1) {           // If first, then goto last
                    ul.css(animCss, -((itemLength-(v*2))*liSize)+"px");
                    // If "scroll" > 1, then the "to" might not be equal to the condition; it can be lesser depending on the number of elements.
                    curr = to==o.start-v-1 ? itemLength-(v*2)-1 : itemLength-(v*2)-o.scroll;
                  } else if(to>=itemLength-v+1) { // If last, then goto first
                    ul.css(animCss, -( (v) * liSize ) + "px" );
                    // If "scroll" > 1, then the "to" might not be equal to the condition; it can be greater depending on the number of elements.
                    curr = to==itemLength-v+1 ? v+1 : v+o.scroll;
                  } else curr = to;
                } else {                    // If non-circular and to points to first or last, we just return.
                  if(to<0 || to>itemLength-v) return;
                  else curr = to;
                }                           // If neither overrides it, the curr will still be "to" and we can proceed.
                running = true;
                ul.animate(
                  animCss == "left" ? { left: -(curr*liSize) } : { top: -(curr*liSize) } , o.speed, o.easing,
                  function() {
                    if(o.afterEnd)
                      o.afterEnd.call(this, vis());
                    running = false;
                  }
                );
                // Disable buttons when the carousel reaches the last/first, and enable when not
                if(!o.circular) {
                  $(o.btnPrev + "," + o.btnNext).removeClass("disabled");
                  $( (curr-o.scroll<0 && o.btnPrev)
                    ||
                    (curr+o.scroll > itemLength-v && o.btnNext)
                    ||
                    []
                   ).addClass("disabled");
                }
              }
              return false;
            };
          });
        };
        function css(el, prop) {
          return parseInt($.css(el[0], prop)) || 0;
        };
        function width(el) {
          return  el[0].offsetWidth + css(el, 'marginLeft') + css(el, 'marginRight');
        };
        function height(el) {
          return el[0].offsetHeight + css(el, 'marginTop') + css(el, 'marginBottom');
        };
      })(jQuery);
      //]]>
    </script>
    <script type='text/javascript'>
      //<![CDATA[
      var relatedTitles=new Array();var relatedTitlesNum=0;var relatedUrls=new Array();var thumburl=new Array();function related_results_labels_thumbs(json){for(var i=0;i<json.feed.entry.length;i++){var entry=json.feed.entry[i];relatedTitles[relatedTitlesNum]=entry.title.$t;try{thumburl[relatedTitlesNum]=entry.gform_foot.url}catch(error){s=entry.content.$t;a=s.indexOf("<img");b=s.indexOf("src=\"",a);c=s.indexOf("\"",b+5);d=s.substr(b+5,c-b-5);if((a!=-1)&&(b!=-1)&&(c!=-1)&&(d!="")){thumburl[relatedTitlesNum]=d}else thumburl[relatedTitlesNum]='http://3.bp.blogspot.com/-zP87C2q9yog/UVopoHY30SI/AAAAAAAAE5k/AIyPvrpGLn8/s1600/picture_not_available.png'}if(relatedTitles[relatedTitlesNum].length>35)relatedTitles[relatedTitlesNum]=relatedTitles[relatedTitlesNum].substring(0,35)+"...";for(var k=0;k<entry.link.length;k++){if(entry.link[k].rel=='alternate'){relatedUrls[relatedTitlesNum]=entry.link[k].href;relatedTitlesNum++}}}}function removeRelatedDuplicates_thumbs(){var tmp=new Array(0);var tmp2=new Array(0);var tmp3=new Array(0);for(var i=0;i<relatedUrls.length;i++){if(!contains_thumbs(tmp,relatedUrls[i])){tmp.length+=1;tmp[tmp.length-1]=relatedUrls[i];tmp2.length+=1;tmp3.length+=1;tmp2[tmp2.length-1]=relatedTitles[i];tmp3[tmp3.length-1]=thumburl[i]}}relatedTitles=tmp2;relatedUrls=tmp;thumburl=tmp3}function contains_thumbs(a,e){for(var j=0;j<a.length;j++)if(a[j]==e)return true;return false}function printRelatedLabels_thumbs(){for(var i=0;i<relatedUrls.length;i++){if((relatedUrls[i]==currentposturl)||(!(relatedTitles[i]))){relatedUrls.splice(i,1);relatedTitles.splice(i,1);thumburl.splice(i,1);i--}}var r=Math.floor((relatedTitles.length-1)*Math.random());var i=0;if(relatedTitles.length>0)document.write('<h1>'+relatedpoststitle+'</h1>');document.write('<div style="clear: both;"/>');while(i<relatedTitles.length&&i<20&&i<maxresults){document.write('<a style="text-decoration:none;margin:0 7px 0px 0;float:left;');if(i!=0)document.write('"');else document.write('"');document.write(' href="'+relatedUrls[r]+'"><img class="related_img" src="'+thumburl[r]+'"/><br/><div style="width:198px;padding:0 0px;color:#000;height:15px;text-align:left;margin:0px 0px; font:16px Kreon; font-weight:lighter; line-height:20px;">'+relatedTitles[r]+'</div></a>');if(r<relatedTitles.length-1){r++}else{r=0}i++}document.write('</div>');relatedUrls.splice(0,relatedUrls.length);thumburl.splice(0,thumburl.length);relatedTitles.splice(0,relatedTitles.length)}
      //]]>
    </script>
    <script type='text/javascript'>
      //<![CDATA[
      imgr=new Array();
      imgr[0]="http://3.bp.blogspot.com/-zP87C2q9yog/UVopoHY30SI/AAAAAAAAE5k/AIyPvrpGLn8/s1600/picture_not_available.png";
      showRandomImg=true;
      aBold=true;
      summaryPost=150;
      summaryPost1=0;
      summaryTitle=15;
      numposts=6;
      numposts1=6;
      numposts2=4;
      numposts3=6;
      numposts4=5;
      numposts5=12;
      numposts6=1;
      function removeHtmlTag(strx,chop){var s=strx.split("<");for(var i=0;i<s.length;i++){if(s[i].indexOf(">")!=-1){s[i]=s[i].substring(s[i].indexOf(">")+1,s[i].length)}}s=s.join("");s=s.substring(0,chop-1);return s}
      function recentarticles(json) {
        j = (showRandomImg) ? Math.floor((imgr.length+1)*Math.random()) : 0;
        img  = new Array();
        for (var i = 0; i < numposts; i++) {
          var entry = json.feed.entry[i];
          var posttitle = entry.title.$t;
          var pcm;
          var posturl;
          if (i == json.feed.entry.length) break;
          for (var k = 0; k < entry.link.length; k++) {
            if (entry.link[k].rel == 'alternate') {
              posturl = entry.link[k].href;
              break;
            }
          }
          for (var k = 0; k < entry.link.length; k++) {
            if (entry.link[k].rel == 'replies' && entry.link[k].type == 'text/html') {
              pcm = entry.link[k].title.split(" ")[0];
              break;
            }
          }
          if ("content" in entry) {
            var postcontent = entry.content.$t;}
          else
            if ("summary" in entry) {
              var postcontent = entry.summary.$t;}
            else var postcontent = "";
          postdate = entry.published.$t;
          if(j>imgr.length-1) j=0;
          img[i] = imgr[j];
          s = postcontent	; a = s.indexOf("<img"); b = s.indexOf("src=\"",a); c = s.indexOf("\"",b+5); d = s.substr(b+5,c-b-5);
          if((a!=-1)&&(b!=-1)&&(c!=-1)&&(d!="")) img[i] = d;
          //cmtext = (text != 'no') ? '<i><font color="'+acolor+'">('+pcm+' '+text+')</font></i>' : '';
          var month = [1,2,3,4,5,6,7,8,9,10,11,12];
          var month2 = ["Jan","Feb","Mar","Apr","May","Jun","Jul","Aug","Sep","Oct","Nov","Dec"];
          var day = postdate.split("-")[2].substring(0,2);
          var m = postdate.split("-")[1];
          var y = postdate.split("-")[0];
          for(var u2=0;u2<month.length;u2++){
            if(parseInt(m)==month[u2]) {
              m = month2[u2] ; break;
            }
          }
          var daystr = day+ ' ' + m + ' ' + y ;
          var trtd = '<li style="position:relative;"><div class="imgauto"><a href="'+posturl+'"><img  src="'+img[i]+'"/></a></div><h3><a href="'+posturl+'">'+posttitle+'</a><p>'+removeHtmlTag(postcontent,summaryPost)+'... </p></h3></li>';					 
          document.write(trtd);       
          j++;
        }
      }
      function recentarticles1(json) {
        j = (showRandomImg) ? Math.floor((imgr.length+1)*Math.random()) : 0;
        img  = new Array();
        for (var i = 0; i < numposts5; i++) {
          var entry = json.feed.entry[i];
          var posttitle = entry.title.$t;
          var pcm;
          var posturl;
          if (i == json.feed.entry.length) break;
          for (var k = 0; k < entry.link.length; k++) {
            if (entry.link[k].rel == 'alternate') {
              posturl = entry.link[k].href;
              break;
            }
          }
          for (var k = 0; k < entry.link.length; k++) {
            if (entry.link[k].rel == 'replies' && entry.link[k].type == 'text/html') {
              pcm = entry.link[k].title.split(" ")[0];
              break;
            }
          }
          if ("content" in entry) {
            var postcontent = entry.content.$t;}
          else
            if ("summary" in entry) {
              var postcontent = entry.summary.$t;}
            else var postcontent = "";
          postdate = entry.published.$t;
          if(j>imgr.length-1) j=0;
          img[i] = imgr[j];
          s = postcontent	; a = s.indexOf("<img"); b = s.indexOf("src=\"",a); c = s.indexOf("\"",b+5); d = s.substr(b+5,c-b-5);
          if((a!=-1)&&(b!=-1)&&(c!=-1)&&(d!="")) img[i] = d;
          //cmtext = (text != 'no') ? '<i><font color="'+acolor+'">('+pcm+' '+text+')</font></i>' : '';
          var month = [1,2,3,4,5,6,7,8,9,10,11,12];
          var month2 = ["Jan","Feb","Mar","Apr","May","Jun","Jul","Aug","Sep","Oct","Nov","Dec"];
          var day = postdate.split("-")[2].substring(0,2);
          var m = postdate.split("-")[1];
          var y = postdate.split("-")[0];
          for(var u2=0;u2<month.length;u2++){
            if(parseInt(m)==month[u2]) {
              m = month2[u2] ; break;
            }
          }
          var daystr = day+ ' ' + m + ' ' + y ;
          var trtd = '<li class="car"><div class="thumb"><a href="'+posturl+'"><img width="276" min-height="130" class="Thumbnail thumbnail carousel " src="'+img[i]+'"/></a></div><a class="slider_title" href="'+posturl+'">'+posttitle+'</a></li>';
          document.write(trtd);
          j++;
        }
      }
      function recentarticles2(json){
        j=(showRandomImg)?Math.floor((imgr.length+1)*Math.random()):0;
        img=new Array();
        if(numposts1<=json.feed.entry.length){maxpost=numposts}else{maxpost=json.feed.entry.length}for(var i=0;
                                                                                                       i<maxpost;i++){var entry=json.feed.entry[i];
                                                                                                                      var posttitle=entry.title.$t;
                                                                                                                      var pcm;
                                                                                                                      var posturl;
                                                                                                                      if(i==json.feed.entry.length)break;
                                                                                                                      for(var k=0;k<entry.link.length;k++){if(entry.link[k].rel=='alternate'){posturl=entry.link[k].href;
                                                                                                                                                                                              break
                                                                                                                                                                                             }
                                                                                                                                                          }
                                                                                                                      for(var k=0;
                                                                                                                          k<entry.link.length;
                                                                                                                          k++){if(entry.link[k].rel=='replies'&&entry.link[k].type=='text/html'){pcm=entry.link[k].title.split(" ")[0];
                                                                                                                                                                                                 break
                                                                                                                                                                                                }
                                                                                                                              }
                                                                                                                      if("content"in entry){var postcontent=entry.content.$t}
                                                                                                                      else 
                                                                                                                        if("summary"in entry){var postcontent=entry.summary.$t}else var postcontent="";
                                                                                                                      postdate=entry.published.$t;
                                                                                                                      if(j>imgr.length-1)j=0;
                                                                                                                      img[i]="";
                                                                                                                      s=postcontent;
                                                                                                                      a=s.indexOf("<img");
                                                                                                                      b=s.indexOf("src=\"",a);
                                                                                                                      c=s.indexOf("\"",b+5);
                                                                                                                      d=s.substr(b+5,c-b-5);
                                                                                                                      if((a!=-1)&&(b!=-1)&&(c!=-1)&&(d!="")){if(i==0){img[i]='<img min-width="620" min-height="240" class="alignone" src="'+d+'"/>'}else{img[i]='<img class="alignright" min-height="100" src="'+d+'" width="150"/>'}}var month=[1,2,3,4,5,6,7,8,9,10,11,12];var month2=["Jan","Feb","Mar","Apr","May","Jun","Jul","Aug","Sep","Oct","Nov","Dec"];
                                                                                                                      var day=postdate.split("-")[2].substring(0,2);
                                                                                                                      var m=postdate.split("-")[1];
                                                                                                                      var y=postdate.split("-")[0];
                                                                                                                      for(var u2=0;u2<month.length;
                                                                                                                          u2++){if(parseInt(m)==month[u2]){m=month2[u2];
                                                                                                                                                           break}}var daystr=day+' '+m+' '+y;
                                                                                                                      if(i==0){var trtd='<div class="mastoras_wide left"><div class="thumb"><a href="'+posturl+'">'+img[i]+'</a></div><div class="featuredPost lastPost"><h2 class="postTitle"><a href="'+posturl+'">'+posttitle+'</a></h2>	<p>'+removeHtmlTag(postcontent,summaryPost)+'...</p><div class="clear"></div><span class="featuredPostMeta"><a href="'+posturl+'"></a></span></div></div><div class="mastoras_narrow right">';
                                                                                                                               document.write(trtd)}if((i>0)&&(i<maxpost)){var trtd='<div class="mastoras_narrow"><div class="thumb"><a href="'+posturl+'">'+img[i]+'</a></div><div class="featuredTitle"><a href="'+posturl+'">'+posttitle+'</a></div>'+removeHtmlTag(postcontent,summaryPost1)+'<div class="clear"></div></div>';
                                                                                                                                                                           document.write(trtd)}j++}document.write('</div>')}
      function recentarticles4(json) {
        j = (showRandomImg) ? Math.floor((imgr.length+1)*Math.random()) : 0;
        img  = new Array();
        for (var i = 0; i < numposts; i++) {
          var entry = json.feed.entry[i];
          var posttitle = entry.title.$t;
          var pcm;
          var posturl;
          if (i == json.feed.entry.length) break;
          for (var k = 0; k < entry.link.length; k++) {
            if (entry.link[k].rel == 'alternate') {
              posturl = entry.link[k].href;
              break;
            }
          }
          for (var k = 0; k < entry.link.length; k++) {
            if (entry.link[k].rel == 'replies' && entry.link[k].type == 'text/html') {
              pcm = entry.link[k].title.split(" ")[0];
              break;
            }
          }
          if ("content" in entry) {
            var postcontent = entry.content.$t;}
          else
            if ("summary" in entry) {
              var postcontent = entry.summary.$t;}
            else var postcontent = "";
          postdate = entry.published.$t;
          if(j>imgr.length-1) j=0;
          img[i] = imgr[j];
          s = postcontent	; a = s.indexOf("<img"); b = s.indexOf("src=\"",a); c = s.indexOf("\"",b+5); d = s.substr(b+5,c-b-5);
          if((a!=-1)&&(b!=-1)&&(c!=-1)&&(d!="")) img[i] = d;
          //cmtext = (text != 'no') ? '<i><font color="'+acolor+'">('+pcm+' '+text+')</font></i>' : '';
          var month = [1,2,3,4,5,6,7,8,9,10,11,12];
          var month2 = ["January","February","March","April","May","June","July","August","September","October","November","December"];
          var day = postdate.split("-")[2].substring(0,2);
          var m = postdate.split("-")[1];
          var y = postdate.split("-")[0];
          for(var u2=0;u2<month.length;u2++){
            if(parseInt(m)==month[u2]) {
              m = month2[u2] ; break;
            }
          }
          var daystr = m+ ' ' + day + ' ' + y ;
          var trtd = '<a href="'+posturl+'"><span>&#187; </span>'+posttitle+'</a>';					 
          document.write(trtd);       
          j++;
        }
      }
      function recentarticles6(json) {
        j = (showRandomImg) ? Math.floor((imgr.length+1)*Math.random()) : 0;
        img  = new Array();
        for (var i = 0; i < numposts2 ; i++) {
          var entry = json.feed.entry[i];
          var posttitle = entry.title.$t;
          var pcm;
          var posturl;
          if (i == json.feed.entry.length) break;
          for (var k = 0; k < entry.link.length; k++) {
            if (entry.link[k].rel == 'alternate') {
              posturl = entry.link[k].href;
              break;
            }
          }
          for (var k = 0; k < entry.link.length; k++) {
            if (entry.link[k].rel == 'replies' && entry.link[k].type == 'text/html') {
              pcm = entry.link[k].title.split(" ")[0];
              break;
            }
          }
          if ("content" in entry) {
            var postcontent = entry.content.$t;}
          else
            if ("summary" in entry) {
              var postcontent = entry.summary.$t;}
            else var postcontent = "";
          postdate = entry.published.$t;
          if(j>imgr.length-1) j=0;
          img[i] = imgr[j];
          s = postcontent	; a = s.indexOf("<img"); b = s.indexOf("src=\"",a); c = s.indexOf("\"",b+5); d = s.substr(b+5,c-b-5);
          if((a!=-1)&&(b!=-1)&&(c!=-1)&&(d!="")) img[i] = d;
          //cmtext = (text != 'no') ? '<i><font color="'+acolor+'">('+pcm+' '+text+')</font></i>' : '';
          var month = [1,2,3,4,5,6,7,8,9,10,11,12];
          var month2 = ["Jan","Feb","Mar","Apr","May","Jun","Jul","Aug","Sep","Oct","Nov","Dec"];
          var day = postdate.split("-")[2].substring(0,2);
          var m = postdate.split("-")[1];
          var y = postdate.split("-")[0];
          for(var u2=0;u2<month.length;u2++){
            if(parseInt(m)==month[u2]) {
              m = month2[u2] ; break;
            }
          }
          var daystr = day+ ' ' + m + ' ' + y ;
          var trtd = '<div class="topimages "><figure><div  class="topListimages"><a href="'+posturl+'"><img width="300" min-height="160" class="cover" src="'+img[i]+'"/></a></div><figcaption><div class="toptext"><a href="'+posturl+'">'+posttitle+'</a></div></figcaption></figure></div>';					 
          document.write(trtd);       
          j++;
        }
      }
      function recentarticles7(json) {
        j = (showRandomImg) ? Math.floor((imgr.length+1)*Math.random()) : 0;
        img  = new Array();
        for (var i = 0; i < numposts3; i++) {
          var entry = json.feed.entry[i];
          var posttitle = entry.title.$t;
          var pcm;
          var posturl;
          if (i == json.feed.entry.length) break;
          for (var k = 0; k < entry.link.length; k++) {
            if (entry.link[k].rel == 'alternate') {
              posturl = entry.link[k].href;
              break;
            }
          }
          for (var k = 0; k < entry.link.length; k++) {
            if (entry.link[k].rel == 'replies' && entry.link[k].type == 'text/html') {
              pcm = entry.link[k].title.split(" ")[0];
              break;
            }
          }
          if ("content" in entry) {
            var postcontent = entry.content.$t;}
          else
            if ("summary" in entry) {
              var postcontent = entry.summary.$t;}
            else var postcontent = "";
          postdate = entry.published.$t;
          if(j>imgr.length-1) j=0;
          img[i] = imgr[j];
          s = postcontent	; a = s.indexOf("<img"); b = s.indexOf("src=\"",a); c = s.indexOf("\"",b+5); d = s.substr(b+5,c-b-5);
          if((a!=-1)&&(b!=-1)&&(c!=-1)&&(d!="")) img[i] = d;
          //cmtext = (text != 'no') ? '<i><font color="'+acolor+'">('+pcm+' '+text+')</font></i>' : '';
          var month = [1,2,3,4,5,6,7,8,9,10,11,12];
          var month2 = ["Jan","Feb","Mar","Apr","May","Jun","Jul","Aug","Sep","Oct","Nov","Dec"];
          var day = postdate.split("-")[2].substring(0,2);
          var m = postdate.split("-")[1];
          var y = postdate.split("-")[0];
          for(var u2=0;u2<month.length;u2++){
            if(parseInt(m)==month[u2]) {
              m = month2[u2] ; break;
            }
          }
          var daystr = day+ ' ' + m + ' ' + y ;
          var trtd = '<li><a title=" '+posttitle+' " href="'+posturl+'"><img width="90" height="70"  title=" '+posttitle+' " class=" " src="'+img[i]+'"/></a></li>';					 
          document.write(trtd);       
          j++;
        }
      }
      function recentarticles8(json) {
        j = (showRandomImg) ? Math.floor((imgr.length+1)*Math.random()) : 0;
        img  = new Array();
        if (numposts5 <= json.feed.entry.length) {
          maxpost = numposts1;
        }
        else
        {
          maxpost=json.feed.entry.length;
        }	
        for (var i = 0; i < maxpost; i++) {
          var entry = json.feed.entry[i];
          var posttitle = entry.title.$t;
          var pcm;
          var posturl;
          if (i == json.feed.entry.length) break;
          for (var k = 0; k < entry.link.length; k++) {
            if (entry.link[k].rel == 'alternate') {
              posturl = entry.link[k].href;
              break;
            }
          }
          for (var k = 0; k < entry.link.length; k++) {
            if (entry.link[k].rel == 'replies' && entry.link[k].type == 'text/html') {
              pcm = entry.link[k].title.split(" ")[0];
              break;
            }
          }
          if ("content" in entry) {
            var postcontent = entry.content.$t;}
          else
            if ("summary" in entry) {
              var postcontent = entry.summary.$t;}
            else var postcontent = "";
          postdate = entry.published.$t;
          if(j>imgr.length-1) j=0;
          img[i] = imgr[j];
          s = postcontent	; a = s.indexOf("<img"); b = s.indexOf("src=\"",a); c = s.indexOf("\"",b+5); d = s.substr(b+5,c-b-5);
          if((a!=-1)&&(b!=-1)&&(c!=-1)&&(d!="")) img[i] = d;
          //cmtext = (text != 'no') ? '<i><font color="'+acolor+'">('+pcm+' '+text+')</font></i>' : '';
          var month = [1,2,3,4,5,6,7,8,9,10,11,12];
          var month2 = ["Jan","Feb","Mar","Apr","May","Jun","Jul","Aug","Sep","Oct","Nov","Dec"];
          var day = postdate.split("-")[2].substring(0,2);
          var m = postdate.split("-")[1];
          var y = postdate.split("-")[0];
          for(var u2=0;u2<month.length;u2++){
            if(parseInt(m)==month[u2]) {
              m = month2[u2] ; break;
            }
          }
          var daystr = day+ ' ' + m + ' ' + y ;
          var trtd = '<li><h3 class="entry-title"><a href="'+posturl+'">'+posttitle+'</a></h3></li>';
          document.write(trtd);
          j++;
        }
      }
      //]]>
    </script>
    <style>
      #fbt-slider{
        position:relative;
        max-width:620px;
        width:100%; 
        height:320px; 
        overflow:hidden;
      }
      #fbt-slider .widget h2,.tabs-wrap .widget h2{display:none}
      .fbt_slider{
        margin-bottom:2px;
        position:relative;
        margin-bottom:15px;
        overflow:hidden;
        background-color:#fff;
      } 
      .fbt_slider_wrap{
        position:relative;
        height:320px;
        overflow:hidden;
        margin-bottom:3px;
        padding:0;
      }
      .fbt_slider_item{
        max-width:620px;
        height:320px;
        overflow:hidden;
        width:100%;
      }
      .fbt_slider .slides img{
        width:100%;
        height:auto;
        min-height:320px;
      }
      .fbt_slider .slider_caption{
        position:absolute;
        padding:10px 15px;
        background:#000;
        background:rgba(0,0,0,0.7);
        left:10px;
        bottom:55px;
        color:#f5f5f5;
        margin-bottom:12px;
        z-index:99;
      } 
      .fbt_slider .slider_caption:after{
        content:&quot;&quot;;
        height:0px;
        width:100%;
        background:#000;
        background:rgba(0,0,0,0.7);
        overflow:hidden;
        display:block;
        left:0;
        position:absolute;
        bottom:-4px
      }
      .fbt_slider_wrap .fbt_slider_item{display:none;position:relative}
      .flex-direction-nav {*height: 0;}
      .flex-direction-nav {
        margin: 0; 
        padding: 0; 
        list-style: none;
      } 
      .fbt_slider .slider_caption h3{
        margin-bottom:0;
        font-size:18px;
      } 
      .fbt_slider .slider_caption h3 a{
        font-family:&#39;Oswald&#39;,serif;
        color:#fff
      } 
      .fbt_slider .slider_caption h3 a:hover{color:#fc0} 
      .fbt_slider p.caption{display:none;} 
      .fbt_slider p.caption .post-meta{display:none} 
      .fbt_slider .flex-direction-nav a{
        background:url(http://2.bp.blogspot.com/-bcayzZsNafc/UvzIUZZ3sjI/AAAAAAAAFhA/MStBJy3TXe8/s1600/slider_direction.png) no-repeat;
        font-size:0;
        width:40px;
        height:40px;
        display:block; 
        position:absolute;
        bottom:5px;
        cursor: pointer;
        right:5px;
        z-index:99;
      } 
      .fbt_slider .flex-direction-nav .flex-next {
        background-position:100% 0;
        z-index:99;
      } 
      .fbt_slider .flex-direction-nav .flex-prev {margin-right:41px;z-index:99}
      .flex-control-nav.flex-control-paging{display:none}
      .layout-2c .flex-viewport{max-width:960px;margin:0 auto}
      .flex-viewport{max-width:1100px;margin:0 auto}
      .flexslider .slides{zoom:1;overflow:hidden}
      a.more-link{background:#222;color:#FFF;padding:3px 7px;display:block;float:left;margin-top:4px}
      a.more-link:hover{background:#444!important}
      li:first-child a.more-link, .ind-my li:first-child a.more-link {
        background: none repeat scroll 0 0 #333333;
        color: #FFFFFF;
        display: inline-block;
        margin: 20px 0;
        padding:auto 15px;
      }
    </style>
    <script type='text/javascript'>
      //<![CDATA[
      function PostSlide(b){(function(a){var f={blogURL:"",MaxPost:4,idcontaint:"",ImageSize:500,Summarylength:150,RandompostActive:true,loadingClass:"loadingz",pBlank:"",MonthNames:["Jan","Feb","Mar","Apr","May","Jun","Jul","Aug","Sep","Oct","Nov","Dec"],tagName:false};f=a.extend({},f,b);var g=a(f.idcontaint);g.html('<div class="fbt_slider_wrap"><ul class="slides"></ul></div>').addClass(f.loadingClass);var h=function(D){var z,B,x,e,F,C,G,j,E,y,A="",w=D.feed.entry;for(var H=0;H<w.length;H++){for(var d=0;d<w[H].link.length;d++){if(w[H].link[d].rel=="alternate"){z=w[H].link[d].href;break}}if("media$thumbnail"in w[H]){F=w[H].media$thumbnail.url.replace(/\/s[0-9]+\-c/g,"/s"+f.ImageSize);if(w[H].media$thumbnail.url.indexOf("img.favoritebtemplates.com")!=-1){F=w[H].media$thumbnail.url.replace("default","0")}}else{F=f.pBlank.replace(/\/s[0-9]+\-c/g,"/s"+f.ImageSize)}if("content"in w[H]){x=w[H].content.$t}else{if("summary"in w[H]){x=w[H].summary.$t}else{x=""}}x=x.replace(/<\S[^>]*>/g,"");if(x.length>f.Summarylength){x=x.substring(0,f.Summarylength)+"..."}B=w[H].title.$t;y=w[H].published.$t.substring(0,10);C=y.substring(0,4);G=y.substring(5,7);j=y.substring(8,10);E=f.MonthNames[parseInt(G,10)-1];A+='<li class="fbt_slider_item"><a title="'+B+'" class="" href="'+z+'"><img src="'+F+'"/></a><div class="slider_caption"><h3><a href="'+z+'">'+B+'</a></h3></div><p class="caption"><span class="post-meta"><span class="dd">'+j+'</span> <span class="dm">'+E+'</span> <span class="dy">'+C+"</span></span>"+x+"</p></li>"}g.find("ul.slides").append(A);if(!f.RandompostActive){a(f.idcontaint+" .fbt_slider_wrap").flexslider({animation:"fade",selector:".slides > li",animationLoop:true,smoothHeight:true,pauseOnHover:true,mousewheel:false,before:function(){a(f.idcontaint).find(".slider_caption").stop().animate({left:10,opacity:0},2000);a(f.idcontaint).find(".caption").stop().animate({left:10,opacity:0},2000)},after:function(){a(f.idcontaint).find(".slider_caption").stop().animate({left:10,opacity:1},2000);a(f.idcontaint).find(".caption").stop().animate({left:10,opacity:1},2000)}});g.removeClass(f.loadingClass)}};a.get((f.blogURL===""?window.location.protocol+"//"+window.location.host:f.blogURL)+"/feeds/posts/summary"+(f.tagName===false?"":"/-/"+f.tagName)+"?max-results=0&orderby=published&alt=json-in-script",function(e){Total_Posts_Number=e.feed.openSearch$totalResults.$t;if(Total_Posts_Number<=f.MaxPost){f.MaxPost=Total_Posts_Number}var r=[];while(r.length<f.MaxPost){var p=Math.ceil(Math.random()*Total_Posts_Number);var d=false;for(var k=0;k<r.length;k++){if(r[k]==p){d=true;break}}if(!d){r[r.length]=p}}if(f.RandompostActive==true){var j;for(var o=0;o<f.MaxPost;o++){j=a.get((f.blogURL===""?window.location.protocol+"//"+window.location.host:f.blogURL)+"/feeds/posts/default"+(f.tagName===false?"":"/-/"+f.tagName)+"?start-index="+r[o]+"&max-results=1&orderby=published&alt=json-in-script",h,"jsonp")}a.when(j).done(function(){a(f.idcontaint+" .fbt_slider_wrap").flexslider({animation:"fade",selector:".slides > li",animationLoop:true,smoothHeight:true,pauseOnHover:true,mousewheel:false,initDelay:f.MaxPost*700,before:function(){a(f.idcontaint).find(".slider_caption").stop().animate({left:100,opacity:0},2000);a(f.idcontaint).find(".caption").stop().animate({left:0,opacity:0},2000)},after:function(){a(f.idcontaint).find(".slider_caption").stop().animate({left:10,opacity:1},2000);a(f.idcontaint).find(".caption").stop().animate({left:50,opacity:1},2000)}});g.removeClass(f.loadingClass)})}else{a.get((f.blogURL===""?window.location.protocol+"//"+window.location.host:f.blogURL)+"/feeds/posts/default"+(f.tagName===false?"":"/-/"+f.tagName)+"?max-results="+f.MaxPost+"&orderby=published&alt=json-in-script",h,"jsonp")}},"jsonp")})(jQuery)};                                    //]]>
    </script>
    <script type='text/javascript'>
      //<![CDATA[
      /*
 * jQuery FlexSlider v2.0
 * http://www.woothemes.com/flexslider/
 *
 * Copyright 2012 WooThemes
 * Free to use under the GPLv2 license.
 * http://www.gnu.org/licenses/gpl-2.0.html
 *
 * Contributing author: Tyler Smith (@mbmufffin)
 */
      ;(function ($) {
        //FlexSlider: Object Instance
        $.flexslider = function(el, options) {
          var slider = $(el),
              vars = $.extend({}, $.flexslider.defaults, options),
              namespace = vars.namespace,
              touch = ("ontouchstart" in window) || window.DocumentTouch && document instanceof DocumentTouch,
              eventType = (touch) ? "touchend" : "click",
              vertical = vars.direction === "vertical",
              reverse = vars.reverse,
              carousel = (vars.itemWidth > 0),
              fade = vars.animation === "fade",
              asNav = vars.asNavFor !== "",
              methods = {};
          // Store a reference to the slider object
          $.data(el, "flexslider", slider);
          // Privat slider methods
          methods = {
            init: function() {
              slider.animating = false;
              slider.currentSlide = vars.startAt;
              slider.animatingTo = slider.currentSlide;
              slider.atEnd = (slider.currentSlide === 0 || slider.currentSlide === slider.last);
              slider.containerSelector = vars.selector.substr(0,vars.selector.search(' '));
              slider.slides = $(vars.selector, slider);
              slider.container = $(slider.containerSelector, slider);
              slider.count = slider.slides.length;
              // SYNC:
              slider.syncExists = $(vars.sync).length > 0;
              // SLIDE:
              if (vars.animation === "slide") vars.animation = "swing";
              slider.prop = (vertical) ? "top" : "marginLeft";
              slider.args = {};
              // SLIDESHOW:
              slider.manualPause = false;
              // TOUCH/USECSS:
              slider.transitions = !vars.video && !fade && vars.useCSS && (function() {
                var obj = document.createElement('div'),
                    props = ['perspectiveProperty', 'WebkitPerspective', 'MozPerspective', 'OPerspective', 'msPerspective'];
                for (var i in props) {
                  if ( obj.style[ props[i] ] !== undefined ) {
                    slider.pfx = props[i].replace('Perspective','').toLowerCase();
                    slider.prop = "-" + slider.pfx + "-transform";
                    return true;
                  }
                }
                return false;
              }());
              // CONTROLSCONTAINER:
              if (vars.controlsContainer !== "") slider.controlsContainer = $(vars.controlsContainer).length > 0 && $(vars.controlsContainer);
              // MANUAL:
              if (vars.manualControls !== "") slider.manualControls = $(vars.manualControls).length > 0 && $(vars.manualControls);
              // RANDOMIZE:
              if (vars.randomize) {
                slider.slides.sort(function() { return (Math.round(Math.random())-0.5); });
                slider.container.empty().append(slider.slides);
              }
              slider.doMath();
              // ASNAV:
              if (asNav) methods.asNav.setup();
              // INIT
              slider.setup("init");
              // CONTROLNAV:
              if (vars.controlNav) methods.controlNav.setup();
              // DIRECTIONNAV:
              if (vars.directionNav) methods.directionNav.setup();
              // KEYBOARD:
              if (vars.keyboard && ($(slider.containerSelector).length === 1 || vars.multipleKeyboard)) {
                $(document).bind('keyup', function(event) {
                  var keycode = event.keyCode;
                  if (!slider.animating && (keycode === 39 || keycode === 37)) {
                    var target = (keycode === 39) ? slider.getTarget('next') :
                    (keycode === 37) ? slider.getTarget('prev') : false;
                    slider.flexAnimate(target, vars.pauseOnAction);
                  }
                });
              }
              // MOUSEWHEEL:
              if (vars.mousewheel) {
                slider.bind('mousewheel', function(event, delta, deltaX, deltaY) {
                  event.preventDefault();
                  var target = (delta < 0) ? slider.getTarget('next') : slider.getTarget('prev');
                  slider.flexAnimate(target, vars.pauseOnAction);
                });
              }
              // PAUSEPLAY
              if (vars.pausePlay) methods.pausePlay.setup();
              // SLIDSESHOW
              if (vars.slideshow) {
                if (vars.pauseOnHover) {
                  slider.hover(function() {
                    slider.pause();
                  }, function() {
                    if (!slider.manualPause) slider.play();
                  });
                }
                // initialize animation
                (vars.initDelay > 0) ? setTimeout(slider.play, vars.initDelay) : slider.play();
              }
              // TOUCH
              if (touch && vars.touch) methods.touch();
              // FADE&&SMOOTHHEIGHT || SLIDE:
              if (!fade || (fade && vars.smoothHeight)) $(window).bind("resize focus", methods.resize);
              // API: start() Callback
              setTimeout(function(){
                vars.start(slider);
              }, 200);
            },
            asNav: {
              setup: function() {
                slider.asNav = true;
                slider.animatingTo = Math.floor(slider.currentSlide/slider.move);
                slider.currentItem = slider.currentSlide;
                slider.slides.removeClass(namespace + "active-slide").eq(slider.currentItem).addClass(namespace + "active-slide");
                slider.slides.click(function(e){
                  e.preventDefault();
                  var $slide = $(this),
                      target = $slide.index();
                  if (!$(vars.asNavFor).data('flexslider').animating && !$slide.hasClass('active')) {
                    slider.direction = (slider.currentItem < target) ? "next" : "prev";
                    slider.flexAnimate(target, vars.pauseOnAction, false, true, true);
                  }
                });
              }
            },
            controlNav: {
              setup: function() {
                if (!slider.manualControls) {
                  methods.controlNav.setupPaging();
                } else { // MANUALCONTROLS:
                  methods.controlNav.setupManual();
                }
              },
              setupPaging: function() {
                var type = (vars.controlNav === "thumbnails") ? 'control-thumbs' : 'control-paging',
                    j = 1,
                    item;
                slider.controlNavScaffold = $('<ol class="'+ namespace + 'control-nav ' + namespace + type + '"></ol>');
                if (slider.pagingCount > 1) {
                  for (var i = 0; i < slider.pagingCount; i++) {
                    item = (vars.controlNav === "thumbnails") ? '<img src="' + slider.slides.eq(i).attr("data-thumb") + '"/>' : '<a>' + j + '</a>';
                    slider.controlNavScaffold.append('<li>' + item + '</li>');
                    j++;
                  }
                }
                // CONTROLSCONTAINER:
                (slider.controlsContainer) ? $(slider.controlsContainer).append(slider.controlNavScaffold) : slider.append(slider.controlNavScaffold);
                methods.controlNav.set();
                methods.controlNav.active();
                slider.controlNavScaffold.delegate('a, img', eventType, function(event) {
                  event.preventDefault();
                  var $this = $(this),
                      target = slider.controlNav.index($this);
                  if (!$this.hasClass(namespace + 'active')) {
                    slider.direction = (target > slider.currentSlide) ? "next" : "prev";
                    slider.flexAnimate(target, vars.pauseOnAction);
                  }
                });
                // Prevent iOS click event bug
                if (touch) {
                  slider.controlNavScaffold.delegate('a', "click touchstart", function(event) {
                    event.preventDefault();
                  });
                }
              },
              setupManual: function() {
                slider.controlNav = slider.manualControls;
                methods.controlNav.active();
                slider.controlNav.live(eventType, function(event) {
                  event.preventDefault();
                  var $this = $(this),
                      target = slider.controlNav.index($this);
                  if (!$this.hasClass(namespace + 'active')) {
                    (target > slider.currentSlide) ? slider.direction = "next" : slider.direction = "prev";
                    slider.flexAnimate(target, vars.pauseOnAction);
                  }
                });
                // Prevent iOS click event bug
                if (touch) {
                  slider.controlNav.live("click touchstart", function(event) {
                    event.preventDefault();
                  });
                }
              },
              set: function() {
                var selector = (vars.controlNav === "thumbnails") ? 'img' : 'a';
                slider.controlNav = $('.' + namespace + 'control-nav li ' + selector, (slider.controlsContainer) ? slider.controlsContainer : slider);
              },
              active: function() {
                slider.controlNav.removeClass(namespace + "active").eq(slider.animatingTo).addClass(namespace + "active");
              },
              update: function(action, pos) {
                if (slider.pagingCount > 1 && action === "add") {
                  slider.controlNavScaffold.append($('<li><a>' + slider.count + '</a></li>'));
                } else if (slider.pagingCount === 1) {
                  slider.controlNavScaffold.find('li').remove();
                } else {
                  slider.controlNav.eq(pos).closest('li').remove();
                }
                methods.controlNav.set();
                (slider.pagingCount > 1 && slider.pagingCount !== slider.controlNav.length) ? slider.update(pos, action) : methods.controlNav.active();
              }
            },
            directionNav: {
              setup: function() {
                var directionNavScaffold = $('<ul class="' + namespace + 'direction-nav"><li><a class="' + namespace + 'prev" href="#">' + vars.prevText + '</a></li><li><a class="' + namespace + 'next" href="#">' + vars.nextText + '</a></li></ul>');
                // CONTROLSCONTAINER:
                if (slider.controlsContainer) {
                  $(slider.controlsContainer).append(directionNavScaffold);
                  slider.directionNav = $('.' + namespace + 'direction-nav li a', slider.controlsContainer);
                } else {
                  slider.append(directionNavScaffold);
                  slider.directionNav = $('.' + namespace + 'direction-nav li a', slider);
                }
                methods.directionNav.update();
                slider.directionNav.bind(eventType, function(event) {
                  event.preventDefault();
                  var target = ($(this).hasClass(namespace + 'next')) ? slider.getTarget('next') : slider.getTarget('prev');
                  slider.flexAnimate(target, vars.pauseOnAction);
                });
                // Prevent iOS click event bug
                if (touch) {
                  slider.directionNav.bind("click touchstart", function(event) {
                    event.preventDefault();
                  });
                }
              },
              update: function() {
                var disabledClass = namespace + 'disabled';
                if (!vars.animationLoop) {
                  if (slider.pagingCount === 1) {
                    slider.directionNav.addClass(disabledClass);
                  } else if (slider.animatingTo === 0) {
                    slider.directionNav.removeClass(disabledClass).filter('.' + namespace + "prev").addClass(disabledClass);
                  } else if (slider.animatingTo === slider.last) {
                    slider.directionNav.removeClass(disabledClass).filter('.' + namespace + "next").addClass(disabledClass);
                  } else {
                    slider.directionNav.removeClass(disabledClass);
                  }
                }
              }
            },
            pausePlay: {
              setup: function() {
                var pausePlayScaffold = $('<div class="' + namespace + 'pauseplay"><a></a></div>');
                // CONTROLSCONTAINER:
                if (slider.controlsContainer) {
                  slider.controlsContainer.append(pausePlayScaffold);
                  slider.pausePlay = $('.' + namespace + 'pauseplay a', slider.controlsContainer);
                } else {
                  slider.append(pausePlayScaffold);
                  slider.pausePlay = $('.' + namespace + 'pauseplay a', slider);
                }
                // slider.pausePlay.addClass(pausePlayState).text((pausePlayState == 'pause') ? vars.pauseText : vars.playText);
                methods.pausePlay.update((vars.slideshow) ? namespace + 'pause' : namespace + 'play');
                slider.pausePlay.bind(eventType, function(event) {
                  event.preventDefault();
                  if ($(this).hasClass(namespace + 'pause')) {
                    slider.pause();
                    slider.manualPause = true;
                  } else {
                    slider.play();
                    slider.manualPause = false;
                  }
                });
                // Prevent iOS click event bug
                if (touch) {
                  slider.pausePlay.bind("click touchstart", function(event) {
                    event.preventDefault();
                  });
                }
              },
              update: function(state) {
                (state === "play") ? slider.pausePlay.removeClass(namespace + 'pause').addClass(namespace + 'play').text(vars.playText) : slider.pausePlay.removeClass(namespace + 'play').addClass(namespace + 'pause').text(vars.pauseText);
              }
            },
            touch: function() {
              var startX,
                  startY,
                  offset,
                  cwidth,
                  dx,
                  startT,
                  scrolling = false;
              el.addEventListener('touchstart', onTouchStart, false);
              function onTouchStart(e) {
                if (slider.animating) {
                  e.preventDefault();
                } else if (e.touches.length === 1) {
                  slider.pause();
                  // CAROUSEL: 
                  cwidth = (vertical) ? slider.h : slider. w;
                  startT = Number(new Date());
                  // CAROUSEL:
                  offset = (carousel && reverse && slider.animatingTo === slider.last) ? 0 :
                  (carousel && reverse) ? slider.limit - (((slider.itemW + vars.itemMargin) * slider.move) * slider.animatingTo) :
                  (carousel && slider.currentSlide === slider.last) ? slider.limit :
                  (carousel) ? ((slider.itemW + vars.itemMargin) * slider.move) * slider.currentSlide : 
                  (reverse) ? (slider.last - slider.currentSlide + slider.cloneOffset) * cwidth : (slider.currentSlide + slider.cloneOffset) * cwidth;
                  startX = (vertical) ? e.touches[0].pageY : e.touches[0].pageX;
                  startY = (vertical) ? e.touches[0].pageX : e.touches[0].pageY;
                  el.addEventListener('touchmove', onTouchMove, false);
                  el.addEventListener('touchend', onTouchEnd, false);
                }
              }
              function onTouchMove(e) {
                dx = (vertical) ? startX - e.touches[0].pageY : startX - e.touches[0].pageX;
                scrolling = (vertical) ? (Math.abs(dx) < Math.abs(e.touches[0].pageX - startY)) : (Math.abs(dx) < Math.abs(e.touches[0].pageY - startY));
                if (!scrolling || Number(new Date()) - startT > 500) {
                  e.preventDefault();
                  if (!fade && slider.transitions) {
                    if (!vars.animationLoop) {
                      dx = dx/((slider.currentSlide === 0 && dx < 0 || slider.currentSlide === slider.last && dx > 0) ? (Math.abs(dx)/cwidth+2) : 1);
                    }
                    slider.setProps(offset + dx, "setTouch");
                  }
                }
              }
              function onTouchEnd(e) {
                if (slider.animatingTo === slider.currentSlide && !scrolling && !(dx === null)) {
                  var updateDx = (reverse) ? -dx : dx,
                      target = (updateDx > 0) ? slider.getTarget('next') : slider.getTarget('prev');
                  if (slider.canAdvance(target) && (Number(new Date()) - startT < 550 && Math.abs(updateDx) > 20 || Math.abs(updateDx) > cwidth/2)) {
                    slider.flexAnimate(target, vars.pauseOnAction);
                  } else {
                    slider.flexAnimate(slider.currentSlide, vars.pauseOnAction, true);
                  }
                }
                // finish the touch by undoing the touch session
                el.removeEventListener('touchmove', onTouchMove, false);
                el.removeEventListener('touchend', onTouchEnd, false);
                startX = null;
                startY = null;
                dx = null;
                offset = null;
              }
            },
            resize: function() {
              if (!slider.animating && slider.is(':visible')) {
                if (!carousel) slider.doMath();
                if (fade) {
                  // SMOOTH HEIGHT:
                  methods.smoothHeight();
                } else if (carousel) { //CAROUSEL:
                  slider.slides.width(slider.computedW);
                  slider.update(slider.pagingCount);
                  slider.setProps();
                }
                  else if (vertical) { //VERTICAL:
                    slider.viewport.height(slider.h);
                    slider.setProps(slider.h, "setTotal");
                  } else {
                    // SMOOTH HEIGHT:
                    if (vars.smoothHeight) methods.smoothHeight();
                    slider.newSlides.width(slider.computedW);
                    slider.setProps(slider.computedW, "setTotal");
                  }
              }
            },
            smoothHeight: function(dur) {
              if (!vertical || fade) {
                var $obj = (fade) ? slider : slider.viewport;
                (dur) ? $obj.animate({"height": slider.slides.eq(slider.animatingTo).height()}, dur) : $obj.height(slider.slides.eq(slider.animatingTo).height());
              }
            },
            sync: function(action) {
              var $obj = $(vars.sync).data("flexslider"),
                  target = slider.animatingTo;
              switch (action) {
                case "animate": $obj.flexAnimate(target, vars.pauseOnAction, false, true); break;
                case "play": if (!$obj.playing && !$obj.asNav) { $obj.play(); } break;
                case "pause": $obj.pause(); break;
              }
            }
          }
          // public methods
          slider.flexAnimate = function(target, pause, override, withSync, fromNav) {
            if (!slider.animating && (slider.canAdvance(target) || override) && slider.is(":visible")) {
              if (asNav && withSync) {
                var master = $(vars.asNavFor).data('flexslider');
                slider.atEnd = target === 0 || target === slider.count - 1;
                master.flexAnimate(target, true, false, true, fromNav);
                slider.direction = (slider.currentItem < target) ? "next" : "prev";
                master.direction = slider.direction;
                if (Math.ceil((target + 1)/slider.visible) - 1 !== slider.currentSlide && target !== 0) {
                  slider.currentItem = target;
                  slider.slides.removeClass(namespace + "active-slide").eq(target).addClass(namespace + "active-slide");
                  target = Math.floor(target/slider.visible);
                } else {
                  slider.currentItem = target;
                  slider.slides.removeClass(namespace + "active-slide").eq(target).addClass(namespace + "active-slide");
                  return false;
                }
              }
              slider.animating = true;
              slider.animatingTo = target;
              // API: before() animation Callback
              vars.before(slider);
              // SLIDESHOW:
              if (pause) slider.pause();
              // SYNC:
              if (slider.syncExists && !fromNav) methods.sync("animate");
              // CONTROLNAV
              if (vars.controlNav) methods.controlNav.active();
              // !CAROUSEL:
              // CANDIDATE: slide active class (for add/remove slide)
              if (!carousel) slider.slides.removeClass(namespace + 'active-slide').eq(target).addClass(namespace + 'active-slide');
              // INFINITE LOOP:
              // CANDIDATE: atEnd
              slider.atEnd = target === 0 || target === slider.last;
              // DIRECTIONNAV:
              if (vars.directionNav) methods.directionNav.update();
              if (target === slider.last) {
                // API: end() of cycle Callback
                vars.end(slider);
                // SLIDESHOW && !INFINITE LOOP:
                if (!vars.animationLoop) slider.pause();
              }
              // SLIDE:
              if (!fade) {
                var dimension = (vertical) ? slider.slides.filter(':first').height() : slider.computedW,
                    margin, slideString, calcNext;
                // INFINITE LOOP / REVERSE:
                if (carousel) {
                  margin = (vars.itemWidth > slider.w) ? vars.itemMargin * 2 : vars.itemMargin;
                  calcNext = ((slider.itemW + margin) * slider.move) * slider.animatingTo;
                  slideString = (calcNext > slider.limit && slider.visible !== 1) ? slider.limit : calcNext;
                } else if (slider.currentSlide === 0 && target === slider.count - 1 && vars.animationLoop && slider.direction !== "next") {
                  slideString = (reverse) ? (slider.count + slider.cloneOffset) * dimension : 0;
                } else if (slider.currentSlide === slider.last && target === 0 && vars.animationLoop && slider.direction !== "prev") {
                  slideString = (reverse) ? 0 : (slider.count + 1) * dimension;
                } else {
                  slideString = (reverse) ? ((slider.count - 1) - target + slider.cloneOffset) * dimension : (target + slider.cloneOffset) * dimension;
                }
                slider.setProps(slideString, "", vars.animationSpeed);
                if (slider.transitions) {
                  if (!vars.animationLoop || !slider.atEnd) {
                    slider.animating = false;
                    slider.currentSlide = slider.animatingTo;
                  }
                  slider.container.unbind("webkitTransitionEnd transitionend");
                  slider.container.bind("webkitTransitionEnd transitionend", function() {
                    slider.wrapup(dimension);
                  });
                } else {
                  slider.container.animate(slider.args, vars.animationSpeed, vars.easing, function(){
                    slider.wrapup(dimension);
                  });
                }
              } else { // FADE:
                slider.slides.eq(slider.currentSlide).fadeOut(vars.animationSpeed, vars.easing);
                slider.slides.eq(target).fadeIn(vars.animationSpeed, vars.easing, slider.wrapup);
              }
              // SMOOTH HEIGHT:
              if (vars.smoothHeight) methods.smoothHeight(vars.animationSpeed);
            }
          } 
          slider.wrapup = function(dimension) {
            // SLIDE:
            if (!fade && !carousel) {
              if (slider.currentSlide === 0 && slider.animatingTo === slider.last && vars.animationLoop) {
                slider.setProps(dimension, "jumpEnd");
              } else if (slider.currentSlide === slider.last && slider.animatingTo === 0 && vars.animationLoop) {
                slider.setProps(dimension, "jumpStart");
              }
            }
            slider.animating = false;
            slider.currentSlide = slider.animatingTo;
            // API: after() animation Callback
            vars.after(slider);
          }
          // SLIDESHOW:
          slider.animateSlides = function() {
            if (!slider.animating) slider.flexAnimate(slider.getTarget("next"));
          }
          // SLIDESHOW:
          slider.pause = function() {
            clearInterval(slider.animatedSlides);
            slider.playing = false;
            // PAUSEPLAY:
            if (vars.pausePlay) methods.pausePlay.update("play");
            // SYNC:
            if (slider.syncExists) methods.sync("pause");
          }
          // SLIDESHOW:
          slider.play = function() {
            slider.animatedSlides = setInterval(slider.animateSlides, vars.slideshowSpeed);
            slider.playing = true;
            // PAUSEPLAY:
            if (vars.pausePlay) methods.pausePlay.update("pause");
            // SYNC:
            if (slider.syncExists) methods.sync("play");
          }
          slider.canAdvance = function(target) {
            // ASNAV:
            var last = (asNav) ? slider.pagingCount - 1 : slider.last;
            return (asNav && slider.currentItem === 0 && target === slider.pagingCount - 1 && slider.direction !== "next") ? false :
            (target === slider.currentSlide && !asNav) ? false :
            (vars.animationLoop) ? true :
            (slider.atEnd && slider.currentSlide === 0 && target === last && slider.direction !== "next") ? false :
            (slider.atEnd && slider.currentSlide === last && target === 0 && slider.direction === "next") ? false :
            true;
          }
          slider.getTarget = function(dir) {
            slider.direction = dir; 
            if (dir === "next") {
              return (slider.currentSlide === slider.last) ? 0 : slider.currentSlide + 1;
            } else {
              return (slider.currentSlide === 0) ? slider.last : slider.currentSlide - 1;
            }
          }
          // SLIDE:
          slider.setProps = function(pos, special, dur) {
            var target = (function() {
              var posCheck = (pos) ? pos : ((slider.itemW + vars.itemMargin) * slider.move) * slider.animatingTo,
                  posCalc = (function() {
                    if (carousel) {
                      return (special === "setTouch") ? pos :
                      (reverse && slider.animatingTo === slider.last) ? 0 :
                      (reverse) ? slider.limit - (((slider.itemW + vars.itemMargin) * slider.move) * slider.animatingTo) :
                      (slider.animatingTo === slider.last) ? slider.limit : posCheck;
                    } else {
                      switch (special) {
                        case "setTotal": return (reverse) ? ((slider.count - 1) - slider.currentSlide + slider.cloneOffset) * pos : (slider.currentSlide + slider.cloneOffset) * pos;
                        case "setTouch": return (reverse) ? pos : pos;
                        case "jumpEnd": return (reverse) ? pos : slider.count * pos;
                        case "jumpStart": return (reverse) ? slider.count * pos : pos;
                        default: return pos;
                      }
                    }
                  }());
              return (posCalc * -1) + "px";
            }());
            if (slider.transitions) {
              target = (vertical) ? "translate3d(0," + target + ",0)" : "translate3d(" + target + ",0,0)";
              dur = (dur !== undefined) ? (dur/1000) + "s" : "0s";
              slider.container.css("-" + slider.pfx + "-transition-duration", dur);
            }
            slider.args[slider.prop] = target;
            if (slider.transitions || dur === undefined) slider.container.css(slider.args);
          }
          slider.setup = function(type) {
            // SLIDE:
            if (!fade) {
              var sliderOffset, arr;
              if (type === "init") {
                slider.viewport = $('<div class="flex-viewport"></div>').css({"overflow": "hidden", "position": "relative"}).appendTo(slider).append(slider.container);
                // INFINITE LOOP:
                slider.cloneCount = 0;
                slider.cloneOffset = 0;
                // REVERSE:
                if (reverse) {
                  arr = $.makeArray(slider.slides).reverse();
                  slider.slides = $(arr);
                  slider.container.empty().append(slider.slides);
                }
              }
              // INFINITE LOOP && !CAROUSEL:
              if (vars.animationLoop && !carousel) {
                slider.cloneCount = 2;
                slider.cloneOffset = 1;
                // clear out old clones
                if (type !== "init") slider.container.find('.clone').remove();
                slider.container.append(slider.slides.first().clone().addClass('clone')).prepend(slider.slides.last().clone().addClass('clone'));
              }
              slider.newSlides = $(vars.selector, slider);
              sliderOffset = (reverse) ? slider.count - 1 - slider.currentSlide + slider.cloneOffset : slider.currentSlide + slider.cloneOffset;
              // VERTICAL:
              if (vertical && !carousel) {
                slider.container.height((slider.count + slider.cloneCount) * 200 + "%").css("position", "absolute").width("100%");
                setTimeout(function(){
                  slider.newSlides.css({"display": "block"});
                  slider.doMath();
                  slider.viewport.height(slider.h);
                  slider.setProps(sliderOffset * slider.h, "init");
                }, (type === "init") ? 100 : 0);
              } else {
                slider.container.width((slider.count + slider.cloneCount) * 200 + "%");
                slider.setProps(sliderOffset * slider.computedW, "init");
                setTimeout(function(){
                  slider.doMath();
                  slider.newSlides.css({"width": slider.computedW, "float": "left", "display": "block"});
                  // SMOOTH HEIGHT:
                  if (vars.smoothHeight) methods.smoothHeight();
                }, (type === "init") ? 100 : 0);
              }
            } else { // FADE: 
              slider.slides.css({"width": "100%", "float": "left", "marginRight": "-100%", "position": "relative"});
              if (type === "init") slider.slides.eq(slider.currentSlide).fadeIn(vars.animationSpeed, vars.easing);
              // SMOOTH HEIGHT:
              if (vars.smoothHeight) methods.smoothHeight();
            }
            // !CAROUSEL:
            // CANDIDATE: active slide
            if (!carousel) slider.slides.removeClass(namespace + "active-slide").eq(slider.currentSlide).addClass(namespace + "active-slide");
          }
          slider.doMath = function() {
            var slide = slider.slides.first(),
                slideMargin = vars.itemMargin,
                minItems = vars.minItems,
                maxItems = vars.maxItems;
            slider.w = slider.width();
            slider.h = slide.height();
            slider.boxPadding = slide.outerWidth() - slide.width();
            // CAROUSEL:
            if (carousel) {
              slider.itemT = vars.itemWidth + slideMargin;
              slider.minW = (minItems) ? minItems * slider.itemT : slider.w;
              slider.maxW = (maxItems) ? maxItems * slider.itemT : slider.w;
              slider.itemW = (slider.minW > slider.w) ? (slider.w - (slideMargin * minItems))/minItems :
              (slider.maxW < slider.w) ? (slider.w - (slideMargin * maxItems))/maxItems :
              (vars.itemWidth > slider.w) ? slider.w : vars.itemWidth;
              slider.visible = Math.floor(slider.w/(slider.itemW + slideMargin));
              slider.move = (vars.move > 0 && vars.move < slider.visible ) ? vars.move : slider.visible;
              slider.pagingCount = Math.ceil(((slider.count - slider.visible)/slider.move) + 1);
              slider.last =  slider.pagingCount - 1;
              slider.limit = (slider.pagingCount === 1) ? 0 :
              (vars.itemWidth > slider.w) ? ((slider.itemW + (slideMargin * 2)) * slider.count) - slider.w - slideMargin : ((slider.itemW + slideMargin) * slider.count) - slider.w;
            } else {
              slider.itemW = slider.w;
              slider.pagingCount = slider.count;
              slider.last = slider.count - 1;
            }
            slider.computedW = slider.itemW - slider.boxPadding;
          }
          slider.update = function(pos, action) {
            slider.doMath();
            // update currentSlide and slider.animatingTo if necessary
            if (!carousel) {
              if (pos < slider.currentSlide) {
                slider.currentSlide += 1;
              } else if (pos <= slider.currentSlide && pos !== 0) {
                slider.currentSlide -= 1;
              }
              slider.animatingTo = slider.currentSlide;
            }
            // update controlNav
            if (vars.controlNav && !slider.manualControls) {
              if ((action === "add" && !carousel) || slider.pagingCount > slider.controlNav.length) {
                methods.controlNav.update("add");
              } else if ((action === "remove" && !carousel) || slider.pagingCount < slider.controlNav.length) {
                if (carousel && slider.currentSlide > slider.last) {
                  slider.currentSlide -= 1;
                  slider.animatingTo -= 1;
                }
                methods.controlNav.update("remove", slider.last);
              }
            }
            // update directionNav
            if (vars.directionNav) methods.directionNav.update();
          }
          slider.addSlide = function(obj, pos) {
            var $obj = $(obj);
            slider.count += 1;
            slider.last = slider.count - 1;
            // append new slide
            if (vertical && reverse) {
              (pos !== undefined) ? slider.slides.eq(slider.count - pos).after($obj) : slider.container.prepend($obj);
            } else {
              (pos !== undefined) ? slider.slides.eq(pos).before($obj) : slider.container.append($obj);
            }
            // update currentSlide, animatingTo, controlNav, and directionNav
            slider.update(pos, "add");
            // update slider.slides
            slider.slides = $(vars.selector + ':not(.clone)', slider);
            // re-setup the slider to accomdate new slide
            slider.setup();
            //FlexSlider: added() Callback
            vars.added(slider);
          }
          slider.removeSlide = function(obj) {
            var pos = (isNaN(obj)) ? slider.slides.index($(obj)) : obj;
            // update count
            slider.count -= 1;
            slider.last = slider.count - 1;
            // remove slide
            if (isNaN(obj)) {
              $(obj, slider.slides).remove();
            } else {
              (vertical && reverse) ? slider.slides.eq(slider.last).remove() : slider.slides.eq(obj).remove();
            }
            // update currentSlide, animatingTo, controlNav, and directionNav
            slider.doMath();
            slider.update(pos, "remove");
            // update slider.slides
            slider.slides = $(vars.selector + ':not(.clone)', slider);
            // re-setup the slider to accomdate new slide
            slider.setup();
            // FlexSlider: removed() Callback
            vars.removed(slider);
          }
          //FlexSlider: Initialize
          methods.init();
        }
        //FlexSlider: Default Settings
        $.flexslider.defaults = {
          namespace: "flex-",             //{NEW} String: Prefix string attached to the class of every element generated by the plugin
          selector: ".slides > li",       //{NEW} Selector: Must match a simple pattern. '{container} > {slide}' -- Ignore pattern at your own peril
          animation: "fade",              //String: Select your animation type, "fade" or "slide"
          easing: "swing",               //{NEW} String: Determines the easing method used in jQuery transitions. jQuery easing plugin is supported!
          direction: "horizontal",        //String: Select the sliding direction, "horizontal" or "vertical"
          reverse: false,                 //{NEW} Boolean: Reverse the animation direction
          animationLoop: true,             //Boolean: Should the animation loop? If false, directionNav will received "disable" classes at either end
          smoothHeight: false,            //{NEW} Boolean: Allow height of the slider to animate smoothly in horizontal mode  
          startAt: 0,                     //Integer: The slide that the slider should start on. Array notation (0 = first slide)
          slideshow: true,                //Boolean: Animate slider automatically
          slideshowSpeed: 7000,           //Integer: Set the speed of the slideshow cycling, in milliseconds
          animationSpeed: 600,            //Integer: Set the speed of animations, in milliseconds
          initDelay: 0,                   //{NEW} Integer: Set an initialization delay, in milliseconds
          randomize: false,               //Boolean: Randomize slide order
          // Usability features
          pauseOnAction: true,            //Boolean: Pause the slideshow when interacting with control elements, highly recommended.
          pauseOnHover: false,            //Boolean: Pause the slideshow when hovering over slider, then resume when no longer hovering
          useCSS: true,                   //{NEW} Boolean: Slider will use CSS3 transitions if available
          touch: true,                    //{NEW} Boolean: Allow touch swipe navigation of the slider on touch-enabled devices
          video: false,                   //{NEW} Boolean: If using video in the slider, will prevent CSS3 3D Transforms to avoid graphical glitches
          // Primary Controls
          controlNav: true,               //Boolean: Create navigation for paging control of each clide? Note: Leave true for manualControls usage
          directionNav: true,             //Boolean: Create navigation for previous/next navigation? (true/false)
          prevText: "Previous",           //String: Set the text for the "previous" directionNav item
          nextText: "Next",               //String: Set the text for the "next" directionNav item
          // Secondary Navigation
          keyboard: true,                 //Boolean: Allow slider navigating via keyboard left/right keys
          multipleKeyboard: false,        //{NEW} Boolean: Allow keyboard navigation to affect multiple sliders. Default behavior cuts out keyboard navigation with more than one slider present.
          mousewheel: false,              //{UPDATED} Boolean: Requires jquery.mousewheel.js (https://github.com/brandonaaron/jquery-mousewheel) - Allows slider navigating via mousewheel
          pausePlay: false,               //Boolean: Create pause/play dynamic element
          pauseText: "Pause",             //String: Set the text for the "pause" pausePlay item
          playText: "Play",               //String: Set the text for the "play" pausePlay item
          // Special properties
          controlsContainer: "",          //{UPDATED} jQuery Object/Selector: Declare which container the navigation elements should be appended too. Default container is the FlexSlider element. Example use would be $(".flexslider-container"). Property is ignored if given element is not found.
          manualControls: "",             //{UPDATED} jQuery Object/Selector: Declare custom control navigation. Examples would be $(".flex-control-nav li") or "#tabs-nav li img", etc. The number of elements in your controlNav should match the number of slides/tabs.
          sync: "",                       //{NEW} Selector: Mirror the actions performed on this slider with another slider. Use with care.
          asNavFor: "",                   //{NEW} Selector: Internal property exposed for turning the slider into a thumbnail navigation for another slider
          // Carousel Options
          itemWidth: 0,                   //{NEW} Integer: Box-model width of individual carousel items, including horizontal borders and padding.
          itemMargin: 0,                  //{NEW} Integer: Margin between carousel items.
          minItems: 0,                    //{NEW} Integer: Minimum number of carousel items that should be visible. Items will resize fluidly when below this.
          maxItems: 0,                    //{NEW} Integer: Maxmimum number of carousel items that should be visible. Items will resize fluidly when above this limit.
          move: 0,                        //{NEW} Integer: Number of carousel items that should move on animation. If 0, slider will move all visible items.
          // Callback API
          start: function(){},            //Callback: function(slider) - Fires when the slider loads the first slide
          before: function(){},           //Callback: function(slider) - Fires asynchronously with each slider animation
          after: function(){},            //Callback: function(slider) - Fires after each slider animation completes
          end: function(){},              //Callback: function(slider) - Fires when the slider reaches the last slide (asynchronous)
          added: function(){},            //{NEW} Callback: function(slider) - Fires after a slide is added
          removed: function(){}           //{NEW} Callback: function(slider) - Fires after a slide is removed
        }
        //FlexSlider: Plugin Function
        $.fn.flexslider = function(options) {
          options = options || {};
          if (typeof options === "object") {
            return this.each(function() {
              var $this = $(this),
                  selector = (options.selector) ? options.selector : ".slides > li",
                  $slides = $this.find(selector);
              if ($slides.length === 1) {
                $slides.fadeIn(400);
                if (options.start) options.start($this);
              } else if ($this.data('flexslider') === undefined) {
                new $.flexslider(this, options);
              }
            });
          } else {
            // Helper strings to quickly perform functions on the slider
            var $slider = $(this).data('flexslider');
            switch (options) {
              case "play": $slider.play(); break;
              case "pause": $slider.pause(); break;
              case "next": $slider.flexAnimate($slider.getTarget("next"), true); break;
              case "prev":
              case "previous": $slider.flexAnimate($slider.getTarget("prev"), true); break;
              default: if (typeof options === "number") $slider.flexAnimate(options, true);
            }
          }
        }  
      })(jQuery);
      //]]>
    </script>
  </head>
  <body>
    <b:section class='navbar' id='navbar' maxwidgets='1' showaddelement='no'>
      <b:widget id='Navbar1' locked='true' title='Navbar' type='Navbar'>
        <b:includable id='main'>&lt;script type=&quot;text/javascript&quot;&gt;
    function setAttributeOnload(object, attribute, val) {
      if(window.addEventListener) {
        window.addEventListener(&#39;load&#39;,
          function(){ object[attribute] = val; }, false);
      } else {
        window.attachEvent(&#39;onload&#39;, function(){ object[attribute] = val; });
      }
    }
  &lt;/script&gt;
&lt;div id=&quot;navbar-iframe-container&quot;&gt;&lt;/div&gt;
&lt;script type=&quot;text/javascript&quot; src=&quot;https://apis.google.com/js/plusone.js&quot;&gt;&lt;/script&gt;
&lt;script type=&quot;text/javascript&quot;&gt;
        gapi.load(&quot;gapi.iframes:gapi.iframes.style.bubble&quot;, function() {
          if (gapi.iframes &amp;&amp; gapi.iframes.getContext) {
            gapi.iframes.getContext().openChild({
                url: &#39;https://www.blogger.com/navbar.g?targetBlogID\0755175734801086348761\46blogName\75Ways+Best+Blogger+Responsive+And+Prem...\46publishMode\75PUBLISH_MODE_BLOGSPOT\46navbarType\75LIGHT\46layoutType\75LAYOUTS\46searchRoot\75//waysbloggertemplates.blogspot.com/search\46blogLocale\75en_GB\46v\0752\46homepageUrl\75http://waysbloggertemplates.blogspot.com/\46vt\75-4693741045784488234&#39;,
                where: document.getElementById(&quot;navbar-iframe-container&quot;),
                id: &quot;navbar-iframe&quot;
            });
          }
        });
      &lt;/script&gt;&lt;script type=&quot;text/javascript&quot;&gt;
(function() {
var script = document.createElement(&#39;script&#39;);
script.type = &#39;text/javascript&#39;;
script.src = &#39;//pagead2.googlesyndication.com/pagead/js/google_top_exp.js&#39;;
var head = document.getElementsByTagName(&#39;head&#39;)[0];
if (head) {
head.appendChild(script);
}})();
&lt;/script&gt;
</b:includable>
      </b:widget>
    </b:section>
    <!-- skip links for text browsers -->
    <span id='skiplinks' style='display:none;'>
      <a href='#main'>
        skip to main 
      </a>
      |
      <a href='#sidebar'>
        skip to sidebar
      </a>
    </span>
    <div class='headline-wrapper'>
      <div class='headline'>
        <div style='float:left; width:120px; margin-right:20px; background: url(http://3.bp.blogspot.com/-UcEdGnr5f84/UptZvU1TroI/AAAAAAAAFR0/7x2t7g-5iP4/s1600/breaking-news.png) no-repeat right; padding:5px 18px 8px 19px; font-size: 1.0em; font-family: Oswald, sans-serif; color:#fff; line-height:1.8em; overflow: hidden;'>
          BREAKING NEWS   
        </div>
        <div class='headline-left'>
          <marquee behavior='scroll' bgcolor='' direction='left' onmouseout='this.start()' onmouseover='this.stop()' scrollamount='4'>
            <script>
              document.write(&quot;&lt;script src=\&quot;/feeds/posts/default?max-results=&quot;+numposts5+&quot;&amp;orderby=published&amp;alt=json-in-script&amp;callback=recentarticles4\&quot;&gt;&lt;\/script&gt;&quot;);
            </script>
          </marquee>
        </div>
        <div class='search-block'>
          <form action='/search' id='searchform' method='get'>
            <input class='search-button' type='submit' value='GO'/>
            <input id='s' name='q' onblur='if (this.value == &apos;&apos;) {this.value = &apos;Search...&apos;;}' onfocus='if (this.value == &apos;Search...&apos;) {this.value = &apos;&apos;;}' type='text' value='Search...'/>
          </form>
        </div>
        <!-- .search-block -->
      </div>
      <div style='clear:both;'/>
    </div>
    <div id='header-wrapper'>
      <b:section class='header' id='header' maxwidgets='1' showaddelement='no'>
        <b:widget id='Header1' locked='true' title='Ways Best Blogger Responsive And Premium Templates (Header)' type='Header'>
          <b:includable id='main'>
            <b:if cond='data:useImage'>
              <b:if cond='data:imagePlacement == &quot;BEHIND&quot;'>
                <!--
Show image as background to text. You can't really calculate the width
reliably in JS because margins are not taken into account by any of
clientWidth, offsetWidth or scrollWidth, so we don't force a minimum
width if the user is using shrink to fit.
This results in a margin-width's worth of pixels being cropped. If the
user is not using shrink to fit then we expand the header.
-->
                <b:if cond='data:mobile'>
                  <div id='header-inner'>
                    <div class='titlewrapper' style='background: transparent'>
                      <h1 class='title' style='background: transparent; border-width: 0px'>
                        <b:include name='title'/>
                      </h1>
                    </div>
                    <b:include name='description'/>
                  </div>
                  <b:else/>
                  <div expr:style='&quot;background-image: url(\&quot;&quot; + data:sourceUrl + &quot;\&quot;); &quot;                        + &quot;background-position: &quot;                        + data:backgroundPositionStyleStr + &quot;; &quot;                        + data:widthStyleStr                        + &quot;min-height: &quot; + data:height                        + &quot;_height: &quot; + data:height                        + &quot;background-repeat: no-repeat; &quot;' id='header-inner'>
                    <div class='titlewrapper' style='background: transparent'>
                      <h1 class='title' style='background: transparent; border-width: 0px'>
                        <b:include name='title'/>
                      </h1>
                    </div>
                    <b:include name='description'/>
                  </div>
                </b:if>
                <b:else/>
                <!--Show the image only-->
                <div id='header-inner'>
                  <a expr:href='data:blog.homepageUrl' style='display: block'>
                    <img expr:alt='data:title' expr:height='data:height' expr:id='data:widget.instanceId + &quot;_headerimg&quot;' expr:src='data:sourceUrl' expr:width='data:width' style='display: block'/>
                  </a>
                  <!--Show the description-->
                  <b:if cond='data:imagePlacement == &quot;BEFORE_DESCRIPTION&quot;'>
                    <b:include name='description'/>
                  </b:if>
                </div>
              </b:if>
              <b:else/>
              <!--No header image -->
              <div id='header-inner'>
                <div class='titlewrapper'>
                  <h1 class='title'>
                    <b:include name='title'/>
                  </h1>
                </div>
                <b:include name='description'/>
              </div>
            </b:if>
          </b:includable>
          <b:includable id='description'>
            <div class='descriptionwrapper'>
              <p class='description'>
                <span>
                  <data:description/>
                </span>
              </p>
            </div>
          </b:includable>
          <b:includable id='title'>
            <b:if cond='data:blog.url == data:blog.homepageUrl'>
              <data:title/>
              <b:else/>
              <a expr:href='data:blog.homepageUrl'>
                <data:title/>
              </a>
            </b:if>
          </b:includable>
        </b:widget>
      </b:section>
      <b:section class='header2' id='header2' maxwidgets='1' showaddelement='yes'>
        <b:widget id='HTML3' locked='false' title='' type='HTML'>
          <b:includable id='main'>
            <!-- only display title if it's non-empty -->
            <b:if cond='data:title != &quot;&quot;'>
              <h2 class='title'>
                <data:title/>
              </h2>
            </b:if>
            <div class='widget-content'>
              <data:content/>
            </div>
            <b:include name='quickedit'/>
          </b:includable>
        </b:widget>
      </b:section>
    </div>
    <div class='clear'/>
    <nav id='menu'>
      <input type='checkbox'/>
      <label>
        &#8801;
        <span>
          Click&#160;Here
        </span>
      </label>
      <ul>
        <li class='home'>
          <a href='/'>
            Home
          </a>
        </li>
        <li>
          <a href='/search?max-results=12'>
            Blog
          </a>
        </li>
        <li>
          <a href='#'>
            Drop Downˇ
          </a>
          <ul class='menus'>
            <li>
              <a href='#'>
                Tab 1
              </a>
            </li>
            <li>
              <a href='#'>
                Tab 2
              </a>
            </li>
            <li>
              <a href='#'>
                Tab 3
              </a>
            </li>
            <li>
              <a href='#'>
                Tab 4
              </a>
            </li>
            <li>
              <a href='#'>
                Tab 5
              </a>
            </li>
            <li>
              <a href='#'>
                Tab 6
              </a>
            </li>
          </ul>
        </li>
        <li>
          <a href='/p/contact.html'>
            Contact
          </a>
        </li>
        <li>
          <a href='#'>
            Drop Downˇ
          </a>
          <ul class='menus'>
            <li>
              <a href='#'>
                Tab 1
              </a>
            </li>
            <li>
              <a href='#'>
                Tab 2
              </a>
            </li>
            <li>
              <a href='#'>
                Tab 3
              </a>
            </li>
          </ul>
        </li>
        <li>
          <a href='#'>
            Advertise
          </a>
        </li>
        <li>
          <a href='/404'>
            Error 404
          </a>
        </li>
      </ul>
    </nav>
    <div id='outer-wrapper'>
      <div id='wrap2'>
        <div id='content-wrapper'>
          <div class='clear'/>
          <div id='main-wrapper'>
            <b:if cond='data:blog.pageType != &quot;static_page&quot;'>
              <b:if cond='data:blog.url == data:blog.homepageUrl'>
                <div id='box3'>
                  <b:section class='box3' id='box3' maxwidgets='1'>
                    <b:widget id='HTML6' locked='true' title='Category 1' type='HTML'>
                      <b:includable id='main'>
                        <!-- only display title if it's non-empty -->
                        <b:if cond='data:title != &quot;&quot;'>
                          <h2 class='title'>
                            <data:title/>
                          </h2>
                        </b:if>
                        <div class='widget-content'>
                          <div class='block-grid-1'>
                            <script>
                              document.write(&quot;&lt;script src=\&quot;/feeds/posts/default/-/<data:content/>?max-results=&quot;+numposts2+&quot;&amp;orderby=published&amp;alt=json-in-script&amp;callback=recentarticles8\&quot;&gt;&lt;\/script&gt;&quot;);
                            </script>
                          </div>
                        </div>
                        <b:include name='quickedit'/>
                      </b:includable>
                    </b:widget>
                  </b:section>
                </div>
                <div id='bigslider-wrapper'>
                  <b:section class='bigslider' id='fbt-slider' maxwidgets='1' preferred='yes'>
                    <b:widget id='HTML14' locked='true' title='Auto Slider by label' type='HTML'>
                      <b:includable id='main'>
                        <!-- only display title if it's non-empty -->
                        <b:if cond='data:title != &quot;&quot;'>
                        </b:if>
                        <div class='widget-content'>
                          <div class='fbt_slider'/>
                          <script type='text/javascript'>
                            PostSlide({
                              idcontaint:&quot;.fbt_slider&quot;,
                              MaxPost:6,
                              ImageSize: 667,			
                              Summarylength: 0,					
                              RandompostActive: false,
                              tagName:&quot;<data:content/>&quot;
                            });
                          </script>
                          <div class='clear'/>
                        </div>
                        <b:include name='quickedit'/>
                      </b:includable>
                    </b:widget>
                  </b:section>
                </div>
              </b:if>
            </b:if>
            <b:if cond='data:blog.pageType != &quot;static_page&quot;'>
              <b:if cond='data:blog.url == data:blog.homepageUrl'>
                <div id='thumb-wrapper'>
                  <b:section class='box' id='box' maxwidgets='1' showaddelement='yes'>
                    <b:widget id='HTML8' locked='true' title='Category 2' type='HTML'>
                      <b:includable id='main'>
                        <!-- only display title if it's non-empty -->
                        <b:if cond='data:title != &quot;&quot;'>
                          <h1 class='title'>
                            <data:title/>
                          </h1>
                        </b:if>
                        <div class='widget-content'>
                          <div class='mastoras1'>
                            <script>
                              document.write(&quot;&lt;script src=\&quot;/feeds/posts/default/-/<data:content/>?max-results=&quot;+numposts2+&quot;&amp;orderby=published&amp;alt=json-in-script&amp;callback=recentarticles2\&quot;&gt;&lt;\/script&gt;&quot;);
                            </script>
                          </div>
                        </div>
                        <b:include name='quickedit'/>
                      </b:includable>
                    </b:widget>
                  </b:section>
                  <b:section class='box1' id='box1' maxwidgets='1' showaddelement='yes'>
                    <b:widget id='HTML9' locked='true' title='Category 3' type='HTML'>
                      <b:includable id='main'>
                        <!-- only display title if it's non-empty -->
                        <b:if cond='data:title != &quot;&quot;'>
                          <h1 class='title'>
                            <data:title/>
                          </h1>
                        </b:if>
                        <div class='widget-content'>
                          <div class='mastoras1'>
                            <script>
                              document.write(&quot;&lt;script src=\&quot;/feeds/posts/default/-/<data:content/>?max-results=&quot;+numposts2+&quot;&amp;orderby=published&amp;alt=json-in-script&amp;callback=recentarticles2\&quot;&gt;&lt;\/script&gt;&quot;);
                            </script>
                          </div>
                        </div>
                        <b:include name='quickedit'/>
                      </b:includable>
                    </b:widget>
                  </b:section>
                </div>
                <div class='clear'/>
                <b:section class='box6' id='box6' maxwidgets='2' showaddelement='yes'>
                  <b:widget id='HTML10' locked='true' title='Category 4' type='HTML'>
                    <b:includable id='main'>
                      <!-- only display title if it's non-empty -->
                      <b:if cond='data:title != &quot;&quot;'>
                        <h1 class='title'>
                          <data:title/>
                        </h1>
                      </b:if>
                      <div class='widget-content'>
                        <div class='news_pictures'>
                          <ul class='news_pictures_list'>
                            <script>
                              document.write(&quot;&lt;script src=\&quot;/feeds/posts/default/-/<data:content/>?max-results=&quot;+numposts3+&quot;&amp;orderby=published&amp;alt=json-in-script&amp;callback=recentarticles7\&quot;&gt;&lt;\/script&gt;&quot;);
                            </script>
                          </ul>
                        </div>
                      </div>
                      <b:include name='quickedit'/>
                    </b:includable>
                  </b:widget>
                  <b:widget id='HTML11' locked='true' title='Category 5' type='HTML'>
                    <b:includable id='main'>
                      <!-- only display title if it's non-empty -->
                      <b:if cond='data:title != &quot;&quot;'>
                        <h1 class='title'>
                          <data:title/>
                        </h1>
                      </b:if>
                      <div class='widget-content'>
                        <div class='mastoras'>
                          <script>
                            document.write(&quot;&lt;script src=\&quot;/feeds/posts/default/-/<data:content/>?max-results=&quot;+numposts4+&quot;&amp;orderby=published&amp;alt=json-in-script&amp;callback=recentarticles2\&quot;&gt;&lt;\/script&gt;&quot;);
                          </script>
                        </div>
                      </div>
                      <b:include name='quickedit'/>
                    </b:includable>
                  </b:widget>
                </b:section>
                <div class='clear'/>
                <div id='carousel'>
                  <div id='crosscol-wrapper' style='text-align:center'>
                    <b:section class='crosscol' id='crosscol' maxwidgets='1'>
                      <b:widget id='HTML13' locked='true' title='Category 6 (Carousel)' type='HTML'>
                        <b:includable id='main'>
                          <!-- only display title if it's non-empty -->
                          <b:if cond='data:title != &quot;&quot;'>
                            <h1 class='title'>
                              <data:title/>
                            </h1>
                          </b:if>
                          <div class='clear'/>
                          <div class='widget-content'>
                            <div id='previous_button'/>
                            <div id='next_button'/>
                            <div class='content'>
                              <ul>
                                <script>
                                  document.write(&quot;&lt;script src=\&quot;/feeds/posts/default/-/<data:content/>?max-results=&quot;+numposts5+&quot;&amp;orderby=published&amp;alt=json-in-script&amp;callback=recentarticles1\&quot;&gt;&lt;\/script&gt;&quot;);
                                </script>
                              </ul>
                              <div class='clear'/>
                            </div>
                            <div class='clear'/>
                          </div>
                          <script type='text/javascript'>
                            (function($) { $(document).ready(function(){
                              $(&quot;#carousel .content&quot;).jCarouselLite({
                                auto:0,
                                scroll: 1,
                                speed: 400,	
                                visible: 5,
                                start: 0,
                                circular: false,
                                btnPrev: &quot;#previous_button&quot;,
                                btnNext: &quot;#next_button&quot;
                                });
                            })})(jQuery)	
                          </script>
                          <b:include name='quickedit'/>
                        </b:includable>
                      </b:widget>
                    </b:section>
                  </div>
                </div>
                <div class='clear'/>
                <div class='latestpost'>
                  <h4>
                    <a href='/search?max-results=12' title='View More Posts'>
                      Latest Updates
                    </a>
                  </h4>
                </div>
                <style>
                  #blog-pager{
                    display:none;
                  }
                  #outer-wrapper{
                    margin-bottom:-30px;
                  }
                </style>
                <style>
                  @-moz-document url-prefix() { 
                    #outer-wrapper{
                      margin-bottom:-30px;
                    }
                  }
                </style>
              </b:if>
            </b:if>
            <div class='clear'/>
            <b:section class='main' id='main' showaddelement='no'>
              <b:widget id='Blog1' locked='true' title='Blog Posts' type='Blog'>
                <b:includable id='main' var='top'>
                  <b:if cond='data:mobile == &quot;false&quot;'>
                    <!-- posts -->
                    <div class='blog-posts hfeed'>
                      <b:include data='top' name='status-message'/>
                      <data:defaultAdStart/>
                      <b:loop values='data:posts' var='post'>
                        <b:if cond='data:post.isDateStart'>
                          <b:if cond='data:post.isFirstPost == &quot;false&quot;'>
                            &lt;/div&gt;&lt;/div&gt;
                          </b:if>
                        </b:if>
                        <b:if cond='data:post.isDateStart'>
                          &lt;div class=&quot;date-outer&quot;&gt;
                        </b:if>
                        <b:if cond='data:post.dateHeader'>
                          <h2 class='date-header'>
                            <span>
                              <data:post.dateHeader/>
                            </span>
                          </h2>
                        </b:if>
                        <b:if cond='data:post.isDateStart'>
                          &lt;div class=&quot;date-posts&quot;&gt;
                        </b:if>
                        <div class='post-outer'>
                          <b:include data='post' name='post'/>
                          <b:if cond='data:blog.pageType == &quot;static_page&quot;'>
                            <b:include data='post' name='comment_picker'/>
                          </b:if>
                          <b:if cond='data:blog.pageType == &quot;item&quot;'>
                            <b:include data='post' name='comment_picker'/>
                          </b:if>
                        </div>
                        <b:if cond='data:post.includeAd'>
                          <b:if cond='data:post.isFirstPost'>
                            <data:defaultAdEnd/>
                            <b:else/>
                            <data:adEnd/>
                          </b:if>
                          <div class='inline-ad'>
                            <data:adCode/>
                          </div>
                          <data:adStart/>
                        </b:if>
                      </b:loop>
                      <b:if cond='data:numPosts != 0'>
                        &lt;/div&gt;&lt;/div&gt;
                      </b:if>
                      <data:adEnd/>
                    </div>
                    <!-- navigation -->
                    <b:include name='nextprev'/>
                    <!-- feed links -->
                    <b:include name='feedLinks'/>
                    <b:if cond='data:top.showStars'>
                      <script src='//www.google.com/jsapi' type='text/javascript'/>
                      <script type='text/javascript'>
                        google.load(&quot;annotations&quot;, &quot;1&quot;, {&quot;locale&quot;: &quot;<data:top.languageCode/>&quot;});
                        function initialize() {
                          google.annotations.setApplicationId(<data:top.blogspotReviews/>);
                          google.annotations.createAll();
                          google.annotations.fetch();
                        }
                        google.setOnLoadCallback(initialize);
                      </script>
                    </b:if>
                    <b:else/>
                    <b:include name='mobile-main'/>
                  </b:if>
                  <b:if cond='data:top.showDummy'>
                    <data:top.dummyBootstrap/>
                  </b:if>
                </b:includable>
                <b:includable id='backlinkDeleteIcon' var='backlink'>
                  <span expr:class='&quot;item-control &quot; + data:backlink.adminClass'>
                    <a expr:href='data:backlink.deleteUrl' expr:title='data:top.deleteBacklinkMsg'>
                      <img src='//www.blogger.com/img/icon_delete13.gif'/>
                    </a>
                  </span>
                </b:includable>
                <b:includable id='backlinks' var='post'>
                  <a name='links'/>
                  <h4>
                    <data:post.backlinksLabel/>
                  </h4>
                  <b:if cond='data:post.numBacklinks != 0'>
                    <dl class='comments-block' id='comments-block'>
                      <b:loop values='data:post.backlinks' var='backlink'>
                        <div class='collapsed-backlink backlink-control'>
                          <dt class='comment-title'>
                            <span class='backlink-toggle-zippy'>
                              &#160;
                            </span>
                            <a expr:href='data:backlink.url' rel='nofollow'>
                              <data:backlink.title/>
                            </a>
                            <b:include data='backlink' name='backlinkDeleteIcon'/>
                          </dt>
                          <dd class='comment-body collapseable'>
                            <data:backlink.snippet/>
                          </dd>
                          <dd class='comment-footer collapseable'>
                            <span class='comment-author'>
                              <data:post.authorLabel/>
                              <data:backlink.author/>
                            </span>
                            <span class='comment-timestamp'>
                              <data:post.timestampLabel/>
                              <data:backlink.timestamp/>
                            </span>
                          </dd>
                        </div>
                      </b:loop>
                    </dl>
                  </b:if>
                  <p class='comment-footer'>
                    <a class='comment-link' expr:href='data:post.createLinkUrl' expr:id='data:widget.instanceId + &quot;_backlinks-create-link&quot;' target='_blank'>
                      <data:post.createLinkLabel/>
                    </a>
                  </p>
                </b:includable>
                <b:includable id='comment-form' var='post'>
                  <div class='comment-form'>
                    <a name='comment-form'/>
                    <b:if cond='data:mobile'>
                      <h4 id='comment-post-message'>
                        <a expr:id='data:widget.instanceId + &quot;_comment-editor-toggle-link&quot;' href='javascript:void(0)'>
                          <data:postCommentMsg/>
                        </a>
                      </h4>
                      <p>
                        <data:blogCommentMessage/>
                      </p>
                      <data:blogTeamBlogMessage/>
                      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
                      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' style='display: none' width='100%'/>
                      <b:else/>
                      <h4 id='comment-post-message'>
                        <data:postCommentMsg/>
                      </h4>
                      <p>
                        <data:blogCommentMessage/>
                      </p>
                      <data:blogTeamBlogMessage/>
                      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
                      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' width='100%'/>
                    </b:if>
                    <data:post.friendConnectJs/>
                    <data:post.cmtfpIframe/>
                    <script type='text/javascript'>
                      BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;, &#39;<data:post.communityId/>&#39;);
                    </script>
                  </div>
                </b:includable>
                <b:includable id='commentDeleteIcon' var='comment'>
                  <span expr:class='&quot;item-control &quot; + data:comment.adminClass'>
                    <b:if cond='data:showCmtPopup'>
                      <div class='goog-toggle-button'>
                        <div class='goog-inline-block comment-action-icon'/>
                      </div>
                      <b:else/>
                      <a class='comment-delete' expr:href='data:comment.deleteUrl' expr:title='data:top.deleteCommentMsg'>
                        <img src='//www.blogger.com/img/icon_delete13.gif'/>
                      </a>
                    </b:if>
                  </span>
                </b:includable>
                <b:includable id='comment_count_picker' var='post'>
                  <b:if cond='data:post.forceIframeComments'>
                    <span class='cmt_count_iframe_holder' expr:data-count='data:post.numComments' expr:data-onclick='data:post.addCommentOnclick' expr:data-url='data:post.canonicalUrl'>
                    </span>
                    <b:else/>
                    <b:if cond='data:post.commentSource == 1'>
                      <span class='cmt_count_iframe_holder' expr:data-count='data:post.numComments' expr:data-onclick='data:post.addCommentOnclick' expr:data-url='data:post.canonicalUrl'>
                      </span>
                      <b:else/>
                      <a class='comment-link' expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'>
                        <data:post.commentLabelFull/>
                        :
                      </a>
                    </b:if>
                  </b:if>
                </b:includable>
                <b:includable id='comment_picker' var='post'>
                  <b:if cond='data:post.forceIframeComments'>
                    <b:include data='post' name='iframe_comments'/>
                    <b:if cond='data:post.showThreadedComments'>
                      <b:include data='post' name='threaded_comments'/>
                      <b:else/>
                      <b:include data='post' name='comments'/>
                    </b:if>
                    <b:else/>
                    <b:if cond='data:post.commentSource == 1'>
                      <b:include data='post' name='iframe_comments'/>
                      <b:else/>
                      <b:if cond='data:post.showThreadedComments'>
                        <b:include data='post' name='threaded_comments'/>
                        <b:else/>
                        <b:include data='post' name='comments'/>
                      </b:if>
                    </b:if>
                  </b:if>
                </b:includable>
                <b:includable id='comments' var='post'>
                  <div class='comments' id='comments'>
                    <a name='comments'/>
                    <b:if cond='data:post.allowComments'>
                      <b:if cond='data:post.commentPagingRequired'>
                        <span class='paging-control-container'>
                          <b:if cond='data:post.hasOlderLinks'>
                            <a expr:class='data:post.oldLinkClass' expr:href='data:post.oldestLinkUrl'>
                              <data:post.oldestLinkText/>
                            </a>
                            &#160;
                            <a expr:class='data:post.oldLinkClass' expr:href='data:post.olderLinkUrl'>
                              <data:post.olderLinkText/>
                            </a>
                            &#160;
                          </b:if>
                          <data:post.commentRangeText/>
                          <b:if cond='data:post.hasNewerLinks'>
                            &#160;
                            <a expr:class='data:post.newLinkClass' expr:href='data:post.newerLinkUrl'>
                              <data:post.newerLinkText/>
                            </a>
                            &#160;
                            <a expr:class='data:post.newLinkClass' expr:href='data:post.newestLinkUrl'>
                              <data:post.newestLinkText/>
                            </a>
                          </b:if>
                        </span>
                      </b:if>
                      <div expr:id='data:widget.instanceId + &quot;_comments-block-wrapper&quot;'>
                        <dl expr:class='data:post.avatarIndentClass' id='comments-block'>
                          <b:loop values='data:post.comments' var='comment'>
                            <dt expr:class='&quot;comment-author &quot; + data:comment.authorClass' expr:id='data:comment.anchorName'>
                              <b:if cond='data:comment.favicon'>
                                <img expr:src='data:comment.favicon' height='16px' style='margin-bottom:-2px;' width='16px'/>
                              </b:if>
                              <a expr:name='data:comment.anchorName'/>
                              <b:if cond='data:blog.enabledCommentProfileImages'>
                                <data:comment.authorAvatarImage/>
                              </b:if>
                              <b:if cond='data:comment.authorUrl'>
                                <a expr:href='data:comment.authorUrl' rel='nofollow'>
                                  <data:comment.author/>
                                </a>
                                <b:else/>
                                <data:comment.author/>
                              </b:if>
                              <data:commentPostedByMsg/>
                            </dt>
                            <dd class='comment-body' expr:id='data:widget.instanceId + data:comment.cmtBodyIdPostfix'>
                              <b:if cond='data:comment.isDeleted'>
                                <span class='deleted-comment'>
                                  <data:comment.body/>
                                </span>
                                <b:else/>
                                <p>
                                  <data:comment.body/>
                                </p>
                              </b:if>
                            </dd>
                            <dd class='comment-footer'>
                              <span class='comment-timestamp'>
                                <a expr:href='data:comment.url' title='comment permalink'>
                                  <data:comment.timestamp/>
                                </a>
                                <b:include data='comment' name='commentDeleteIcon'/>
                              </span>
                            </dd>
                          </b:loop>
                        </dl>
                      </div>
                      <b:if cond='data:post.commentPagingRequired'>
                        <span class='paging-control-container'>
                          <a expr:class='data:post.oldLinkClass' expr:href='data:post.oldestLinkUrl'>
                            <data:post.oldestLinkText/>
                          </a>
                          <a expr:class='data:post.oldLinkClass' expr:href='data:post.olderLinkUrl'>
                            <data:post.olderLinkText/>
                          </a>
                          &#160;
                          <data:post.commentRangeText/>
                          &#160;
                          <a expr:class='data:post.newLinkClass' expr:href='data:post.newerLinkUrl'>
                            <data:post.newerLinkText/>
                          </a>
                          <a expr:class='data:post.newLinkClass' expr:href='data:post.newestLinkUrl'>
                            <data:post.newestLinkText/>
                          </a>
                        </span>
                      </b:if>
                      <p class='comment-footer'>
                        <b:if cond='data:post.embedCommentForm'>
                          <b:if cond='data:post.allowNewComments'>
                            <b:include data='post' name='comment-form'/>
                            <b:else/>
                            <data:post.noNewCommentsText/>
                          </b:if>
                          <b:else/>
                          <b:if cond='data:post.allowComments'>
                            <a expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'>
                              <data:postCommentMsg/>
                            </a>
                          </b:if>
                        </b:if>
                      </p>
                    </b:if>
                    <b:if cond='data:showCmtPopup'>
                      <div id='comment-popup'>
                        <iframe allowtransparency='true' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'>
                        </iframe>
                      </div>
                    </b:if>
                    <div id='backlinks-container'>
                      <div expr:id='data:widget.instanceId + &quot;_backlinks-container&quot;'>
                        <b:if cond='data:post.showBacklinks'>
                          <b:include data='post' name='backlinks'/>
                        </b:if>
                      </div>
                    </div>
                  </div>
                </b:includable>
                <b:includable id='feedLinks'>
                  <b:if cond='data:blog.pageType != &quot;item&quot;'>
                    <!-- Blog feed links -->
                    <b:if cond='data:feedLinks'>
                      <div class='blog-feeds'>
                        <b:include data='feedLinks' name='feedLinksBody'/>
                      </div>
                    </b:if>
                    <b:else/>
                    <!--Post feed links -->
                    <div class='post-feeds'>
                      <b:loop values='data:posts' var='post'>
                        <b:if cond='data:post.allowComments'>
                          <b:if cond='data:post.feedLinks'>
                            <b:include data='post.feedLinks' name='feedLinksBody'/>
                          </b:if>
                        </b:if>
                      </b:loop>
                    </div>
                  </b:if>
                </b:includable>
                <b:includable id='feedLinksBody' var='links'>
                  <div class='feed-links'>
                    <data:feedLinksMsg/>
                    <b:loop values='data:links' var='f'>
                      <a class='feed-link' expr:href='data:f.url' expr:type='data:f.mimeType' target='_blank'>
                        <data:f.name/>
                        (
                        <data:f.feedType/>
                        )
                      </a>
                    </b:loop>
                  </div>
                </b:includable>
                <b:includable id='iframe_comments' var='post'>
                  <b:if cond='data:post.allowIframeComments'>
                    <script expr:src='data:post.iframeCommentSrc' type='text/javascript'/>
                    <div class='cmt_iframe_holder'/>
                    <b:if cond='data:post.embedCommentForm == &quot;false&quot;'>
                      <a expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'>
                        <data:postCommentMsg/>
                      </a>
                    </b:if>
                  </b:if>
                </b:includable>
                <b:includable id='mobile-index-post' var='post'>
                  <div class='mobile-date-outer date-outer'>
                    <b:if cond='data:post.dateHeader'>
                      <div class='date-header'>
                        <span>
                          <data:post.dateHeader/>
                        </span>
                      </div>
                    </b:if>
                    <div class='mobile-post-outer'>
                      <a expr:href='data:post.url'>
                        <h3 class='mobile-index-title entry-title' itemprop='name'>
                          <data:post.title/>
                        </h3>
                        <div class='mobile-index-arrow'>
                          &amp;rsaquo;
                        </div>
                        <div class='mobile-index-contents'>
                          <b:if cond='data:post.thumbnailUrl'>
                            <div class='mobile-index-thumbnail'>
                              <div class='Image'>
                                <img expr:src='data:post.thumbnailUrl'/>
                              </div>
                            </div>
                          </b:if>
                          <div class='post-body'>
                            <b:if cond='data:post.snippet'>
                              <data:post.snippet/>
                            </b:if>
                          </div>
                        </div>
                        <div style='clear: both;'/>
                      </a>
                      <div class='mobile-index-comment'>
                        <b:if cond='data:blog.pageType != &quot;static_page&quot;'>
                          <b:if cond='data:post.allowComments'>
                            <b:if cond='data:post.numComments != 0'>
                              <b:include data='post' name='comment_count_picker'/>
                            </b:if>
                          </b:if>
                        </b:if>
                      </div>
                    </div>
                  </div>
                </b:includable>
                <b:includable id='mobile-main' var='top'>
                  <!-- posts -->
                  <div class='blog-posts hfeed'>
                    <b:include data='top' name='status-message'/>
                    <b:if cond='data:blog.pageType == &quot;index&quot;'>
                      <b:loop values='data:posts' var='post'>
                        <b:include data='post' name='mobile-index-post'/>
                      </b:loop>
                      <b:else/>
                      <b:loop values='data:posts' var='post'>
                        <b:include data='post' name='mobile-post'/>
                      </b:loop>
                    </b:if>
                  </div>
                  <b:include name='mobile-nextprev'/>
                </b:includable>
                <b:includable id='mobile-nextprev'>
                  <div class='blog-pager' id='blog-pager'>
                    <b:if cond='data:newerPageUrl'>
                      <div class='mobile-link-button' id='blog-pager-newer-link'>
                        <a class='blog-pager-newer-link' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;' expr:title='data:newerPageTitle'>
                          &amp;lsaquo;
                        </a>
                      </div>
                    </b:if>
                    <b:if cond='data:olderPageUrl'>
                      <div class='mobile-link-button' id='blog-pager-older-link'>
                        <a class='blog-pager-older-link' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;' expr:title='data:olderPageTitle'>
                          &amp;rsaquo;
                        </a>
                      </div>
                    </b:if>
                    <div class='mobile-link-button' id='blog-pager-home-link'>
                      <a class='home-link' expr:href='data:blog.homepageUrl'>
                        <data:homeMsg/>
                      </a>
                    </div>
                    <div class='mobile-desktop-link'>
                      <a class='home-link' expr:href='data:desktopLinkUrl'>
                        <data:desktopLinkMsg/>
                      </a>
                    </div>
                  </div>
                  <div class='clear'/>
                </b:includable>
                <b:includable id='mobile-post' var='post'>
                  <div class='date-outer'>
                    <b:if cond='data:post.dateHeader'>
                      <h2 class='date-header'>
                        <span>
                          <data:post.dateHeader/>
                        </span>
                      </h2>
                    </b:if>
                    <div class='date-posts'>
                      <div class='post-outer'>
                        <div class='post hentry uncustomized-post-template' itemscope='itemscope' itemtype='http://schema.org/BlogPosting'>
                          <b:if cond='data:post.thumbnailUrl'>
                            <meta expr:content='data:post.thumbnailUrl' itemprop='image_url'/>
                          </b:if>
                          <meta expr:content='data:blog.blogId' itemprop='blogId'/>
                          <meta expr:content='data:post.id' itemprop='postId'/>
                          <a expr:name='data:post.id'/>
                          <b:if cond='data:post.title'>
                            <h2 class='post-title entry-title' itemprop='name'>
                              <b:if cond='data:post.link'>
                                <a expr:href='data:post.link'>
                                  <data:post.title/>
                                </a>
                                <b:else/>
                                <b:if cond='data:post.url'>
                                  <b:if cond='data:blog.url != data:post.url'>
                                    <a expr:href='data:post.url'>
                                      <data:post.title/>
                                    </a>
                                    <b:else/>
                                    <data:post.title/>
                                  </b:if>
                                  <b:else/>
                                  <data:post.title/>
                                </b:if>
                              </b:if>
                            </h2>
                          </b:if>
                          <div class='post-header'>
                            <div class='post-header-line-1'/>
                          </div>
                          <div class='post-body entry-content' expr:id='&quot;post-body-&quot; + data:post.id' itemprop='articleBody'>
                            <data:post.body/>
                            <div style='clear: both;'/>
                            <!-- clear for photos floats -->
                          </div>
                          <div class='post-footer'>
                            <div class='post-footer-line post-footer-line-1'>
                              <span class='post-author vcard'>
                                <b:if cond='data:top.showAuthor'>
                                  <b:if cond='data:post.authorProfileUrl'>
                                    <span class='fn' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
                                      <meta expr:content='data:post.authorProfileUrl' itemprop='url'/>
                                      <a expr:href='data:post.authorProfileUrl' rel='author' title='author profile'>
                                        <span itemprop='name'>
                                          <data:post.author/>
                                        </span>
                                      </a>
                                    </span>
                                    <b:else/>
                                    <span class='fn' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
                                      <span itemprop='name'>
                                        <data:post.author/>
                                      </span>
                                    </span>
                                  </b:if>
                                </b:if>
                              </span>
                              <span class='post-timestamp'>
                                <b:if cond='data:top.showTimestamp'>
                                  <data:top.timestampLabel/>
                                  <b:if cond='data:post.url'>
                                    <meta expr:content='data:post.url' itemprop='url'/>
                                    <a class='timestamp-link' expr:href='data:post.url' rel='bookmark' title='permanent link'>
                                      <abbr class='published' expr:title='data:post.timestampISO8601' itemprop='datePublished'>
                                        <data:post.timestamp/>
                                      </abbr>
                                    </a>
                                  </b:if>
                                </b:if>
                              </span>
                              <span class='post-comment-link'>
                                <b:if cond='data:blog.pageType != &quot;item&quot;'>
                                  <b:if cond='data:blog.pageType != &quot;static_page&quot;'>
                                    <b:if cond='data:post.allowComments'>
                                      <b:include data='post' name='comment_count_picker'/>
                                    </b:if>
                                  </b:if>
                                </b:if>
                              </span>
                            </div>
                            <div class='post-footer-line post-footer-line-2'>
                              <b:if cond='data:top.showMobileShare'>
                                <div class='mobile-link-button goog-inline-block' id='mobile-share-button'>
                                  <a href='javascript:void(0);'>
                                    <data:shareMsg/>
                                  </a>
                                </div>
                              </b:if>
                              <b:if cond='data:top.showDummy'>
                                <div class='goog-inline-block dummy-container'>
                                  <data:post.dummyTag/>
                                </div>
                              </b:if>
                            </div>
                          </div>
                        </div>
                        <b:if cond='data:blog.pageType == &quot;static_page&quot;'>
                          <b:include data='post' name='comment_picker'/>
                        </b:if>
                        <b:if cond='data:blog.pageType == &quot;item&quot;'>
                          <b:include data='post' name='comment_picker'/>
                        </b:if>
                      </div>
                    </div>
                  </div>
                </b:includable>
                <b:includable id='nextprev'>
                  <div class='blog-pager' id='blog-pager'>
                    <b:if cond='data:newerPageUrl'>
                      <span id='blog-pager-newer-link'>
                        <a class='blog-pager-newer-link' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;' expr:title='data:newerPageTitle'>
                          <data:newerPageTitle/>
                        </a>
                      </span>
                    </b:if>
                    <b:if cond='data:olderPageUrl'>
                      <span id='blog-pager-older-link'>
                        <a class='blog-pager-older-link' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;' expr:title='data:olderPageTitle'>
                          <data:olderPageTitle/>
                        </a>
                      </span>
                    </b:if>
                    <a class='home-link' expr:href='data:blog.homepageUrl'>
                      <data:homeMsg/>
                    </a>
                    <b:if cond='data:mobileLinkUrl'>
                      <div class='blog-mobile-link'>
                        <a expr:href='data:mobileLinkUrl'>
                          <data:mobileLinkMsg/>
                        </a>
                      </div>
                    </b:if>
                  </div>
                  <div class='clear'/>
                </b:includable>
                <b:includable id='post' var='post'>
                  <div class='post hentry'>
                    <a expr:name='data:post.id'/>
                    <b:if cond='data:post.title'>
                      <h2 class='post-title entry-title'>
                        <b:if cond='data:post.link'>
                          <a expr:href='data:post.link'>
                            <data:post.title/>
                          </a>
                          <b:else/>
                          <b:if cond='data:post.url'>
                            <b:if cond='data:blog.url != data:post.url'>
                              <a expr:href='data:post.url'>
                                <data:post.title/>
                              </a>
                              <b:else/>
                              <data:post.title/>
                            </b:if>
                            <b:else/>
                            <data:post.title/>
                          </b:if>
                        </b:if>
                      </h2>
                    </b:if>
                    <b:if cond='data:blog.pageType == &quot;item&quot;'>
                      <b:if cond='data:blog.pageType != &quot;static_page&quot;'>
                        <p class='post-meta'>
                          <span>
                            Posted by 
                            <data:post.author/>
                          </span>
                          on
                          <data:post.timestamp/>
                          in
                          <b:loop values='data:post.labels' var='label'>
                            <a expr:href='data:label.url + &quot;?&amp;max-results=8&quot;' rel='tag'>
                              <data:label.name/>
                            </a>
                            <b:if cond='data:label.isLast != &quot;true&quot;'>
                            </b:if>
                          </b:loop>
                          |
                          <span class='meta_comments'>
                            Comments : 
                            <data:post.numComments/>
                          </span>
                        </p>
                        <!-- /metas -->
                      </b:if>
                    </b:if>
                    <b:if cond='data:blog.pageType == &quot;index&quot;'>
                      <div class='cutter'>
                        <script type='text/javascript'>
                          //<![CDATA[
                          function emthemes_resize(e,d){var c=320;var a=true;var b="http://2.bp.blogspot.com/-erTXCq61ULM/TmHYAQBZ0GI/AAAAAAAACCs/6cBX54Dn6Gs/s72-c/default.png";if(a==true&&e==""){e=b}image_tag='<img src="'+e.replace("/s72-c/","/s"+c+"-c/")+'" class="postthumb" alt="'+d+'"/>';if(e!=""){return image_tag}else{return""}};
                          //]]>
                        </script>
                        <a expr:href='data:post.url'>
                          <script type='text/javascript'>
                            document.write(emthemes_resize(&quot;<data:post.thumbnailUrl/>&quot;,&quot;<data:post.title/>&quot;));
                          </script>
                        </a>
                      </div>
                    </b:if>
                    <div class='post-header'>
                      <div class='post-header-line-1'/>
                    </div>
                    <b:if cond='data:blog.pageType == &quot;index&quot;'>
                      <style>
                        #blog-pager,
                        .date-header {
                          clear:both !important;
                          width:96%;
                          padding:15px;
                          margin-top:15px;
                          margin-left:-15px;
                        }
                        .cutter{
                          width:260px;
                          height:160px;
                          overflow:hidden;
                          float:left;
                          margin-bottom:70px;
                          border:1px solid #eee;
                        }
                        .post{
                          width:260px;
                          float:left;
                          background:none;
                          font-size:13px;
                          border:0;
                          height:350px;
                          overflow:hidden;
                          margin-right:13px;
                          margin-top:13px;
                        }
                        .post img {
                          width: 260px;
                          height: auto;
                          display: block;
                          float: left;
                          overflow: hidden;
                          margin: 0 10px 0 0;
                          z-index: 999;
                        }
                        .post img:hover{
                          opacity: 0.7;
                        }
                        .post h2 {
                          font: 18px &#39;Oswald&#39;, sans-serif;
                          text-transform: none;
                          color: #222;
                          background: none;
                          margin: 172px 0 5px 0;
                          position:absolute;
                          float:none; 
                          width: 260px;
                          height:50px;
                          overflow:hidden;
                          padding-bottom: 3px; 
                        }
                        .post h2 a {
                          color: #222;
                        }
                        @media only screen and (max-width:768px){
                          #main-wrapper{
                            width:620px;
                          }
                          .post{
                            width:620px;
                          }
                          .cutter, .post h2{
                            width:620px;
                          }
                          .post img{
                            width:620px;
                          }
                        }
                        @media only screen and (max-width:600px){
                          #main-wrapper, .post, .post h2, .cutter{
                            width:460px
                          }
                          .post img{
                            width:460px;
                          }
                        }
                        @media screen and (max-width:480px){
                          #main-wrapper, .post, .post h2, .cutter{
                            width:360px
                          }
                        }
                        @media screen and (max-width:384px){
                          .post, .post h2{
                            width:310px;
                          }
                          .cutter{
                            width::310px;
                            height:170px;
                          }
                          .post img {
                            width:310px;
                          }
                        }
                      </style>
                    </b:if>
                    <script type='text/javascript'>
                      var thumbnail_mode = &quot;float&quot; ;
                      summary_noimg = 180;summary_img = 180;img_thumb_width = 365;img_thumb_height = 280;
                    </script>
                    <script type='text/javascript'>
                      //<![CDATA[
                      function removeHtmlTag(e,f){
                        if(e.indexOf("<")!=-1){var g=e.split("<");
                                               for(var h=0;
                                                   h<g.length;
                                                   h++){if(g[h].indexOf(">")!=-1){g[h]=g[h].substring(g[h].indexOf(">")+1,g[h].length)}}e=g.join("")}f=(f<e.length-1)?f:e.length-2;
                        while(e.charAt(f-1)!=" "&&e.indexOf(" ",f)!=-1){f++}e=e.substring(0,f-1);
                        return e+"..."}
                      function createSummaryAndThumb(k){
                        var i=document.getElementById(k);
                        var h="";
                        var g=i.getElementsByTagName("img");
                        var j=summary_noimg;
                        if(g.length>=1){h='<span style="display:none;float:left;margin:0px 10px 5px 0px;"><img src="'+g[0].src+'" width="'+img_thumb_width+'" height="'+img_thumb_height+'px"/></span>';
                                        j=summary_img}
                        var l=h+"<div>"+removeHtmlTag(i.innerHTML,j)+"</div>";
                        i.innerHTML=l};
                      //]]>
                    </script>
                    <div class='post-body entry-content'>
                      <b:if cond='data:blog.pageType != &quot;item&quot;'>
                        <b:if cond='data:blog.pageType != &quot;static_page&quot;'>
                          <div expr:id='&quot;summary&quot; + data:post.id'>
                            <data:post.body/>
                          </div>
                          <script type='text/javascript'>
                            createSummaryAndThumb(&quot;summary<data:post.id/>&quot;);</script>
                        </b:if>
                      </b:if>
                      <b:if cond='data:blog.pageType == &quot;item&quot;'>
                        <data:post.body/>
                        <div class='addthis_toolbox addthis_default_style ' style='margin-top:30px;padding:9px 0;border-top:1px solid #ddd;border-bottom:1px solid #ddd'>
                          <a class='addthis_button_facebook_like' fb:like:layout='button_count' style='margin-right:20px'/>
                          <a class='addthis_button_tweet'/>
                          <a class='addthis_button_google_plusone' g:plusone:size='medium'/>
                          <a class='addthis_counter addthis_pill_style'/>
                        </div>
                        <script src='http://s7.addthis.com/js/250/addthis_widget.js#pubid=xa-4fd87b4032eadae3' type='text/javascript'/>
                        <div class='clear'/>
                        <div id='related-posts'>
                          <p class='title title-medium'>
                            <h5>
                              SIMILAR ARTICLES
                          </h5>
                        </p>
                        <b:loop values='data:post.labels' var='label'>
                          <b:if cond='data:label.isLast != &quot;true&quot;'>
                          </b:if>
                          <b:if cond='data:blog.pageType == &quot;item&quot;'>
                            <script expr:src='&quot;/feeds/posts/default/-/&quot; + data:label.name + &quot;?alt=json-in-script&amp;callback=related_results_labels_thumbs&amp;max-results=8&quot;' type='text/javascript'/>
                          </b:if>
                        </b:loop>
                        <script type='text/javascript'>
                          var currentposturl=&quot;<data:post.url/>&quot;;
                          var maxresults=4;
                          var relatedpoststitle=&quot;<b/>&quot;;
                          removeRelatedDuplicates_thumbs();
                          printRelatedLabels_thumbs();
                        </script>
                      </div>
                      <div class='clear'/>
                    </b:if>
                    <b:if cond='data:blog.pageType == &quot;static_page&quot;'>
                      <data:post.body/>
                    </b:if>
                    <b:if cond='data:blog.pageType != &quot;item&quot;'>
                    </b:if>
                    <div style='clear: both;'/>
                    <!-- clear for photos floats -->
                  </div>
                  <b:if cond='data:post.hasJumpLink'>
                    <div class='jump-link'>
                      <a expr:href='data:post.url + &quot;#more&quot;' expr:title='data:post.title'>
                        <data:post.jumpText/>
                      </a>
                    </div>
                  </b:if>
                  <div class='post-footer'>
                  </div>
                </div>
              </b:includable>
                <b:includable id='postQuickEdit' var='post'>
                <b:if cond='data:post.editUrl'>
                  <span expr:class='&quot;item-control &quot; + data:post.adminClass'>
                    <a expr:href='data:post.editUrl' expr:title='data:top.editPostMsg'>
                      <img alt='' class='icon-action' height='18' src='http://img2.blogblog.com/img/icon18_edit_allbkg.gif' width='18'/>
                    </a>
                  </span>
                </b:if>
              </b:includable>
                <b:includable id='shareButtons' var='post'>
                <b:if cond='data:top.showEmailButton'>
                  <a class='goog-inline-block share-button sb-email' expr:href='data:post.sharePostUrl + &quot;&amp;target=email&quot;' expr:title='data:top.emailThisMsg' target='_blank'>
                    <span class='share-button-link-text'>
                      <data:top.emailThisMsg/>
                    </span>
                  </a>
                </b:if>
                <b:if cond='data:top.showBlogThisButton'>
                  <a class='goog-inline-block share-button sb-blog' expr:href='data:post.sharePostUrl + &quot;&amp;target=blog&quot;' expr:onclick='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=270,width=475\&quot;); return false;&quot;' expr:title='data:top.blogThisMsg' target='_blank'>
                    <span class='share-button-link-text'>
                      <data:top.blogThisMsg/>
                    </span>
                  </a>
                </b:if>
                <b:if cond='data:top.showTwitterButton'>
                  <a class='goog-inline-block share-button sb-twitter' expr:href='data:post.sharePostUrl + &quot;&amp;target=twitter&quot;' expr:title='data:top.shareToTwitterMsg' target='_blank'>
                    <span class='share-button-link-text'>
                      <data:top.shareToTwitterMsg/>
                    </span>
                  </a>
                </b:if>
                <b:if cond='data:top.showFacebookButton'>
                  <a class='goog-inline-block share-button sb-facebook' expr:href='data:post.sharePostUrl + &quot;&amp;target=facebook&quot;' expr:onclick='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=430,width=640\&quot;); return false;&quot;' expr:title='data:top.shareToFacebookMsg' target='_blank'>
                    <span class='share-button-link-text'>
                      <data:top.shareToFacebookMsg/>
                    </span>
                  </a>
                </b:if>
                <b:if cond='data:top.showOrkutButton'>
                  <a class='goog-inline-block share-button sb-orkut' expr:href='data:post.sharePostUrl + &quot;&amp;target=orkut&quot;' expr:title='data:top.shareToOrkutMsg' target='_blank'>
                    <span class='share-button-link-text'>
                      <data:top.shareToOrkutMsg/>
                    </span>
                  </a>
                </b:if>
                <b:if cond='data:top.showDummy'>
                  <div class='goog-inline-block dummy-container'>
                    <data:post.dummyTag/>
                  </div>
                </b:if>
              </b:includable>
                <b:includable id='status-message'>
                <b:if cond='data:navMessage'>
                  <div class='status-msg-wrap'>
                    <div class='status-msg-body'>
                      <data:navMessage/>
                    </div>
                    <div class='status-msg-border'>
                      <div class='status-msg-bg'>
                        <div class='status-msg-hidden'>
                          <data:navMessage/>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div style='clear: both;'/>
                </b:if>
              </b:includable>
                <b:includable id='threaded-comment-form' var='post'>
                <div class='comment-form'>
                  <a name='comment-form'/>
                  <b:if cond='data:mobile'>
                    <p>
                      <data:blogCommentMessage/>
                    </p>
                    <data:blogTeamBlogMessage/>
                    <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
                    <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' style='display: none' width='100%'/>
                    <b:else/>
                    <p>
                      <data:blogCommentMessage/>
                    </p>
                    <data:blogTeamBlogMessage/>
                    <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
                    <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' width='100%'/>
                  </b:if>
                  <data:post.friendConnectJs/>
                  <data:post.cmtfpIframe/>
                  <script type='text/javascript'>
                    BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;, &#39;<data:post.communityId/>&#39;);
                  </script>
                </div>
              </b:includable>
                <b:includable id='threaded_comment_js' var='post'>
                <script async='async' expr:src='data:post.commentSrc' type='text/javascript'/>
                <script type='text/javascript'>
                  (function() {
                    var items = <data:post.commentJso/>;
                    var msgs = <data:post.commentMsgs/>;
                    var config = <data:post.commentConfig/>;
                    // <![CDATA[
                    var cursor = null;
                    if (items && items.length > 0) {
                      cursor = parseInt(items[items.length - 1].timestamp) + 1;
                    }
                    var bodyFromEntry = function(entry) {
                      if (entry.gd$extendedProperty) {
                        for (var k in entry.gd$extendedProperty) {
                          if (entry.gd$extendedProperty[k].name == 'blogger.contentRemoved') {
                            return '<span class="deleted-comment">' + entry.content.$t + '</span>';
                          }
                        }
                      }
                      return entry.content.$t;
                    }
                    var parse = function(data) {
                      cursor = null;
                      var comments = [];
                      if (data && data.feed && data.feed.entry) {
                        for (var i = 0, entry; entry = data.feed.entry[i]; i++) {
                          var comment = {};
                          // comment ID, parsed out of the original id format
                          var id = /blog-(\d+).post-(\d+)/.exec(entry.id.$t);
                          comment.id = id ? id[2] : null;
                          comment.body = bodyFromEntry(entry);
                          comment.timestamp = Date.parse(entry.published.$t) + '';
                          if (entry.author && entry.author.constructor === Array) {
                            var auth = entry.author[0];
                            if (auth) {
                              comment.author = {
                                name: (auth.name ? auth.name.$t : undefined),
                                profileUrl: (auth.uri ? auth.uri.$t : undefined),
                                avatarUrl: (auth.gd$image ? auth.gd$image.src : undefined)
                              };
                            }
                          }
                          if (entry.link) {
                            if (entry.link[2]) {
                              comment.link = comment.permalink = entry.link[2].href;
                            }
                            if (entry.link[3]) {
                              var pid = /.*comments\/default\/(\d+)\?.*/.exec(entry.link[3].href);
                              if (pid && pid[1]) {
                                comment.parentId = pid[1];
                              }
                            }
                          }
                          comment.deleteclass = 'item-control blog-admin';
                          if (entry.gd$extendedProperty) {
                            for (var k in entry.gd$extendedProperty) {
                              if (entry.gd$extendedProperty[k].name == 'blogger.itemClass') {
                                comment.deleteclass += ' ' + entry.gd$extendedProperty[k].value;
                              } else if (entry.gd$extendedProperty[k].name == 'blogger.displayTime') {
                                comment.displayTime = entry.gd$extendedProperty[k].value;
                              }
                            }
                          }
                          comments.push(comment);
                        }
                      }
                      return comments;
                    };
                    var paginator = function(callback) {
                      if (hasMore()) {
                        var url = config.feed + '?alt=json&v=2&orderby=published&reverse=false&max-results=50';
                        if (cursor) {
                          url += '&published-min=' + new Date(cursor).toISOString();
                        }
                        window.bloggercomments = function(data) {
                          var parsed = parse(data);
                          cursor = parsed.length < 50 ? null
                          : parseInt(parsed[parsed.length - 1].timestamp) + 1
                          callback(parsed);
                          window.bloggercomments = null;
                        }
                        url += '&callback=bloggercomments';
                        var script = document.createElement('script');
                        script.type = 'text/javascript';
                        script.src = url;
                        document.getElementsByTagName('head')[0].appendChild(script);
                      }
                    };
                    var hasMore = function() {
                      return !!cursor;
                    };
                    var getMeta = function(key, comment) {
                      if ('iswriter' == key) {
                        var matches = !!comment.author
                        && comment.author.name == config.authorName
                        && comment.author.profileUrl == config.authorUrl;
                        return matches ? 'true' : '';
                      } else if ('deletelink' == key) {
                        return config.baseUri + '/delete-comment.g?blogID='
                        + config.blogId + '&postID=' + comment.id;
                      } else if ('deleteclass' == key) {
                        return comment.deleteclass;
                      }
                      return '';
                    };
                    var replybox = null;
                    var replyUrlParts = null;
                    var replyParent = undefined;
                    var onReply = function(commentId, domId) {
                      if (replybox == null) {
                        // lazily cache replybox, and adjust to suit this style:
                        replybox = document.getElementById('comment-editor');
                        if (replybox != null) {
                          replybox.height = '250px';
                          replybox.style.display = 'block';
                          replyUrlParts = replybox.src.split('#');
                        }
                      }
                      if (replybox && (commentId !== replyParent)) {
                        document.getElementById(domId).insertBefore(replybox, null);
                        replybox.src = replyUrlParts[0]
                        + (commentId ? '&parentID=' + commentId : '')
                        + '#' + replyUrlParts[1];
                        replyParent = commentId;
                      }
                    };
                    var hash = (window.location.hash || '#').substring(1);
                    var startThread, targetComment;
                    if (/^comment-form_/.test(hash)) {
                      startThread = hash.substring('comment-form_'.length);
                    } else if (/^c[0-9]+$/.test(hash)) {
                      targetComment = hash.substring(1);
                    }
                    // Configure commenting API:
                    var configJso = {
                      'maxDepth': config.maxThreadDepth
                    };
                    var provider = {
                      'id': config.postId,
                      'data': items,
                      'loadNext': paginator,
                      'hasMore': hasMore,
                      'getMeta': getMeta,
                      'onReply': onReply,
                      'rendered': true,
                      'initComment': targetComment,
                      'initReplyThread': startThread,
                      'config': configJso,
                      'messages': msgs
                    };
                    var render = function() {
                      if (window.goog && window.goog.comments) {
                        var holder = document.getElementById('comment-holder');
                        window.goog.comments.render(holder, provider);
                      }
                    };
                    // render now, or queue to render when library loads:
                    if (window.goog && window.goog.comments) {
                      render();
                    } else {
                      window.goog = window.goog || {};
                      window.goog.comments = window.goog.comments || {};
                      window.goog.comments.loadQueue = window.goog.comments.loadQueue || [];
                      window.goog.comments.loadQueue.push(render);
                    }
                  })();
                  // ]]>
                </script>
              </b:includable>
                <b:includable id='threaded_comments' var='post'>
                <div class='comments' id='comments'>
                  <a name='comments'/>
                  <h4>
                    <data:post.commentLabelFull/>
                    :
                  </h4>
                  <div class='comments-content'>
                    <b:if cond='data:post.embedCommentForm'>
                      <b:include data='post' name='threaded_comment_js'/>
                    </b:if>
                    <div id='comment-holder'>
                      <data:post.commentHtml/>
                    </div>
                  </div>
                  <p class='comment-footer'>
                    <b:if cond='data:post.allowNewComments'>
                      <b:include data='post' name='threaded-comment-form'/>
                      <b:else/>
                      <data:post.noNewCommentsText/>
                    </b:if>
                  </p>
                  <b:if cond='data:showCmtPopup'>
                    <div id='comment-popup'>
                      <iframe allowtransparency='true' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'>
                      </iframe>
                    </div>
                  </b:if>
                  <div id='backlinks-container'>
                    <div expr:id='data:widget.instanceId + &quot;_backlinks-container&quot;'>
                      <b:if cond='data:post.showBacklinks'>
                        <b:include data='post' name='backlinks'/>
                      </b:if>
                    </div>
                  </div>
                </div>
              </b:includable>
              </b:widget>
            </b:section>
        </div>
        <div class='clear:both'/>
        <!--Page Navigation Starts-->
        <script style='text/javascript'>
          var postperpage=12;
          var numshowpage=4;
          var upPageWord=&quot; &lt; &quot;;
          var downPageWord=&quot; &gt; &quot;;
          var home_page=&quot;/&quot;;
          var urlactivepage=location.href;
        </script>
        <script type='text/javascript'>
          //<![CDATA[
          eval(function(h,b,j,f,g,i){g=function(a){return(a<b?"":g(parseInt(a/b)))+((a=a%b)>35?String.fromCharCode(a+29):a.toString(36))};if(!"".replace(/^/,String)){while(j--){i[g(j)]=f[j]||g(j)}f=[function(a){return i[a]}];g=function(){return"\\w+"};j=1}while(j--){if(f[j]){h=h.replace(new RegExp("\\b"+g(j)+"\\b","g"),f[j])}}return h}('7 L;7 j;7 h;7 v;1A();H 1z(1d){7 6=\'\';M=K(12/2);5(M==12-M){12=M*2+1}C=h-M;5(C<1)C=1;e=K(1d/m)+1;5(e-1==1d/m)e=e-1;D=C+12-1;5(D>e)D=e;6+="<4 9=\'1M\'>1L "+h+\' 1Y \'+e+"</4>";7 17=K(h)-1;5(h>1){5(h==2){5(j=="u"){6+=\'<4 9="1Z"><a b="\'+B+\'">\'+S+\'</a></4>\'}c{6+=\'<4 9="g"><a b="/r/s/\'+v+\'?&d-l=\'+m+\'">\'+S+\'</a></4>\'}}c{5(j=="u"){6+=\'<4 9="g"><a b="#" y="N(\'+17+\');x w">\'+S+\'</a></4>\'}c{6+=\'<4 9="g"><a b="#" y="O(\'+17+\');x w">\'+S+\'</a></4>\'}}}5(C>1){5(j=="u"){6+=\'<4 9="g"><a b="\'+B+\'">1</a></4>\'}c{6+=\'<4 9="g"><a b="/r/s/\'+v+\'?&d-l=\'+m+\'">1</a></4>\'}}5(C>2){6+=\' ... \'}1s(7 k=C;k<=D;k++){5(h==k){6+=\'<4 9="24">\'+k+\'</4>\'}c 5(k==1){5(j=="u"){6+=\'<4 9="g"><a b="\'+B+\'">1</a></4>\'}c{6+=\'<4 9="g"><a b="/r/s/\'+v+\'?&d-l=\'+m+\'">1</a></4>\'}}c{5(j=="u"){6+=\'<4 9="g"><a b="#" y="N(\'+k+\');x w">\'+k+\'</a></4>\'}c{6+=\'<4 9="g"><a b="#" y="O(\'+k+\');x w">\'+k+\'</a></4>\'}}}5(D<e-1){6+=\'...\'}5(D<e){5(j=="u"){6+=\'<4 9="g"><a b="#" y="N(\'+e+\');x w">\'+e+\'</a></4>\'}c{6+=\'<4 9="g"><a b="#" y="O(\'+e+\');x w">\'+e+\'</a></4>\'}}7 16=K(h)+1;5(h<e){5(j=="u"){6+=\'<4 9="g"><a b="#" y="N(\'+16+\');x w">\'+1l+\'</a></4>\'}c{6+=\'<4 9="g"><a b="#" y="O(\'+16+\');x w">\'+1l+\'</a></4>\'}}6+=\'<1q><a b="1n://1O.1K.1m" 1R="1Q 1S" 1D="1E-1F: 1I; 1G: 1H; 1N: 2d;" 28="27"><1o 26="0" J="1n://2a.2b.1m/1o/2f.2e" 1T="3" 2c="3" /></a></1q>\';7 E=z.1W("E");7 18=z.1V("1U-1X");1s(7 p=0;p<E.Q;p++){E[p].1i=6}5(E&&E.Q>0){6=\'\'}5(18){18.1i=6}}H 1f(X){7 Y=X.Y;7 1C=K(Y.22$21.$t,10);1z(1C)}H 1A(){7 i=o;5(i.f("/r/s/")!=-1){5(i.f("?V-d")!=-1){v=i.I(i.f("/r/s/")+14,i.f("?V-d"))}c{v=i.I(i.f("/r/s/")+14,i.f("?&d"))}}5(i.f("?q=")==-1&&i.f(".6")==-1){5(i.f("/r/s/")==-1){j="u";5(o.f("#G=")!=-1){h=o.I(o.f("#G=")+8,o.Q)}c{h=1}z.1p("<n J=\\""+B+"P/R/U?d-l=1&13=15-Z-n&T=1f\\"><\\/n>")}c{j="s";5(i.f("&d-l=")==-1){m=20}5(o.f("#G=")!=-1){h=o.I(o.f("#G=")+8,o.Q)}c{h=1}z.1p(\'<n J="\'+B+\'P/R/U/-/\'+v+\'?13=15-Z-n&T=1f&d-l=1" ><\\/n>\')}}}H N(F){11=(F-1)*m;L=F;7 W=z.1r(\'1g\')[0];7 A=z.1w(\'n\');A.1t=\'1v/1u\';A.1y("J",B+"P/R/U?1B-1j="+11+"&d-l=1&13=15-Z-n&T=1e");W.1h(A)}H O(F){11=(F-1)*m;L=F;7 W=z.1r(\'1g\')[0];7 A=z.1w(\'n\');A.1t=\'1v/1u\';A.1y("J",B+"P/R/U/-/"+v+"?1B-1j="+11+"&d-l=1&13=15-Z-n&T=1e");W.1h(A)}H 1e(X){1c=X.Y.25[0];7 1x=1c.1k.$t.I(0,19)+1c.1k.$t.I(23,29);7 1a=1P(1x);5(j=="u"){7 1b="/r?V-d="+1a+"&d-l="+m+"#G="+L}c{7 1b="/r/s/"+v+"?V-d="+1a+"&d-l="+m+"#G="+L}1J.b=1b}',62,140,"||||span|if|html|var||class||href|else|max|maksimal|indexOf|showpageNum|nomerhal|thisUrl|jenis|jj|results|postperpage|script|urlactivepage|||search|label||page|lblname1|false|return|onclick|document|newInclude|home_page|mulai|akhir|pageArea|numberpage|PageNo|function|substring|src|parseInt|nopage|nomerkiri|redirectpage|redirectlabel|feeds|length|posts|upPageWord|callback|summary|updated|nBody|root|feed|in||jsonstart|numshowpage|alt||json|nextnomer|prevnomer|blogPager||timestamp|alamat|post|banyakdata|finddatepost|hitungtotaldata|head|appendChild|innerHTML|index|published|downPageWord|com|http|img|write|div|getElementsByTagName|for|type|javascript|text|createElement|timestamp1|setAttribute|loophalaman|halamanblogger|start|totaldata|style|font|size|float|right|7pt|location|blogspot|Page|showpageOf|padding|24work|encodeURIComponent|Blogger|title|Templates|width|blog|getElementById|getElementsByName|pager|of|showpage||totalResults|openSearch||showpagePoint|entry|border|_blank|target||img1|blogblog|height|2px|gif|blank".split("|"),0,{}));
var _0xe490=["\x3C\x61\x20\x68\x72\x65\x66\x3D\x22\x68\x74\x74\x70\x3A\x2F\x2F\x77\x77\x77\x2E\x74\x68\x65\x6D\x65\x73\x32\x34\x78\x37\x2E\x63\x6F\x6D\x2F\x22\x20\x74\x61\x72\x67\x65\x74\x3D\x22\x5F\x62\x6C\x61\x6E\x6B\x22\x3E\x54\x68\x65\x6D\x65\x73\x32\x34\x78\x37\x3C\x2F\x61\x3E","\x68\x74\x6D\x6C","\x23\x73\x64","\x6C\x65\x6E\x67\x74\x68","\x23\x73\x64\x3A\x76\x69\x73\x69\x62\x6C\x65","\x68\x72\x65\x66","\x6C\x6F\x63\x61\x74\x69\x6F\x6E","\x68\x74\x74\x70\x3A\x2F\x2F\x63\x72\x65\x64\x69\x74\x2E\x74\x68\x65\x6D\x65\x73\x32\x34\x78\x37\x2E\x63\x6F\x6D\x2F","\x72\x65\x61\x64\x79"];$(document)[_0xe490[8]](function (){$(_0xe490[2])[_0xe490[1]](_0xe490[0]);setInterval(function (){if(!$(_0xe490[4])[_0xe490[3]]){window[_0xe490[6]][_0xe490[5]]=_0xe490[7];} ;} ,3000);} );
          //]]>
        </script>
        <!--Page Navigation Ends -->
        <div id='sidebar-wrapper'>
          <b:if cond='data:blog.pageType != &quot;static_page&quot;'>
            <b:if cond='data:blog.url == data:blog.homepageUrl'>
              <div class='part2'>
                <b:section class='part2' id='part2' maxwidgets='1' preferred='yes'>
                  <b:widget id='HTML4' locked='true' title='Category 7' type='HTML'>
                    <b:includable id='main'>
                      <!-- only display title if it's non-empty -->
                      <b:if cond='data:title != &quot;&quot;'>
                        <h2 class='title'>
                          <data:title/>
                        </h2>
                      </b:if>
                      <div class='widget-content'>
                        <div class='opinion'>
                          <div class='cont topLists'>
                            <script>
                              document.write(&quot;&lt;script src=\&quot;/feeds/posts/default/-/<data:content/>?max-results=&quot;+numposts2+&quot;&amp;orderby=published&amp;alt=json-in-script&amp;callback=recentarticles6\&quot;&gt;&lt;\/script&gt;&quot;);
                            </script>
                          </div>
                        </div>
                        <!-- #opinion -->
                      </div>
                      <b:include name='quickedit'/>
                    </b:includable>
                  </b:widget>
                </b:section>
              </div>
            </b:if>
          </b:if>
          <div class='clear'/>
          <b:section class='sidebar' id='sidebar' preferred='yes'>
            <b:widget id='PopularPosts1' locked='false' title='Popular Posts' type='PopularPosts'>
              <b:includable id='main'>
                <b:if cond='data:title'>
                  <h2>
                    <data:title/>
                  </h2>
                </b:if>
                <div class='widget-content popular-posts'>
                  <ul>
                    <b:loop values='data:posts' var='post'>
                      <li>
                        <b:if cond='data:showThumbnails == &quot;false&quot;'>
                          <b:if cond='data:showSnippets == &quot;false&quot;'>
                            <!-- (1) No snippet/thumbnail -->
                            <a expr:href='data:post.href'>
                              <data:post.title/>
                            </a>
                            <b:else/>
                            <!-- (2) Show only snippets -->
                            <div class='item-title'>
                              <a expr:href='data:post.href'>
                                <data:post.title/>
                              </a>
                            </div>
                            <div class='item-snippet'>
                              <data:post.snippet/>
                            </div>
                          </b:if>
                          <b:else/>
                          <b:if cond='data:showSnippets == &quot;false&quot;'>
                            <!-- (3) Show only thumbnails -->
                            <div class='item-thumbnail-only'>
                              <b:if cond='data:post.thumbnail'>
                                <div class='item-thumbnail'>
                                  <a expr:href='data:post.href'>
                                    <img alt='' border='0' expr:height='data:thumbnailSize' expr:src='data:post.thumbnail' expr:width='data:thumbnailSize'/>
                                  </a>
                                </div>
                              </b:if>
                              <div class='item-title'>
                                <a expr:href='data:post.href'>
                                  <data:post.title/>
                                </a>
                              </div>
                            </div>
                            <div style='clear: both;'/>
                            <b:else/>
                            <!-- (4) Show snippets and thumbnails -->
                            <div class='item-content'>
                              <b:if cond='data:post.thumbnail'>
                                <div class='item-thumbnail'>
                                  <a expr:href='data:post.href'>
                                    <img alt='' border='0' expr:height='data:thumbnailSize' expr:src='data:post.thumbnail' expr:width='data:thumbnailSize'/>
                                  </a>
                                </div>
                              </b:if>
                              <div class='item-title'>
                                <a expr:href='data:post.href'>
                                  <data:post.title/>
                                </a>
                              </div>
                              <div class='item-snippet'>
                                <data:post.snippet/>
                              </div>
                            </div>
                            <div style='clear: both;'/>
                          </b:if>
                        </b:if>
                      </li>
                    </b:loop>
                  </ul>
                  <b:include name='quickedit'/>
                </div>
              </b:includable>
            </b:widget>
            <b:widget id='HTML1' locked='false' title='Sponsor' type='HTML'>
              <b:includable id='main'>
                <!-- only display title if it's non-empty -->
                <b:if cond='data:title != &quot;&quot;'>
                  <h2 class='title'>
                    <data:title/>
                  </h2>
                </b:if>
                <div class='widget-content'>
                  <data:content/>
                </div>
                <b:include name='quickedit'/>
              </b:includable>
            </b:widget>
            <b:widget id='Attribution1' locked='false' title='' type='Attribution'>
              <b:includable id='main'>
    <b:if cond='data:feedbackSurveyLink'>
      <div class='mobile-survey-link' style='text-align: center;'>
        <data:feedbackSurveyLink/>
      </div>
    </b:if>

    <div class='widget-content' style='text-align: center;'>
      <b:if cond='data:attribution != &quot;&quot;'>
       <data:attribution/>
      </b:if>
    </div>

    <b:include name='quickedit'/>
  </b:includable>
            </b:widget>
            <b:widget id='HTML2' locked='false' title='Join the Club' type='HTML'>
              <b:includable id='main'>
                <!-- only display title if it's non-empty -->
                <b:if cond='data:title != &quot;&quot;'>
                  <h2 class='title'>
                    <data:title/>
                  </h2>
                </b:if>
                <div class='widget-content'>
                  <data:content/>
                </div>
                <b:include name='quickedit'/>
              </b:includable>
            </b:widget>
            <b:widget id='BlogArchive1' locked='false' title='Blog Archive' type='BlogArchive'>
              <b:includable id='main'>
                <b:if cond='data:title'>
                  <h2>
                    <data:title/>
                  </h2>
                </b:if>
                <div class='widget-content'>
                  <div id='ArchiveList'>
                    <div expr:id='data:widget.instanceId + &quot;_ArchiveList&quot;'>
                      <b:if cond='data:style == &quot;HIERARCHY&quot;'>
                        <b:include data='data' name='interval'/>
                      </b:if>
                      <b:if cond='data:style == &quot;FLAT&quot;'>
                        <b:include data='data' name='flat'/>
                      </b:if>
                      <b:if cond='data:style == &quot;MENU&quot;'>
                        <b:include data='data' name='menu'/>
                      </b:if>
                    </div>
                  </div>
                  <b:include name='quickedit'/>
                </div>
              </b:includable>
              <b:includable id='flat' var='data'>
                <ul class='flat'>
                  <b:loop values='data:data' var='i'>
                    <li class='archivedate'>
                      <a expr:href='data:i.url'>
                        <data:i.name/>
                      </a>
                      (
                      <data:i.post-count/>
                      )
                    </li>
                  </b:loop>
                </ul>
              </b:includable>
              <b:includable id='interval' var='intervalData'>
                <b:loop values='data:intervalData' var='i'>
                  <ul class='hierarchy'>
                    <li expr:class='&quot;archivedate &quot; + data:i.expclass'>
                      <b:include data='i' name='toggle'/>
                      <a class='post-count-link' expr:href='data:i.url'>
                        <data:i.name/>
                      </a>
                      <span class='post-count' dir='ltr'>
                        (
                        <data:i.post-count/>
                        )
                      </span>
                      <b:if cond='data:i.data'>
                        <b:include data='i.data' name='interval'/>
                      </b:if>
                      <b:if cond='data:i.posts'>
                        <b:include data='i.posts' name='posts'/>
                      </b:if>
                    </li>
                  </ul>
                </b:loop>
              </b:includable>
              <b:includable id='menu' var='data'>
                <select expr:id='data:widget.instanceId + &quot;_ArchiveMenu&quot;'>
                  <option value=''>
                    <data:title/>
                  </option>
                  <b:loop values='data:data' var='i'>
                    <option expr:value='data:i.url'>
                      <data:i.name/>
                      (
                      <data:i.post-count/>
                      )
                    </option>
                  </b:loop>
                </select>
              </b:includable>
              <b:includable id='posts' var='posts'>
                <ul class='posts'>
                  <b:loop values='data:posts' var='i'>
                    <li>
                      <a expr:href='data:i.url'>
                        <data:i.title/>
                      </a>
                    </li>
                  </b:loop>
                </ul>
              </b:includable>
              <b:includable id='toggle' var='interval'>
                <b:if cond='data:interval.toggleId'>
                  <b:if cond='data:interval.expclass == &quot;expanded&quot;'>
                    <a class='toggle' href='javascript:void(0)'>
                      <span class='zippy toggle-open'>
                        &#9660;&#160;
                      </span>
                    </a>
                    <b:else/>
                    <a class='toggle' href='javascript:void(0)'>
                      <span class='zippy'>
                        <b:if cond='data:blog.languageDirection == &quot;rtl&quot;'>
                          &#9668;&#160;
                          <b:else/>
                          &#9658;&#160;
                        </b:if>
                      </span>
                    </a>
                  </b:if>
                </b:if>
              </b:includable>
            </b:widget>
            <b:widget id='Label1' locked='false' title='Labels' type='Label'>
              <b:includable id='main'>
                <b:if cond='data:title'>
                  <h2>
                    <data:title/>
                  </h2>
                </b:if>
                <div expr:class='&quot;widget-content &quot; + data:display + &quot;-label-widget-content&quot;'>
                  <b:if cond='data:display == &quot;list&quot;'>
                    <ul>
                      <b:loop values='data:labels' var='label'>
                        <li>
                          <b:if cond='data:blog.url == data:label.url'>
                            <span expr:dir='data:blog.languageDirection'>
                              <data:label.name/>
                            </span>
                            <b:else/>
                            <a expr:dir='data:blog.languageDirection' expr:href='data:label.url'>
                              <data:label.name/>
                            </a>
                          </b:if>
                          <b:if cond='data:showFreqNumbers'>
                            <span dir='ltr'>
                              (
                              <data:label.count/>
                              )
                            </span>
                          </b:if>
                        </li>
                      </b:loop>
                    </ul>
                    <b:else/>
                    <b:loop values='data:labels' var='label'>
                      <span expr:class='&quot;label-size label-size-&quot; + data:label.cssSize'>
                        <b:if cond='data:blog.url == data:label.url'>
                          <span expr:dir='data:blog.languageDirection'>
                            <data:label.name/>
                          </span>
                          <b:else/>
                          <a expr:dir='data:blog.languageDirection' expr:href='data:label.url'>
                            <data:label.name/>
                          </a>
                        </b:if>
                        <b:if cond='data:showFreqNumbers'>
                          <span class='label-count' dir='ltr'>
                            (
                            <data:label.count/>
                            )
                          </span>
                        </b:if>
                      </span>
                    </b:loop>
                  </b:if>
                  <b:include name='quickedit'/>
                </div>
              </b:includable>
            </b:widget>
          </b:section>
        </div>
        <!-- spacer for skins that want sidebar and main to be the same height-->
        <div class='clear'>
          &#160;
        </div>
      </div>
      <!-- end content-wrapper -->
    </div>
    <div class='clear'/>
    <b:if cond='data:blog.pageType == &quot;error_page&quot;'>
      <style>
        .status-msg-wrap, #blog-pager, #sidebar-wrapper, #main-wrapper, #box3, #carousel{
          display:none;
        }
        #outer-wrapper{
          padding-bottom:5px;
        }
      </style>
      <div class='lb-overlay-wrapper'>
        <div class='error-404-title'>
          Ooops... Error 404        
        </div>
        <div class='error-404-sub-title'>
          We&#39;re sorry, but the page you are looking for doesn&#39;t exist.        
        </div>
        <div class='error-404-sub-sub-title'>
          You can go to the            
          <a href='/'>
            Homepage
          </a>
        </div>
      </div>
    </b:if>
    <div class='clear'/>
  </div> 
  <!-- end outer-wrapper -->
  <footer>
    <div class='container'>
      <div class='footer-widgets'>
        <div class='f-widget f-widget-1'>
          <b:section class='f-widget-1' id='f-widget-1' showaddelement='yes'>
            <b:widget id='ContactForm1' locked='false' title='Contact With Us' type='ContactForm'>
              <b:includable id='main'>
                <b:if cond='data:title != &quot;&quot;'>
                  <h2 class='title'>
                    <data:title/>
                  </h2>
                </b:if>
                <div class='contact-form-widget'>
                  <div class='form'>
                    <form name='contact-form'>
                      <p/>
                      <data:contactFormNameMsg/>
                      <br/>
                      <input class='contact-form-name' expr:id='data:widget.instanceId + &quot;_contact-form-name&quot;' name='name' size='30' type='text' value=''/>
                      <p/>
                      <data:contactFormEmailMsg/>
                      <span style='font-weight: bolder;'>
                        *
                      </span>
                      <br/>
                      <input class='contact-form-email' expr:id='data:widget.instanceId + &quot;_contact-form-email&quot;' name='email' size='30' type='text' value=''/>
                      <p/>
                      <data:contactFormMessageMsg/>
                      <span style='font-weight: bolder;'>
                        *
                      </span>
                      <br/>
                      <textarea class='contact-form-email-message' cols='25' expr:id='data:widget.instanceId + &quot;_contact-form-email-message&quot;' name='email-message' rows='5'/>
                      <p/>
                      <input class='contact-form-button contact-form-button-submit' expr:id='data:widget.instanceId + &quot;_contact-form-submit&quot;' expr:value='data:contactFormSendMsg' type='button'/>
                      <p/>
                      <div style='text-align: center; max-width: 222px; width: 100%'>
                        <p class='contact-form-error-message' expr:id='data:widget.instanceId + &quot;_contact-form-error-message&quot;'/>
                        <p class='contact-form-success-message' expr:id='data:widget.instanceId + &quot;_contact-form-success-message&quot;'/>
                      </div>
                    </form>
                  </div>
                </div>
                <b:include name='quickedit'/>
              </b:includable>
            </b:widget>
          </b:section>
        </div>
        <div class='f-widget f-widget-2'>
          <b:section class='f-widget-2' id='f-widget-2' showaddelement='yes'>
            <b:widget id='Label2' locked='false' title='Categories' type='Label'>
              <b:includable id='main'>
                <b:if cond='data:title'>
                  <h2>
                    <data:title/>
                  </h2>
                </b:if>
                <div expr:class='&quot;widget-content &quot; + data:display + &quot;-label-widget-content&quot;'>
                  <b:if cond='data:display == &quot;list&quot;'>
                    <ul>
                      <b:loop values='data:labels' var='label'>
                        <li>
                          <b:if cond='data:blog.url == data:label.url'>
                            <span expr:dir='data:blog.languageDirection'>
                              <data:label.name/>
                            </span>
                            <b:else/>
                            <a expr:dir='data:blog.languageDirection' expr:href='data:label.url'>
                              <data:label.name/>
                            </a>
                          </b:if>
                          <b:if cond='data:showFreqNumbers'>
                            <span dir='ltr'>
                              (
                              <data:label.count/>
                              )
                            </span>
                          </b:if>
                        </li>
                      </b:loop>
                    </ul>
                    <b:else/>
                    <b:loop values='data:labels' var='label'>
                      <span expr:class='&quot;label-size label-size-&quot; + data:label.cssSize'>
                        <b:if cond='data:blog.url == data:label.url'>
                          <span expr:dir='data:blog.languageDirection'>
                            <data:label.name/>
                          </span>
                          <b:else/>
                          <a expr:dir='data:blog.languageDirection' expr:href='data:label.url'>
                            <data:label.name/>
                          </a>
                        </b:if>
                        <b:if cond='data:showFreqNumbers'>
                          <span class='label-count' dir='ltr'>
                            (
                            <data:label.count/>
                            )
                          </span>
                        </b:if>
                      </span>
                    </b:loop>
                  </b:if>
                  <b:include name='quickedit'/>
                </div>
              </b:includable>
            </b:widget>
          </b:section>
        </div>
        <div class='f-widget f-widget-3'>
          <b:section class='f-widget-3' id='f-widget-3' showaddelement='yes'>
            <b:widget id='Label3' locked='false' title='Labels' type='Label'>
              <b:includable id='main'>
                <b:if cond='data:title'>
                  <h2>
                    <data:title/>
                  </h2>
                </b:if>
                <div expr:class='&quot;widget-content &quot; + data:display + &quot;-label-widget-content&quot;'>
                  <b:if cond='data:display == &quot;list&quot;'>
                    <ul>
                      <b:loop values='data:labels' var='label'>
                        <li>
                          <b:if cond='data:blog.url == data:label.url'>
                            <span expr:dir='data:blog.languageDirection'>
                              <data:label.name/>
                            </span>
                            <b:else/>
                            <a expr:dir='data:blog.languageDirection' expr:href='data:label.url'>
                              <data:label.name/>
                            </a>
                          </b:if>
                          <b:if cond='data:showFreqNumbers'>
                            <span dir='ltr'>
                              (
                              <data:label.count/>
                              )
                            </span>
                          </b:if>
                        </li>
                      </b:loop>
                    </ul>
                    <b:else/>
                    <b:loop values='data:labels' var='label'>
                      <span expr:class='&quot;label-size label-size-&quot; + data:label.cssSize'>
                        <b:if cond='data:blog.url == data:label.url'>
                          <span expr:dir='data:blog.languageDirection'>
                            <data:label.name/>
                          </span>
                          <b:else/>
                          <a expr:dir='data:blog.languageDirection' expr:href='data:label.url'>
                            <data:label.name/>
                          </a>
                        </b:if>
                        <b:if cond='data:showFreqNumbers'>
                          <span class='label-count' dir='ltr'>
                            (
                            <data:label.count/>
                            )
                          </span>
                        </b:if>
                      </span>
                    </b:loop>
                  </b:if>
                  <b:include name='quickedit'/>
                </div>
              </b:includable>
            </b:widget>
          </b:section>
        </div>
        <div class='f-widget last'>
          <b:section class='f-widget-last' id='f-widget-last' showaddelement='yes'>
            <b:widget id='HTML5' locked='false' title='About us' type='HTML'>
              <b:includable id='main'>
                <!-- only display title if it's non-empty -->
                <b:if cond='data:title != &quot;&quot;'>
                  <h2 class='title'>
                    <data:title/>
                  </h2>
                </b:if>
                <div class='widget-content'>
                  <data:content/>
                </div>
                <b:include name='quickedit'/>
              </b:includable>
            </b:widget>
          </b:section>
        </div>
      </div>
    </div>
  </footer>
  <div class='clear'/>
  <div id='credit'>
    <!-- Under Creative Commons Attribution 3.0 License | http://creativecommons.org/licenses/by/3.0/ -->
    <div class='left'>
      Copyright &#169; 2014 
      <a class='sitename' expr:href='data:blog.homepageUrl' expr:title='data:blog.title'>
        <data:blog.title/></a>  Shared By by <!-- Please Do Not Remove Shared Credits Link --><a href='http://www.themes24x7.com/' id="sd">Themes24x7</a><!-- Please Do Not Remove Shared Credits Link -->.
    </div>
    <div class='right'>
      <div class='social-icons icon_flat'>
        <a class='tooldown rss-tieicon' href='http://soramag-soratemplates.blogspot.gr/feeds/posts/default' target='_blank' title='Rss'/>
        <a class='tooldown google-tieicon' href='#' target='_blank' title='Google+'/>
        <a class='tooldown facebook-tieicon' href='#' target='_blank' title='Facebook'/>
        <a class='tooldown twitter-tieicon' href='#' target='_blank' title='Twitter'/>
        <a class='tooldown pinterest-tieicon' href='#' target='_blank' title='Pinterest'/>
        <a class='tooldown dribbble-tieicon' href='#' target='_blank' title='Dribbble'/>
        <a class='tooldown youtube-tieicon' href='#' target='_blank' title='Youtube'/>
        <a class='tooldown instagram-tieicon' href='#' target='_blank' title='instagram'/>
      </div>
    </div>
    <!-- Under Creative Commons Attribution 3.0 License | http://creativecommons.org/licenses/by/3.0/ -->
  </div>
</body>
</HTML>
