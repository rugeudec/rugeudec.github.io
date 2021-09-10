<!DOCTYPE html>
<html xmlns="https://www.w3.org/1999/xhtml">
<head>
 
<!--
 
Theme:  Lightsome by @mhango | @themesbyeva
        Version 1 (26th Jan. 2021) 
 
Rules:
 
> don't alter / remove any credit
> don't copy parts of this theme or use as a base code
> don't edit this theme and redistribute
> don't claim as your own
 
Credits / Resources:
 
> Base Code 
    @shythemes
> PXU Photosets
    https://github.com/PixelUnion/Extended-Tumblr-Photoset
    Edited by @bychloethemes
> Infinite Scroll
    https://infinite-scroll.com
> Masonry
    https://masonry.desandro.com
> Icons
    icons8.com
> Fonts
    fonts.google.com
> Scroll To Top
    @painthemes
> Custom Tooltips
    @htmlqueens
> Hide / Show Effect
    @sophiasthemage
> Un-nested tumblr captions
    @neothm, @magnusthemes
 
-->
 
<title>{Title}</title>
<link rel="alternate" type="application/rss+xml" href="{RSS}">
<link rel="shortcut icon" href="{Favicon}">
{block:Description}
<meta name="description" content="{MetaDescription}">
{/block:Description}
 
<link href="https://static.tumblr.com/wgijwsy/k1Hm9ei8b/normalize.css" rel="stylesheet" type="text/css" />
 
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery-smooth-scroll/1.7.2/jquery.smooth-scroll.min.js"></script>
 
<meta name="viewport" content="width=device-width, initial-scale=1">
 
<meta name="image:Background" content="" />
<meta name="image:Topbar Background" content="" />
<meta name="image:Topbar Icon" content="" />
 
<meta name="color:Background" content="#ffffff" />
<meta name="color:Text" content="#000000" />
<meta name="color:Link" content="#000000" />
<meta name="color:Link Hover" content="#c9b6c2" />
<meta name="color:Accent" content="#97738a" />
<meta name="color:Blockquote" content="#eddde7" />
<meta name="color:Blogtitle" content="#000000" />
<meta name="color:Post Borders" content="#eddde7" />
<meta name="color:Post Background" content="#f9f1f6" />
<meta name="color:Post Overlay" content="#000000" />
<meta name="color:Footer Background" content="#f9f1f6" />
<meta name="color:Topbar Text" content="#000000" />
<meta name="color:Topbar Background" content="#f9f1f6" />
<meta name="color:Topbar Borders" content="#eddde7" />
<meta name="color:Topbar Buttons" content="#f9f1f6" />
<meta name="color:Tooltip Text" content="#000000" />
<meta name="color:Tooltip Background" content="#eddde7" />
<meta name="color:Tooltip Borders" content="#dfcbd8" />
<meta name="color:Scrollbar" content="#eddde7" />
<meta name="color:Text Highlight" content="#c9b9c3" />
 
<meta name="if:Infinite Scroll" content="1">
<meta name="if:Fixed Header" content="0">
<meta name="if:Dark Tumblr Controls" content="0">
<meta name="if:News Tab" content="1"/>
<meta name="if:Stats Tab" content="1"/>
<meta name="if:Blogs Tab" content="1"/>
<meta name="if:Groups Tab" content="1"/>
<meta name="if:Always Show Tabs" content="0"/>
<meta name="if:Show Topbar Icon" content="0"/>
<meta name="if:Two Columns" content="0">
<meta name="if:Three Columns" content="1">
<meta name="if:Four Columns" content="0">
 
<meta name="text:News Title" content="NEWS" />
<meta name="text:News Text" content="your news go here" />
<meta name="text:Stats Title" content="STATS" />
<meta name="text:Stats Text" content="your stats go here" />
<meta name="text:Blogs Title" content="BLOGS" />
<meta name="text:Blog 1 Username" content="" />
<meta name="text:Blog 2 Username" content="" />
<meta name="text:Blog 3 Username" content="" />
<meta name="text:Blog 4 Username" content="" />
<meta name="text:Groups Title" content="GROUPS" />
<meta name="text:Group 1 Badge Code" content="badge code" />
<meta name="text:Group 2 Badge Code" content="badge code" />
<meta name="text:Group 3 Badge Code" content="badge code" />
<meta name="text:Group 4 Badge Code" content="badge code" />
 
<meta name="text:home title" content="home" />
<meta name="text:ask title" content="ask" />
<meta name="text:ask link" content="/ask" />
<meta name="text:submit title" content="" />
<meta name="text:archive title" content="past" />
<meta name="text:link 1 title" content="" />
<meta name="text:link 1" content="" />
<meta name="text:link 2 title" content="" />
<meta name="text:link 2" content="" />
<meta name="text:link 3 title" content="" />
<meta name="text:link 3" content="" />
<meta name="text:link 4 title" content="" />
<meta name="text:link 4" content="" />
<meta name="text:link 5 title" content="" />
<meta name="text:link 5" content="" />
<meta name="text:link 6 title" content="" />
<meta name="text:link 6" content="" />
 
<meta name="select:Body Font" content="'Arimo', Helvetica, Arial, sans-serif" title="Arimo">
<meta name="select:Body Font" content="'Avalon', Helvetica, Arial, sans-serif" title="Avalon">
<meta name="select:Body Font" content="'Gudea', Helvetica, Arial, sans-serif" title="Gudea">
<meta name="select:Body Font" content="'Imprima', Helvetica, Arial, sans-serif" title="Imprima">
<meta name="select:Body Font" content="'Karla', Helvetica, Arial, sans-serif" title="Karla">
<meta name="select:Body Font" content="'Lato', Helvetica, Arial, sans-serif" title="Lato">
<meta name="select:Body Font" content="'Muli', Helvetica, Arial, sans-serif" title="Muli">
<meta name="select:Body Font" content="'Quicksand', Helvetica, Arial, sans-serif" title="Quicksand">
<meta name="select:Body Font" content="'Raleway', Helvetica, Arial, sans-serif" title="Raleway">
<meta name="select:Body Font" content="'Roboto', Helvetica, Arial, sans-serif" title="Roboto">
<meta name="select:Body Font" content="'Source Serif Pro', Times New Roman, Times, serif" title="Source Serif Pro">
 
<meta name="select:Title Font" content="'DM Serif Text', Helvetica, Arial, sans-serif" title="DM Serif Text">
<meta name="select:Title Font" content="'Lexend Deca', Helvetica, Arial, sans-serif" title="Lexend Deca">
<meta name="select:Title Font" content="'Montserrat', Helvetica, Arial, sans-serif" title="Montserrat">
<meta name="select:Title Font" content="'Oswald', Helvetica, Arial, sans-serif" title="Oswald">
<meta name="select:Title Font" content="'Playfair Display', Helvetica, Arial, sans-serif" title="Playfair Display">
<meta name="select:Title Font" content="'Poiret One', Helvetica, Arial, sans-serif" title="Poiret One">
<meta name="select:Title Font" content="'Roboto Slab', Helvetica, Arial, sans-serif" title="Roboto Slab">
 
<!-- google fonts -->
 
<link rel="preconnect" href="https://fonts.gstatic.com">
<link href="https://fonts.googleapis.com/css2?family=Arimo:wght@400;700&family=Gudea:wght@400;700&family=Imprima&family=Karla:wght@400;700&family=Lato:wght@400;700&family=Mulish:wght@400;700&family=Quicksand:wght@400;700&family=Raleway:wght@400;700&family=Roboto:wght@400;700&family=Source+Serif+Pro:wght@400;700&display=swap" rel="stylesheet">
 
<link rel="preconnect" href="https://fonts.gstatic.com">
<link href="https://fonts.googleapis.com/css2?family=DM+Serif+Text&family=Lexend+Deca&family=Montserrat:wght@400;700&family=Oswald:wght@400;700&family=Playfair+Display:wght@400;700&family=Poiret+One&family=Roboto+Slab:wght@400;700&display=swap" rel="stylesheet">
 
<link rel="stylesheet" type="text/css" href="https://assets.tumblr.com/fonts/avalon/stylesheet.css?v=1">
 
<!-- jquery library + hide / show effect -->
 
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.7.1/jquery.min.js"></script>
 
{block:ifnotalwaysshowtabs}
<script>
$(document).ready(function(){
$("#newsclick").click(function(){
$("#newsshow").slideToggle("slow");
});
});
$(document).ready(function(){
$("#statsclick").click(function(){
$("#statsshow").slideToggle("slow");
});
});
$(document).ready(function(){
$("#blogsclick").click(function(){
$("#blogsshow").slideToggle("slow");
});
});
$(document).ready(function(){
$("#groupsclick").click(function(){
$("#groupsshow").slideToggle("slow");
});
});
</script>
{/block:ifnotalwaysshowtabs}
 
<style type="text/css">
 
body {
    background: {color:Background} url('{image:Background}');
    background-attachment:fixed;
    background-repeat:repeat;
    color: {color:text};
    font-family: {select:body font};
    font-size: 12px;
    margin: 0;
    padding: 0;
    -moz-osx-font-smoothing:grayscale;
    -webkit-font-smoothing:antialiased;
    font-smoothing:antialiased;
}
 
a:link, a:active, a:visited {
    color: {color:link};
    text-decoration: none;
    outline: none;
    -webkit-transition: all 0.5s ease-in-out;
    -moz-transition: all 0.5s ease-in-out;
    -o-transition: all 0.5s ease-in-out;
    -ms-transition: all 0.5s ease-in-out;
    transition: all 0.5s ease-in-out;
}
 
a:hover{
    color:{color:link hover};
    -webkit-transition: all 0.5s ease-in-out;
    -moz-transition: all 0.5s ease-in-out;
    -o-transition: all 0.5s ease-in-out;
    -ms-transition: all 0.5s ease-in-out;
    transition: all 0.5s ease-in-out;
 
}
 
small, sub {
    font-size:1em;
    vertical-align:baseline;
}
 
cite {
    font-style:normal;
}
 
blockquote {
    margin: 0;
    padding-left: 2%;
    padding-right:2%;
    border-left:1px solid {color:blockquote};
}
 
blockquote, ol, ul, p, pre {
    margin:0 0 .6em;
}
 
h1, h2, h3, h4, h5, h6 {
    margin:0 0 .6em;
    font-size:1.2em;
    font-weight:inherit;
    font-family: {select:title font};
}
 
.tumblr_video_container {
    max-width: 100%!important;
    height:auto;
}
 
iframe, img, embed, object, video {
    max-width: 100%;
}
 
img {
    border:0;
    max-width:100%;
    height:auto;
    display:block;
}
 
hr {
    margin:1em 0;
    border:0;
    height:1px;
    -moz-box-sizing:border-box;
    box-sizing:border-box;
    background-color:{color:border};
}
 
::-webkit-scrollbar-thumb{
    background-color: {color:scrollbar};
    border: 2px solid {color:background};
    height:auto;
    -moz-border-radius: 20%;
    border-radius: 20%;
}
 
::-webkit-scrollbar {
    height:auto;
    width:8px;
    background-color: {color:background};
    border: 4px solid {color:background};
}
 
::-moz-selection {
    background: {color:Text highlight};
    color: {color:text};
}
 
::selection {
    background: {color:Text highlight};
    color: {color:text};
}
 
#scroll:link, #scroll:visited {
    display: none;
    position: fixed;
    bottom: 20px;
    right: 20px;
    width:25px;
    z-index:999999;
}
 
#s-m-t-tooltip {
    font-weight:600;
    font-family: {select:body font};
    font-size:0.9em;
    color: {color:tooltip text};
    background-color:{color:tooltip background};
    text-align: center;
    max-width:150px;
    border: 1px solid {color:tooltip borders};
    overflow:auto;
    text-transform:none;
     letter-spacing:0.028em;
    position: absolute;
    z-index: 999999999999;
    padding: .33em .66em .33em .66em;
    box-shadow:0 0 rgba(0,0,0,0.2);
    -webkit-transition: all 0.2s ease-in-out;
    -moz-transition: all 0.2s ease-in-out;
    transition: all 0.2s ease-in-out;
    margin:20px 0 15px 10px;
}  
 
#content {
    {block:iffixedheader}
    {block:ifnotshowtopbaricon}
    margin-top:170px;
    {/block:ifnotshowtopbaricon}
    {block:ifshowtopbaricon}
    margin-top:calc(170px + 70px);
    {/block:ifshowtopbaricon}
    {/block:iffixedheader}
    {block:ifnotfixedheader}
    margin-top:25px;
    {/block:ifnotfixedheader}
    float: center;
    position:absolute;
    height:100%;
    z-index:9999;
    {block:indexpage}
    margin-left: 50%;
    transform: translate(-50%);
    width: min(60%,500px);
    {block:iftwocolumns}
    width: min(60%,1070px);
    {/block:iftwocolumns}
    {block:ifthreecolumns}
    width: min(60%,1600px);
    {/block:ifthreecolumns}
    {block:iffourcolumns}
    width: min(60%,2090px);
    {/block:iffourcolumns}
    {/block:indexpage}
    {block:permalinkpage}
    width:min(30%,500px);
    margin-left: 50%;
    transform: translate(-50%);
    {/block:permalinkpage}
}
 
@-webkit-keyframes cssAnimation {
    from{
    -webkit-transform: scale(0.871);}
    to{
    -webkit-transform:scale(1); }
}
 
@-moz-keyframes cssAnimation {
    from{
    -moz-transform:scale(0.871);}
    to{
    -moz-transform:  scale(1); }
}
 
@-o-keyframes cssAnimation {
    from{
    -o-transform: scale(0.871);
}
 
    to{
    -o-transform: scale(1);}
}
 
.entry {
    position:relative;
    background: {color:Background};
    max-width:500px;
    border:none;
    height:auto;
    margin: 20px 0;
    padding: 0;
    {block:indexpage}
    width: 18vw;
    -webkit-animation: cssAnimation 1s 1 ease-in-out;
    -moz-animation: cssAnimation 1s 1 ease-in-out;
    -o-animation: cssAnimation 1s 1 ease-in-out;
    {/block:indexpage}
    {block:PermalinkPage}
    width:100%;
    height:auto;
    padding: 0;
    {/block:PermalinkPage}
}
 
{block:indexpage}
 
.gutter-sizer {
    width: 0px;
}
 
.grid-sizer, .entry {
    width: 100%;
} 
 
{block:iftwocolumns}
.gutter-sizer {
    width: 70px;
}
 
.grid-sizer, .entry {
    width: calc((100% - 70px) / 2);
}
{/block:iftwocolumns}
 
{block:ifthreecolumns}
.gutter-sizer {
    width: 50px;
}
 
.grid-sizer, .entry {
    width: calc((100% - 100px) / 3);
}
{/block:ifthreecolumns}
 
{block:iffourcolumns}
.gutter-sizer {
    width: 30px;
}
 
.grid-sizer, .entry {
    width: calc((100% - 90px) / 4);
}
{/block:iffourcolumns}
 
{/block:indexpage}
 
.entry:last-child {
    margin-bottom:5px;
}
 
#overlay{
    position:absolute;
    left:0px;
    top:0px;
    height:100%;
    width:100%;
    background: rgba({RGBcolor:Post Overlay}, 0);
    box-sizing:border-box;
    z-index:999;
    -webkit-transition: all .5s ease-in-out;
    -moz-transition: all .5s ease-in-out;
    -ms-transition: all .5s ease-in-out;
    -o-transition: all .5s ease-in-out;
    transition: all .5s ease-in-out;
}
 
.entry:hover #overlay {   
    {block:indexpage}
    background: rgba({RGBcolor:Post Overlay}, 0.5);
    -webkit-transition: all .5s ease-in-out;
    -moz-transition: all .5s ease-in-out;
    -ms-transition: all .5s ease-in-out;
    -o-transition: all .5s ease-in-out;
    transition: all .5s ease-in-out;
    {/block:indexpage}
}
 
.permabutton, .reblogbutton {
    {block:indexpage}
    position:absolute;
    width:auto;
    display:inline-block;
    padding: 8px;
    height:25px;
    border: 1px solid transparent;
    border-radius:100%;
    z-index:999999;
    -webkit-transition: all 0.5s ease-in-out;
    -moz-transition: all 0.5s ease-in-out;
    -o-transition: all 0.5s ease-in-out;
    -ms-transition: all 0.5s ease-in-out;
    transition: all 0.5s ease-in-out;
    font-size:10px;
    font-weight:700;
    text-transform:uppercase;
    margin:8px;
    opacity:0;
    {/block:indexpage}
}
 
.permabutton {
    left:40%;
    top:50%;
    margin-top:-22px;
    margin-left:-32px;
}
 
.reblogbutton {
    right:40%;
    top:50%;
    margin-top:-22px;
    margin-right:-32px;
}
 
.permabutton img, .reblogbutton img {
    height:25px;
    vertical-align:middle;
}
 
.permabutton a, .permabutton a:visited, 
.reblogbutton a, .reblogbutton a:visited {
    color: {color:text};
    text-decoration: none;
    -webkit-transition: all 0.5s ease-in-out;
    -moz-transition: all 0.5s ease-in-out;
    -o-transition: all 0.5s ease-in-out;
    -ms-transition: all 0.5s ease-in-out;
    transition: all 0.5s ease-in-out;
}
 
.permabutton:hover, .reblogbutton:hover {
    background:{color:accent};
    border: 1px solid {color:accent};
    border-radius:100%;
    -webkit-transition: all 0.5s ease-in-out;
    -moz-transition: all 0.5s ease-in-out;
    -o-transition: all 0.5s ease-in-out;
    -ms-transition: all 0.5s ease-in-out;
    transition: all 0.5s ease-in-out;
}
 
.entry:hover .permabutton, .entry:hover .reblogbutton {
    {block:indexpage}
    opacity:1;
    -webkit-transition: all 0.5s ease-in-out;
    -moz-transition: all 0.5s ease-in-out;
    -o-transition: all 0.5s ease-in-out;
    -ms-transition: all 0.5s ease-in-out;
    transition: all 0.5s ease-in-out;
    {/block:indexpage}
 
}
 
/* audio / video post perma */
 
.permainfo, .rebloginfo {
    {block:indexpage}
    opacity:1;
    margin-top:-8px;
    margin-left:3px;
    margin-right:3px;
    font-size:11px;
    text-transform:none;
    display:inline-block;
    color: {color:text};
    padding-bottom:2px;
    -webkit-transition: all 0.5s ease-in-out;
    -moz-transition: all 0.5s ease-in-out;
    -o-transition: all 0.5s ease-in-out;
    -ms-transition: all 0.5s ease-in-out;
    transition: all 0.5s ease-in-out;
    {/block:indexpage}
}
 
.permainfo {
    {block:indexpage}
    float:left;
    {/block:indexpage}
}
 
.rebloginfo {
    {block:indexpage}
    float:right;
    {/block:indexpage}
}
 
.rebloginfo:hover, .permainfo:hover {
    color: {color:link hover};
    -webkit-transition: all 0.5s ease-in-out;
    -moz-transition: all 0.5s ease-in-out;
    -o-transition: all 0.5s ease-in-out;
    -ms-transition: all 0.5s ease-in-out;
    transition: all 0.5s ease-in-out;
}
 
.notebox {
    background:{color:Post Background};
    border:1px solid {color:post borders};
    -moz-border-radius: 3%;
    border-radius:3%;
    width:auto;
    height:auto;
    padding:15px 10px;
}
 
{block:indexpage}
.photoset #overlay {
    height: calc(100% - 2px);
}
 
.photoset {
    margin-bottom:-2px;
}
{/block:indexpage}
 
 
{block:permalinkpage}
.details {
    background:{color:footer background};
    border-top:1px solid {color:footer background};
    border-bottom:1px solid {color:blockquote};
    border-left:1px solid {color:blockquote};
    border-right:1px solid {color:blockquote};
    padding-bottom:10px;
}
 
.photoset {
    margin-bottom:-3px;
}
{/block:permalinkpage}
 
#topbar {
    background:{color:Topbar background} url('{image:Topbar Background}');
    padding: 1%;
    color: {color:Topbar text};
    height:auto;
    width: min(58%,1546px);
    font-size:1.1em;
    line-height:1.2em;
    top: 0;
    {block:iffixedheader}
    position:fixed;
    {/block:iffixedheader}
    {block:ifnotfixedheader}
    position:relative;
    {/block:ifnotfixedheader}
    margin-left: 50%;
    transform: translate(-50%);
    text-align:center;
    border:1px solid {color:Topbar Borders};
    z-index:99999;
}
 
.topblock {
    margin-top:15px;
    text-align:center;
}
 
.sideicon {
    width:70px;
    height:70px;
    margin:-20px auto 20px auto;
}
 
.sideicon img {
    width:70px;
    height:70px;
    border:1px solid {color:Topbar Borders};
    -moz-border-radius: 100%;
    border-radius:100%;
}
 
.blogtitle a {
    padding:5px;
    font-size:1.8em;
    font-weight:normal;
    font-family:{select:title font};
    color: {color:blogtitle};
    -webkit-transition: all 0.5s ease-in-out;
    -moz-transition: all 0.5s ease-in-out;
    -o-transition: all 0.5s ease-in-out;
    -ms-transition: all 0.5s ease-in-out;
    transition: all 0.5s ease-in-out;
}
 
.blogtitle a:hover{
    color:{color:link hover};
    -webkit-transition: all 0.5s ease-in-out;
    -moz-transition: all 0.5s ease-in-out;
    -o-transition: all 0.5s ease-in-out;
    -ms-transition: all 0.5s ease-in-out;
    transition: all 0.5s ease-in-out;
}
 
.description {
    margin:15px 18%;
}
 
.navigation {
    text-align:center;
    text-transform:none;
    padding: 0 15%;
}
 
.navigation a {
    color: {color:Topbar text};
    -webkit-transition: all 0.5s ease-in-out;
    -moz-transition: all 0.5s ease-in-out;
    -o-transition: all 0.5s ease-in-out;
    -ms-transition: all 0.5s ease-in-out;
    transition: all 0.5s ease-in-out;
}
 
.nav {
    display:inline-block;
    width:80px;
    padding:3px 8px;
    margin:8px 10px;
    line-height:150%;
    border:1px solid {color:Topbar Borders};
    -moz-border-radius: 3%;
    border-radius:3%;
    background:{color:Topbar buttons};
    -webkit-transition: all 0.5s ease-in-out;
    -moz-transition: all 0.5s ease-in-out;
    -o-transition: all 0.5s ease-in-out;
    -ms-transition: all 0.5s ease-in-out;
    transition: all 0.5s ease-in-out;
}
 
.nav:hover{
    background:{color:Topbar Borders};
    -webkit-transition: all 0.5s ease-in-out;
    -moz-transition: all 0.5s ease-in-out;
    -o-transition: all 0.5s ease-in-out;
    -ms-transition: all 0.5s ease-in-out;
    transition: all 0.5s ease-in-out;
}
 
nav li {
    display:inline;
}
 
#rightbar {
    background:transparent;
    padding: 1.250vw;
    color: {color:Topbar text};
    width: 10vw;
    height:100%;
    line-height:1.2em;
    top: 0;
    right: 0;
    position:fixed;
    margin-top:3vh;
    margin-right:3vw;
}
 
.plugin {
    position:relative;
    display:block;
    margin:20px 10px;
    width:10vw;
}
 
.plugin img {
    width:28px;
    height:auto;
    border-radius:100%;
    -moz-border-radius: 100%;
    display:inline-block;
    padding:0 2px;
}
 
.plugin_title {
    background:{color:Topbar background};
    border:1px solid {color:Topbar Borders};
    -moz-border-radius: 3%;
    border-radius:3%;
    padding:8px 10px;
    text-align:center;
}
 
.plugin_body {
    background:{color:background};
    border:1px solid {color:Topbar Borders};
    border-top:0px;
    -moz-border-radius: 3%;
    border-radius:3%;
    padding:8px 10px;
}
 
{block:ifnotalwaysshowtabs}
#statsclick,#blogsclick, #newsclick, #groupsclick {cursor:help;}
#statsshow, #blogsshow, #newsshow, #groupsshow {display:none;}
{/block:ifnotalwaysshowtabs}
 
.title {
    padding-top:0px;
    padding-bottom:5px;
    font-size:1.5em;
    font-weight:normal;
    font-family:{select:title font};
}
 
.title a {
    color:{color:text};
}
 
.title img {
    width:15px;
}
 
.accent,
.tumblr_blog {
    color:{color:accent};
}
 
.text {
    background:{color:Post Background}; 
    padding: 15px;
    border:1px solid {color:post borders};
}
 
.text a, .text img {
    max-width:100%;
}
 
.text:last-child,
.text *:last-child {
    margin-bottom:0;
}
 
.text img {
    text-align:center;
    margin:auto;
}
 
.question {
    padding-bottom:7px;
    border-bottom: 1px solid {color:post borders};
}
 
.asker, .asker a {
    color:{color:accent};
    font-weight:700;
    margin-bottom:5px;
}
 
.quotetext {
    font-size:1.1em;
    font-weight:700;
    font-family: {select:title font};
}
 
.quotesource {
    padding-top:5px;
    padding-bottom:5px;
}
 
.chat {
    background:{color:Post Background}; 
    padding: 15px;
    border:1px solid {color:Post Borders};
}
 
.chat .label {
    font-weight:700;
}
 
.chat span {
    float: left;
    margin-right: 1%;
}
 
.spotify_audio_player, .soundcloud_audio_player {
    margin-bottom:-3px;
}
 
.spotify_audio_player {
    height:80px!important;
    width:100%!important;
}
 
.soundcloud_audio_player {
    height:150px!important;
    width:100%!important;
}
 
#notes {
    margin-top:5px;
    display:inline-block;
}
 
#notes img {
    display:inline-block;
}
 
.notes {
    clear: both;
    padding: 0;
}
 
ol.notes { 
    list-style-type:none;
    line-height:150%;
    padding:0;
    margin 0 0;
    border-bottom:solid 1px {color:blockquote};
}
 
ol.notes li.note {
    border-top:1px solid {color:blockquote};
    padding:5px;
}
 
ol.notes li.note img {
    padding:0 !important;
}
 
ol.notes li.note img.avatar {
    vertical-align:-4px;
    margin-right:5px;
    width:16px;
    height:16px;
}
 
#tags {
    text-align:left;
    opacity: 1;
}
 
#tags, nav ul, .chat ul {
    list-style: none;
    list-style-image: none;
    margin: 0;
    padding: 0;
}
 
#tags li {
    float: left;
    margin-right: 1%;
}
 
.caption {
    margin:10px 20px;
}
 
.caption ul {
    list-style: none;
    list-style-image: none;
    margin: 0;
    padding: 0; 
    line-height:150%;
}
 
.infoheading {
    font-weight:700;
    color:{color:text};
    -moz-osx-font-smoothing:grayscale;
    -webkit-font-smoothing:antialiased;
    font-smoothing:antialiased;
}
 
.media {
    position:relative;
    display:inline-block;
    width:100%;
}
 
.tmblr-iframe-compact .tmblr-iframe--unified-controls {
    position:fixed!important;
    opacity:.67!important;
    padding:4px;
    z-index:99999999999999999999999;
    {block:ifdarktumblrcontrols}
    -webkit-filter:invert(100%);
    -moz-filter:invert(100%);
    -o-filter:invert(100%);
    -ms-filter:invert(100%);
    filter:invert(100%);
    {/block:ifdarktumblrcontrols}
}
 
.tmblr-iframe--controls-phone-container,
.iframe-controls--phone-mobile,
.tmblr-iframe--app-cta-button {
    z-index:999999999999999999999999999999999999999999999999999999!important;
    position:fixed!important;
    margin:0!important;
}
 
{block:ifInfiniteScroll}
.pagination,
#infscr-loading {
    display:none!important;
}
{/block:ifInfiniteScroll}
 
{block:ifnotInfiniteScroll}
.pagination {
    margin-bottom:0;
    text-align:center;
    width:auto;
    z-index:9999999999999999999999999999;
}
 
.pagination img {
    width:20px;
    display:inline-block;
    padding:10px;
}
 
#sitenav {
    background:{color:Topbar background};
    color: {color:Topbar text};
    padding:0px 1%;
    height:auto;
    font-size:1.1em;
    line-height:1.2em;
    bottom: 0;
    position:fixed;
    text-align:center;
    z-index:99999;
    width: min(58%,1546px);
    margin-left: 50%;
    transform: translate(-50%);
    border:1px solid {color:Topbar Borders};
}
 
@media only screen and (max-width:900px){
    #sitenav {
        width:100%;
        max-width:100vw;
        overflow-x:hidden;
    }
}   
 
{/block:ifnotInfiniteScroll}
 
#important {
    bottom:15px;
    left:15px;
    width:15px;
    font-size:0.9em;
    position:fixed;
    z-index:9999999999999999999999999999;
}
 
@media only screen and (max-width:900px) {
 
    body {
        max-width:100vw;
        overflow-x:hidden;
    }
 
    #content {
        max-width:100%;
        width:min(80%,500px);
        margin-top:25px;
        background:{color:background};
        height:auto;
    }    
 
    .gutter-sizer {
        width: 0px;
    }
 
    .grid-sizer, .entry {
        width: calc((100% - 0px));
    } 
 
    #topbar {
        width:100%;
        max-width:100vw;
        overflow-x:hidden;
        position:relative;
        margin-top:auto;
    }
 
    .navigation {
        padding: 0 5%;
}
 
 
    #rightbar {
        display:none;
    } 
 
    .sideicon {
        display:none;
    }
 
    .nav {
        min-width:40px;
        width:auto;
    }
 
    #scroll:link, #scroll:visited {
        bottom:10px;
        right:5px;
    }
 
    #important {
        bottom:10px;
        left:5px;
    }
 
}
 
</style>
 
<link href="https://static.tumblr.com/qudkd6d/OcDnl99gb/style.css" rel="stylesheet" type="text/css">
 
</head>
 
<body>
 
<header id="topbar">
 
<div class="topblock">
 
{block:ifshowtopbaricon}<div class="sideicon"><img src="{image:topbar icon}"></div>{/block:ifshowtopbaricon}
 
<div class="blogtitle"><a href="/">{Title}</a></div>
 
{block:Description}
<div class="description">{Description}</div>
{block:Description}
 
 
<div class="navigation">
 
{block:ifhometitle} 
<a href="/"><div class="nav">{text:home title}</div></a>
{/block:ifhometitle}
 
{block:ifasktitle}
<a href="{text:ask link}"><div class="nav">{text:ask title}</div></a>
{/block:ifasktitle}
 
{block:ifsubmittitle}
<a href="/submit"><div class="nav">{text:Submit title}</div></a>
{/block:ifsubmittitle}
 
{block:ifarchivetitle}
<a href="/archive"><div class="nav">{text:archive title}</div></a>
{/block:ifarchivetitle}
 
{block:iflink1}<a href="{text:link 1}"><div class="nav">{text:link 1 title}</div></a>{/block:iflink1}
{block:iflink2}<a href="{text:link 2}"><div class="nav">{text:link 2 title}</div></a>{/block:iflink2}
{block:iflink3}<a href="{text:link 3}"><div class="nav">{text:link 3 title}</div></a>{/block:iflink3}
{block:iflink4}<a href="{text:link 4}"><div class="nav">{text:link 4 title}</div></a>{/block:iflink4}
{block:iflink5}<a href="{text:link 5}"><div class="nav">{text:link 5 title}</div></a>{/block:iflink5}
{block:iflink6}<a href="{text:link 6}"><div class="nav">{text:link 6 title}</div></a>{/block:iflink6}
 
<!--  {block:HasPages}
{block:Pages}
<div class="nav"><a href="{URL}">{Label}</a>
{/block:Pages}
{/block:HasPages}-->
 
</div>
 
</div>
 
</header>
 
 
<div id="sitenav">
{block:Pagination}<div class="pagination">{block:PreviousPage}<a class="prev" href="{PreviousPage}" title="previous"><img src="https://img.icons8.com/ios/50/000000/circled-left-2.png"/></a>{/block:PreviousPage} {block:NextPage}<a class="next" href="{NextPage}" title="next"><img src="https://img.icons8.com/ios/50/000000/circled-right-2.png"/></a>{/block:NextPage}</div>{/block:Pagination}
</div>
 
 
<aside id="rightbar">
    {block:ifnewstab}<div class="plugin">
        <div id="newsclick" class="plugin_title">{text:news title}</div>
        <div id="newsshow" class="plugin_body">{text:news text}</div>
    </div>
    {/block:ifnewstab}
    {block:ifstatstab}<div class="plugin">
        <div id="statsclick" class="plugin_title">{text:stats title}</div>
        <div id="statsshow" class="plugin_body">{text:stats text}</div>
    </div>
    {/block:ifstatstab}
    {block:ifblogstab}<div class="plugin">
        <div  id="blogsclick" class="plugin_title">{text:blogs title}</div>
        <div  id="blogsshow" class="plugin_body">
        <center>
{block:ifblog1username}<a href="https://{text:blog 1 username}.tumblr.com" title="{text:blog 1 username}" target="_blank"><img src="https://api.tumblr.com/v2/blog/{text:blog 1 username}.tumblr.com/avatar/512"></a>{/block:ifblog1username}
{block:ifblog2username}<a href="https://{text:blog 2 username}.tumblr.com" title="{text:blog 2 username}" target="_blank"><img src="https://api.tumblr.com/v2/blog/{text:blog 2 username}.tumblr.com/avatar/512"></a>{/block:ifblog2username} 
{block:ifblog3username}<a href="https://{text:blog 3 username}.tumblr.com" title="{text:blog 3 username}" target="_blank"><img src="https://api.tumblr.com/v2/blog/{text:blog 3 username}.tumblr.com/avatar/512"></a>{/block:ifblog3username} 
{block:ifblog4username}<a href="https://{text:blog 4 username}.tumblr.com" title="{text:blog 4 username}" target="_blank"><img src="https://api.tumblr.com/v2/blog/{text:blog 4 username}.tumblr.com/avatar/512"></a>{/block:ifblog4username} 
        </center>
        </div>
    </div>
    {/block:ifblogstab}
    {block:ifgroupstab}<div class="plugin">
        <div id="groupsclick" class="plugin_title">{text:groups title}</div>
        <div id="groupsshow" class="plugin_body">
        <center>
{block:ifGroup1badgecode}{text:Group 1 Badge Code}{/block:ifGroup1badgecode}
{block:ifGroup2badgecode}{text:Group 2 Badge Code}{/block:ifGroup2badgecode}
{block:ifGroup3badgecode}{text:Group 3 Badge Code}{/block:ifGroup3badgecode}
{block:ifGroup4badgecode}{text:Group 4 Badge Code}{/block:ifGroup4badgecode}
        </center>
        </div>
    </div>
    {/block:ifgroupstab}
</aside>
 
<div id="content">
 
{block:Posts}
 
{block:ContentSource}<!-- {SourceURL}
{block:SourceLogo}<img src="{BlackLogoURL}"width="{LogoWidth}" height="{LogoHeight}" alt="{SourceTitle}" />{/block:SourceLogo}
{block:NoSourceLogo}{SourceLink}{/block:NoSourceLogo} -->
{/block:ContentSource}
 
<!-- {block:NoRebloggedFrom}
{block:RebloggedFrom}{ReblogParentName}{/block:RebloggedFrom}
{/block:NoRebloggedFrom} -->
 
<article class="entry {block:Photo}ph{/block:Photo}{block:Photoset}ph{/block:Photoset}" id="{PostID}">
 
<div class="grid-sizer"></div>
<div class="gutter-sizer"></div>
 
{block:Text}
 
<div class="text">
{block:Title}<div class="title"><a href="{Permalink}">{Title}</a></div>{/block:Title}<div class="textbody">
{Body}</div>
{block:indexpage}<div id="overlay"></div>
<div class="permabutton"><a href="{Permalink}" title="{notecountwithlabel}"><img src="https://img.icons8.com/ios/50/ffffff/link--v1.png"/></a></div><div class="reblogbutton"><a href="{ReblogURL}" target="_blank" title="reblog"><img src="https://img.icons8.com/ios/50/ffffff/synchronize.png"/></a></div>{/block:indexpage}
</div>
{/block:Text}
 
{block:Photo}
 
<div class="photo">
{LinkOpenTag}<a href="{permalink}"><img src="{PhotoURL-500}" alt="{PhotoAlt}"/></a>{LinkCloseTag}
{block:indexpage}
<div id="overlay"></div>
<div class="permabutton"><a href="{Permalink}" title="{notecountwithlabel}"><img src="https://img.icons8.com/ios/50/ffffff/link--v1.png"/></a></div><div class="reblogbutton"><a href="{ReblogURL}" target="_blank" title="reblog"><img src="https://img.icons8.com/ios/50/ffffff/synchronize.png"/></a></div>{/block:indexpage}
 
</div>
{/block:Photo}
 
{block:Photoset}
<div class="media photoset">
<div class="photo-slideshow" id="photoset_{PostID}" data-layout="{PhotosetLayout}">{block:Photos}<div class="photo-data"><div class="pxu-photo"><img src="{PhotoURL-500}" width="{PhotoWidth-500}" height="{PhotoHeight-500}" data-highres="{PhotoURL-HighRes}" data-width="{PhotoWidth-HighRes}" data-height="{PhotoHeight-HighRes}"></div><a class="tumblr-box" rel="post-{PostID}" href="{PhotoURL-HighRes}"></a></div>{/block:Photos}
{block:indexpage}<div id="overlay"></div>
<div class="permabutton"><a href="{Permalink}" title="{notecountwithlabel}"><img src="https://img.icons8.com/ios/50/ffffff/link--v1.png"/></a></div><div class="reblogbutton"><a href="{ReblogURL}" target="_blank" title="reblog"><img src="https://img.icons8.com/ios/50/ffffff/synchronize.png"/></a></div>
{/block:IndexPage}
</div>
</div>
{/block:Photoset}
 
{block:Quote}
 
<div class="text">
<div class="textpost">
<div class="quotetext">{Quote}</div>
<div class="quotesource">{block:Source}<cite>{Source}</cite>{/block:Source}</div></div>
{block:indexpage}<div id="overlay"></div>
<div class="permabutton"><a href="{Permalink}" title="{notecountwithlabel}"><img src="https://img.icons8.com/ios/50/ffffff/link--v1.png"/></a></div><div class="reblogbutton"><a href="{ReblogURL}" target="_blank" title="reblog"><img src="https://img.icons8.com/ios/50/ffffff/synchronize.png"/></a></div>{/block:indexpage}
</div>
{/block:Quote}
 
{block:Link}
 
<div class="text">
<div class="title"><a href="{URL}">{Name}</div>
{block:Description}{Description}{/block:Description}
{block:indexpage}<div id="overlay"></div>
<div class="permabutton"><a href="{Permalink}" title="{notecountwithlabel}"><img src="https://img.icons8.com/ios/50/ffffff/link--v1.png"/></a></div><div class="reblogbutton"><a href="{ReblogURL}" target="_blank" title="reblog"><img src="https://img.icons8.com/ios/50/ffffff/synchronize.png"/></a></div>{/block:indexpage}
</div>
{/block:Link}
 
{block:Chat}
 
<div class="chat">
<div class="textpost">
{block:Title}<div class="title"><a href="{Permalink}">{Title}</a></div>{/block:Title}
<ul>
{block:Lines}<li class="{Alt}">{block:Label}<span class="label">{Label}</span>{/block:Label}<p> {Line} </p></li>{/block:Lines}
</ul></div>
{block:indexpage}<div id="overlay"></div>
<div class="permabutton"><a href="{Permalink}" title="{notecountwithlabel}"><img src="https://img.icons8.com/ios/50/ffffff/link--v1.png"/></a></div><div class="reblogbutton"><a href="{ReblogURL}" target="_blank" title="reblog"><img src="https://img.icons8.com/ios/50/ffffff/synchronize.png"/></a></div>{/block:indexpage}
</div>
{/block:Chat}
 
{block:Audio}
 
<div class="audio">
<div class="textpost">
{block:TrackName}{TrackName} by{/block:TrackName} {block:Artist}{Artist} <br><br>{/block:Artist}
{AudioPlayerGrey}</div>
{block:indexpage}<div class="notebox"><a href="{Permalink}"><div class="permainfo">{notecountwithlabel}</div></a><a href="{ReblogURL}" target="_blank"><div class="rebloginfo">reblog</div></a></div>{/block:indexpage}
</div>
{/block:Audio}
 
{block:Video}
 
<div class="video">
<div class="video-player">{Video-500}</div>
{block:indexpage}<div class="notebox"><a href="{Permalink}"><div class="permainfo">{notecountwithlabel}</div></a><a href="{ReblogURL}" target="_blank"><div class="rebloginfo">reblog</div></a></div>{/block:indexpage}
</div>
{/block:Video}
 
{block:Answer}
 
<div class="text">
<div class="question"><p><div class="asker">{Asker} said:&nbsp;</div>{Question}</div></p>
{Answer}
{block:indexpage}<div id="overlay"></div>
<div class="permabutton"><a href="{Permalink}" title="{notecountwithlabel}"><img src="https://img.icons8.com/ios/50/ffffff/link--v1.png"/></a></div><div class="reblogbutton"><a href="{ReblogURL}" target="_blank" title="reblog"><img src="https://img.icons8.com/ios/50/ffffff/synchronize.png"/></a></div>{/block:indexpage}
</div>
{/block:Answer}
 
{block:Date}
<div class="details">
{block:PermalinkPage}
<div class="caption">
<div class="blogcaption">{block:caption}{Caption}{/block:caption}</div>
<ul>
{block:HasTags}<li><div id="tags"><span class="infoheading">Tags:</span> {block:Tags}<a href="{TagURL}">#{Tag} </a> {/block:Tags}</div></li>{/block:HasTags}
<li><span class="infoheading">Posted:</span> {timeago}</li>
{block:NoteCount}<li><span class="infoheading">Notecount:</span> {notecount}</li>{/block:NoteCount}
{block:RebloggedFrom}<li><span class="infoheading">Via:</span> <a href="{ReblogParentURL}" target="_blank">{ReblogParentName}</a></li>{/block:RebloggedFrom}
{block:ContentSource}<li><span class="infoheading">Source:</span> <a href="{SourceURL}" target="_blank">{SourceTitle}</a></li>{/block:ContentSource}
</ul>
{block:PostNotes}<div id="notes">{PostNotes-16}</div>{/block:PostNotes}
</div>
{/block:PermalinkPage}
</div>{/block:Date}
 
</article>
 
{/block:Posts}
 
 
</div>
 
<!-- Codes for Infinite Scroll, Masonry, PXU Photosets, etc. -->
 
<!--<script src="https://static.tumblr.com/qudkd6d/Az6nkemqr/pxuphotoset.min.js"></script>-->
<script src="https://static.tumblr.com/yxfeliq/hHwojmt8m/bctphotoset.min.js"></script>
<script src="https://static.tumblr.com/fwgzvyf/l6jnyutne/shythemes.vr.js"></script>
<script src="https://static.tumblr.com/wgg6svp/OoTofxa0c/unnest.min.js"></script>
{block:IndexPage}
<script src="https://static.tumblr.com/lrtkpti/68fqnfrtl/masonry.pkgd.min.js"></script>
<script src="https://static.tumblr.com/lrtkpti/RGIqnfs0v/imagesloaded.pkgd.min.js"></script>
{block:ifInfiniteScroll}
<script src="https://static.tumblr.com/wgijwsy/u2vm2hxv6/jquery.infinitescroll.min.js"></script>
{/block:ifInfiniteScroll}
{/block:IndexPage}
<script>
$(document).ready(function(){
   $('.photo-slideshow').pxuPhotoset({
       lightbox: true,
       rounded: false,
       gutter: '2px',
       photoset: '.photo-slideshow',
       photoWrap: '.photo-data',
       photo: '.pxu-photo'
   });
    $(function(){  $('.entry').unnest({
    yourCaption: ".blogcaption", {Caption}
    wrapName: ".tumblr_parent",
    newCaptionUsername: false, //if the user adds a new caption, following a series of captions, show their username above the caption
    originalPostCaptionUsername: false, //for the original captions, or a user-added caption that previously didn’t have any, have their username on it
    tumblrAvatars: false,
    tumblrAvatarClass: ".tumblr_avatar",
    usernameColon: true
    }); }); 
   {block:IndexPage}
   var $container = $('#content');
	   $container.masonry({ itemSelector: '.entry', columnWidth: '.grid-sizer', gutter: '.gutter-sizer', percentPosition: true });
    $container.imagesLoaded(function(){
    $container.masonry({ 
        itemSelector: '.entry', 
        columnWidth: '.grid-sizer',
        gutter: '.gutter-sizer',
        percentPosition: true
    });
       $container.find('.entry').animate({ opacity: 1, zIndex: 1 });
   });
   {block:ifInfiniteScroll}
   $container.infinitescroll({
       itemSelector: '.entry',
       navSelector: '.pagination',
       nextSelector: '.next',
       loadingImg: '',
       loadingText: '<em></em>',
       bufferPx: 2000
   },
   function( newElements ) {
       	    var $newElems = $( newElements ).css({ opacity:0, zIndex:-1 });
       $newElems.unnest();  
       $newElems.find('.photo-slideshow').pxuPhotoset({
           lightbox: true,
           rounded: false,
           gutter: '2px',
           photoset: '.photo-slideshow',
           photoWrap: '.photo-data',
           photo: '.pxu-photo'
       },
       function(){
           $container.masonry();
       });
       $newElems.imagesLoaded(function(){
           $newElems.animate({ opacity: 1, zIndex: 1 });
           $container.masonry( 'appended', $newElems );
       });
   });
   {/block:ifInfiniteScroll}
   {/block:IndexPage}
});
</script>
 
<!-- scroll to top script -->
 
<script type="text/javascript">
 
$(function(){$window=$(window);$link=$("#scroll");$link.click(function(){$("html, body").animate({scrollTop:0},"slow")});$window.scroll(function(){if($window.scrollTop()<=0){$link.fadeOut("slow")}else{$link.fadeIn("fast")}})});
 
</script>
 
<!-- tooltip script -->
 
<script src="https://static.tumblr.com/iuw14ew/VSQma1786/jquery.style-my-tooltips.js"></script>
 
<script>
 
(function($){
 
$(document).ready(function(){
 
$("[title]").style_my_tooltips({
 
tip_follows_cursor:true,
 
tip_delay_time:100,
 
tip_fade_speed:250,
 
attribute:"title"
 
});
 
});
 
})(jQuery);
 
</script>
 
<!-- Don't be a d*** and just leave this part alone, ok? :) -->
 
<div id="important"><a href="https://mhango.tumblr.com" target="_blank" title="theme by mhango"><img src="https://img.icons8.com/ios/50/000000/cloud.png" /></a></div>        
 
 
</body>
 
<!-- scroll to top -->
 
<a href="javascript:;" id="scroll" rel="nofollow" title="scroll to top"><img src="https://img.icons8.com/ios/50/000000/circled-up-2.png"/></a>
 
</html>
 
 
