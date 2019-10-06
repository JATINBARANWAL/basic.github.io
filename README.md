# basic
<?xml version="1.0" encoding="UTF-8" ?>
<!DOCTYPE html>
<html b:version='2' class='v2' expr:dir='data:blog.languageDirection' xmlns='http://www.w3.org/1999/xhtml' xmlns:b='http://www.google.com/2005/gml/b' xmlns:data='http://www.google.com/2005/gml/data' xmlns:expr='http://www.google.com/2005/gml/expr'>
  <head>
    <meta charset='UTF-8'/>
    <meta content='width=device-width, initial-scale=1' name='viewport'/>
    <b:include data='blog' name='all-head-content'/>
    <link href='https://fonts.googleapis.com/css?family=Open+Sans:300' rel='stylesheet' type='text/css'/>
    <link href='//netdna.bootstrapcdn.com/font-awesome/4.1.0/css/font-awesome.min.css' rel='stylesheet'/>
    <b:if cond='data:blog.pageType == &quot;index&quot;'>
      <title>
        <data:blog.pageTitle/>
      </title>
      <b:else/>
      <b:if cond='data:blog.pageType != &quot;error_page&quot;'>
        <title>
          <data:blog.pageName/>
          | 
          <data:blog.title/>
        </title>
        <b:else/>
        <title>
          404 ~ Page Not Found!
        </title>
      </b:if>
    </b:if>
    <!--[if lt IE 9]>
<script type="text/javascript">
//<![CDATA[
/*
HTML5 Shiv v3.7.0 | @afarkas @jdalton @jon_neal @rem | MIT/GPL2 Licensed
*/
(function(l,f){function m(){var a=e.elements;return"string"==typeof a?a.split(" "):a}function i(a){var b=n[a[o]];b||(b={},h++,a[o]=h,n[h]=b);return b}function p(a,b,c){b||(b=f);if(g)return b.createElement(a);c||(c=i(b));b=c.cache[a]?c.cache[a].cloneNode():r.test(a)?(c.cache[a]=c.createElem(a)).cloneNode():c.createElem(a);return b.canHaveChildren&&!s.test(a)?c.frag.appendChild(b):b}function t(a,b){if(!b.cache)b.cache={},b.createElem=a.createElement,b.createFrag=a.createDocumentFragment,b.frag=b.createFrag();
a.createElement=function(c){return!e.shivMethods?b.createElem(c):p(c,a,b)};a.createDocumentFragment=Function("h,f","return function(){var n=f.cloneNode(),c=n.createElement;h.shivMethods&&("+m().join().replace(/[\w\-]+/g,function(a){b.createElem(a);b.frag.createElement(a);return'c("'+a+'")'})+");return n}")(e,b.frag)}function q(a){a||(a=f);var b=i(a);if(e.shivCSS&&!j&&!b.hasCSS){var c,d=a;c=d.createElement("p");d=d.getElementsByTagName("head")[0]||d.documentElement;c.innerHTML="x<style>article,aside,dialog,figcaption,figure,footer,header,hgroup,main,nav,section{display:block}mark{background:#FF0;color:#000}template{display:none}</style>";
c=d.insertBefore(c.lastChild,d.firstChild);b.hasCSS=!!c}g||t(a,b);return a}var k=l.html5||{},s=/^<|^(?:button|map|select|textarea|object|iframe|option|optgroup)$/i,r=/^(?:a|b|code|div|fieldset|h1|h2|h3|h4|h5|h6|i|label|li|ol|p|q|span|strong|style|table|tbody|td|th|tr|ul)$/i,j,o="_html5shiv",h=0,n={},g;(function(){try{var a=f.createElement("a");a.innerHTML="<xyz></xyz>";j="hidden"in a;var b;if(!(b=1==a.childNodes.length)){f.createElement("a");var c=f.createDocumentFragment();b="undefined"==typeof c.cloneNode||
"undefined"==typeof c.createDocumentFragment||"undefined"==typeof c.createElement}g=b}catch(d){g=j=!0}})();var e={elements:k.elements||"abbr article aside audio bdi canvas data datalist details dialog figcaption figure footer header hgroup main mark meter nav output progress section summary template time video",version:"3.7.0",shivCSS:!1!==k.shivCSS,supportsUnknownElements:g,shivMethods:!1!==k.shivMethods,type:"default",shivDocument:q,createElement:p,createDocumentFragment:function(a,b){a||(a=f);
if(g)return a.createDocumentFragment();for(var b=b||i(a),c=b.frag.cloneNode(),d=0,e=m(),h=e.length;d<h;d++)c.createElement(e[d]);return c}};l.html5=e;q(f)})(this,document);
//]]>
</script>
<![endif]-->
    <b:skin><![CDATA[
      
/*
-----------------------------------------------
Template Name  : Rareti
Author         : Widiyanata
Author URL     : http://widiyanata.com/
Theme URL      : http://widiyanata.com/
Created Date   : Sunday, Juli 17, 2016
License        : This template is free for both personal and commercial use, But to satisfy the 'attribution' clause of the license, you are required to keep the footer links intact which provides due credit to its authors.For more information about this license, please use this link :http://creativecommons.org/licenses/by/3.0/
----------------------------------------------- */
[hidden],body#layout #slider,template{display:none}hr,img{border:0}.nav>li>a:focus,.nav>li>a:hover,.navbar-brand:focus,.navbar-brand:hover,a{text-decoration:none}#primary-menu li,.nav,body#layout ul,body#layout ul li{list-style:none}body#layout #headerbwrap{height:auto}.section,.widget{margin:0;padding:0}/*!
* Bootstrap v3.1.1 (http://getbootstrap.com)
* Copyright 2011-2014 Twitter, Inc.
* Licensed under MIT (https://github.com/twbs/bootstrap/blob/master/LICENSE)
*//*! normalize.css v3.0.0 | MIT License | git.io/normalize */html{font-family:sans-serif;-ms-text-size-adjust:100%;-webkit-text-size-adjust:100%}article,aside,details,figcaption,figure,footer,header,hgroup,main,nav,section,summary{display:block}audio,canvas,progress,video{display:inline-block;vertical-align:baseline}audio:not([controls]){display:none;height:0}a{background:0 0}abbr[title]{border-bottom:1px dotted}b,optgroup,strong{font-weight:700}dfn{font-style:italic}h1{font-size:2em;margin:.67em 0}mark{background:#ff0;color:#000}.form-control,.img-thumbnail,body{background-color:#fff}small{font-size:80%}sub,sup{font-size:75%;line-height:0;position:relative;vertical-align:baseline}sup{top:-.5em}sub{bottom:-.25em}svg:not(:root){overflow:hidden}hr{-moz-box-sizing:content-box;box-sizing:content-box;height:0}pre,textarea{overflow:auto}code,kbd,pre,samp{font-family:monospace,monospace;font-size:1em}button,input,optgroup,select,textarea{color:inherit;font:inherit;margin:0}button{overflow:visible}button,select{text-transform:none}button,html input[type=button],input[type=reset],input[type=submit]{-webkit-appearance:button;cursor:pointer}button[disabled],html input[disabled]{cursor:default}button::-moz-focus-inner,input::-moz-focus-inner{border:0;padding:0}input[type=checkbox],input[type=radio]{box-sizing:border-box;padding:0}input[type=number]::-webkit-inner-spin-button,input[type=number]::-webkit-outer-spin-button{height:auto}input[type=search]::-webkit-search-cancel-button,input[type=search]::-webkit-search-decoration{-webkit-appearance:none}table{border-collapse:collapse;border-spacing:0}td,th{padding:0}*,:after,:before{-webkit-box-sizing:border-box;-moz-box-sizing:border-box;box-sizing:border-box}html{font-size:62.5%;-webkit-tap-highlight-color:transparent}body{margin:0;font-size:14px;line-height:1.42857143;color:#333}button,input,select,textarea{font-family:inherit;font-size:inherit;line-height:inherit}a:hover,figure{margin:0}.img-responsive{display:block;max-width:100%;height:auto}.img-thumbnail,label{display:inline-block}.img-rounded{border-radius:6px}.img-thumbnail{padding:4px;line-height:1.42857143;border:1px solid #ddd;border-radius:4px;-webkit-transition:all .2s ease-in-out;transition:all .2s ease-in-out;max-width:100%;height:auto}.img-circle{border-radius:50%}hr{margin-top:20px;margin-bottom:20px;border-top:1px solid #eee}.sr-only{position:absolute;width:1px;height:1px;margin:-1px;padding:0;overflow:hidden;clip:rect(0,0,0,0);border:0}.container,.container-fluid{margin-right:auto;margin-left:auto;padding-left:15px;padding-right:15px}@media (min-width:768px){.container{width:750px}}@media (min-width:992px){.container{width:970px}}@media (min-width:1200px){.container{width:1170px}}.row{margin-left:-15px;margin-right:-15px}.col-lg-1,.col-lg-10,.col-lg-11,.col-lg-12,.col-lg-2,.col-lg-3,.col-lg-4,.col-lg-5,.col-lg-6,.col-lg-7,.col-lg-8,.col-lg-9,.col-md-1,.col-md-10,.col-md-11,.col-md-12,.col-md-2,.col-md-3,.col-md-4,.col-md-5,.col-md-6,.col-md-7,.col-md-8,.col-md-9,.col-sm-1,.col-sm-10,.col-sm-11,.col-sm-12,.col-sm-2,.col-sm-3,.col-sm-4,.col-sm-5,.col-sm-6,.col-sm-7,.col-sm-8,.col-sm-9,.col-xs-1,.col-xs-10,.col-xs-11,.col-xs-12,.col-xs-2,.col-xs-3,.col-xs-4,.col-xs-5,.col-xs-6,.col-xs-7,.col-xs-8,.col-xs-9{position:relative;min-height:1px;padding-left:15px;padding-right:15px}fieldset,legend{padding:0;border:0}.col-xs-1,.col-xs-10,.col-xs-11,.col-xs-12,.col-xs-2,.col-xs-3,.col-xs-4,.col-xs-5,.col-xs-6,.col-xs-7,.col-xs-8,.col-xs-9{float:left}.col-xs-12{width:100%}.col-xs-11{width:91.66666667%}.col-xs-10{width:83.33333333%}.col-xs-9{width:75%}.col-xs-8{width:66.66666667%}.col-xs-7{width:58.33333333%}.col-xs-6{width:50%}.col-xs-5{width:41.66666667%}.col-xs-4{width:33.33333333%}.col-xs-3{width:25%}.col-xs-2{width:16.66666667%}.col-xs-1{width:8.33333333%}.col-xs-pull-12{right:100%}.col-xs-pull-11{right:91.66666667%}.col-xs-pull-10{right:83.33333333%}.col-xs-pull-9{right:75%}.col-xs-pull-8{right:66.66666667%}.col-xs-pull-7{right:58.33333333%}.col-xs-pull-6{right:50%}.col-xs-pull-5{right:41.66666667%}.col-xs-pull-4{right:33.33333333%}.col-xs-pull-3{right:25%}.col-xs-pull-2{right:16.66666667%}.col-xs-pull-1{right:8.33333333%}.col-xs-pull-0{right:0}.col-xs-push-12{left:100%}.col-xs-push-11{left:91.66666667%}.col-xs-push-10{left:83.33333333%}.col-xs-push-9{left:75%}.col-xs-push-8{left:66.66666667%}.col-xs-push-7{left:58.33333333%}.col-xs-push-6{left:50%}.col-xs-push-5{left:41.66666667%}.col-xs-push-4{left:33.33333333%}.col-xs-push-3{left:25%}.col-xs-push-2{left:16.66666667%}.col-xs-push-1{left:8.33333333%}.col-xs-push-0{left:0}.col-xs-offset-12{margin-left:100%}.col-xs-offset-11{margin-left:91.66666667%}.col-xs-offset-10{margin-left:83.33333333%}.col-xs-offset-9{margin-left:75%}.col-xs-offset-8{margin-left:66.66666667%}.col-xs-offset-7{margin-left:58.33333333%}.col-xs-offset-6{margin-left:50%}.col-xs-offset-5{margin-left:41.66666667%}.col-xs-offset-4{margin-left:33.33333333%}.col-xs-offset-3{margin-left:25%}.col-xs-offset-2{margin-left:16.66666667%}.col-xs-offset-1{margin-left:8.33333333%}.col-xs-offset-0{margin-left:0}@media (min-width:768px){.col-sm-1,.col-sm-10,.col-sm-11,.col-sm-12,.col-sm-2,.col-sm-3,.col-sm-4,.col-sm-5,.col-sm-6,.col-sm-7,.col-sm-8,.col-sm-9{float:left}.col-sm-12{width:100%}.col-sm-11{width:91.66666667%}.col-sm-10{width:83.33333333%}.col-sm-9{width:75%}.col-sm-8{width:66.66666667%}.col-sm-7{width:58.33333333%}.col-sm-6{width:50%}.col-sm-5{width:41.66666667%}.col-sm-4{width:33.33333333%}.col-sm-3{width:25%}.col-sm-2{width:16.66666667%}.col-sm-1{width:8.33333333%}.col-sm-pull-12{right:100%}.col-sm-pull-11{right:91.66666667%}.col-sm-pull-10{right:83.33333333%}.col-sm-pull-9{right:75%}.col-sm-pull-8{right:66.66666667%}.col-sm-pull-7{right:58.33333333%}.col-sm-pull-6{right:50%}.col-sm-pull-5{right:41.66666667%}.col-sm-pull-4{right:33.33333333%}.col-sm-pull-3{right:25%}.col-sm-pull-2{right:16.66666667%}.col-sm-pull-1{right:8.33333333%}.col-sm-pull-0{right:0}.col-sm-push-12{left:100%}.col-sm-push-11{left:91.66666667%}.col-sm-push-10{left:83.33333333%}.col-sm-push-9{left:75%}.col-sm-push-8{left:66.66666667%}.col-sm-push-7{left:58.33333333%}.col-sm-push-6{left:50%}.col-sm-push-5{left:41.66666667%}.col-sm-push-4{left:33.33333333%}.col-sm-push-3{left:25%}.col-sm-push-2{left:16.66666667%}.col-sm-push-1{left:8.33333333%}.col-sm-push-0{left:0}.col-sm-offset-12{margin-left:100%}.col-sm-offset-11{margin-left:91.66666667%}.col-sm-offset-10{margin-left:83.33333333%}.col-sm-offset-9{margin-left:75%}.col-sm-offset-8{margin-left:66.66666667%}.col-sm-offset-7{margin-left:58.33333333%}.col-sm-offset-6{margin-left:50%}.col-sm-offset-5{margin-left:41.66666667%}.col-sm-offset-4{margin-left:33.33333333%}.col-sm-offset-3{margin-left:25%}.col-sm-offset-2{margin-left:16.66666667%}.col-sm-offset-1{margin-left:8.33333333%}.col-sm-offset-0{margin-left:0}}@media (min-width:992px){.col-md-1,.col-md-10,.col-md-11,.col-md-12,.col-md-2,.col-md-3,.col-md-4,.col-md-5,.col-md-6,.col-md-7,.col-md-8,.col-md-9{float:left}.col-md-12{width:100%}.col-md-11{width:91.66666667%}.col-md-10{width:83.33333333%}.col-md-9{width:75%}.col-md-8{width:66.66666667%}.col-md-7{width:58.33333333%}.col-md-6{width:50%}.col-md-5{width:41.66666667%}.col-md-4{width:33.33333333%}.col-md-3{width:25%}.col-md-2{width:16.66666667%}.col-md-1{width:8.33333333%}.col-md-pull-12{right:100%}.col-md-pull-11{right:91.66666667%}.col-md-pull-10{right:83.33333333%}.col-md-pull-9{right:75%}.col-md-pull-8{right:66.66666667%}.col-md-pull-7{right:58.33333333%}.col-md-pull-6{right:50%}.col-md-pull-5{right:41.66666667%}.col-md-pull-4{right:33.33333333%}.col-md-pull-3{right:25%}.col-md-pull-2{right:16.66666667%}.col-md-pull-1{right:8.33333333%}.col-md-pull-0{right:0}.col-md-push-12{left:100%}.col-md-push-11{left:91.66666667%}.col-md-push-10{left:83.33333333%}.col-md-push-9{left:75%}.col-md-push-8{left:66.66666667%}.col-md-push-7{left:58.33333333%}.col-md-push-6{left:50%}.col-md-push-5{left:41.66666667%}.col-md-push-4{left:33.33333333%}.col-md-push-3{left:25%}.col-md-push-2{left:16.66666667%}.col-md-push-1{left:8.33333333%}.col-md-push-0{left:0}.col-md-offset-12{margin-left:100%}.col-md-offset-11{margin-left:91.66666667%}.col-md-offset-10{margin-left:83.33333333%}.col-md-offset-9{margin-left:75%}.col-md-offset-8{margin-left:66.66666667%}.col-md-offset-7{margin-left:58.33333333%}.col-md-offset-6{margin-left:50%}.col-md-offset-5{margin-left:41.66666667%}.col-md-offset-4{margin-left:33.33333333%}.col-md-offset-3{margin-left:25%}.col-md-offset-2{margin-left:16.66666667%}.col-md-offset-1{margin-left:8.33333333%}.col-md-offset-0{margin-left:0}}@media (min-width:1200px){.col-lg-1,.col-lg-10,.col-lg-11,.col-lg-12,.col-lg-2,.col-lg-3,.col-lg-4,.col-lg-5,.col-lg-6,.col-lg-7,.col-lg-8,.col-lg-9{float:left}.col-lg-12{width:100%}.col-lg-11{width:91.66666667%}.col-lg-10{width:83.33333333%}.col-lg-9{width:75%}.col-lg-8{width:66.66666667%}.col-lg-7{width:58.33333333%}.col-lg-6{width:50%}.col-lg-5{width:41.66666667%}.col-lg-4{width:33.33333333%}.col-lg-3{width:25%}.col-lg-2{width:16.66666667%}.col-lg-1{width:8.33333333%}.col-lg-pull-12{right:100%}.col-lg-pull-11{right:91.66666667%}.col-lg-pull-10{right:83.33333333%}.col-lg-pull-9{right:75%}.col-lg-pull-8{right:66.66666667%}.col-lg-pull-7{right:58.33333333%}.col-lg-pull-6{right:50%}.col-lg-pull-5{right:41.66666667%}.col-lg-pull-4{right:33.33333333%}.col-lg-pull-3{right:25%}.col-lg-pull-2{right:16.66666667%}.col-lg-pull-1{right:8.33333333%}.col-lg-pull-0{right:0}.col-lg-push-12{left:100%}.col-lg-push-11{left:91.66666667%}.col-lg-push-10{left:83.33333333%}.col-lg-push-9{left:75%}.col-lg-push-8{left:66.66666667%}.col-lg-push-7{left:58.33333333%}.col-lg-push-6{left:50%}.col-lg-push-5{left:41.66666667%}.col-lg-push-4{left:33.33333333%}.col-lg-push-3{left:25%}.col-lg-push-2{left:16.66666667%}.col-lg-push-1{left:8.33333333%}.col-lg-push-0{left:0}.col-lg-offset-12{margin-left:100%}.col-lg-offset-11{margin-left:91.66666667%}.col-lg-offset-10{margin-left:83.33333333%}.col-lg-offset-9{margin-left:75%}.col-lg-offset-8{margin-left:66.66666667%}.col-lg-offset-7{margin-left:58.33333333%}.col-lg-offset-6{margin-left:50%}.col-lg-offset-5{margin-left:41.66666667%}.col-lg-offset-4{margin-left:33.33333333%}.col-lg-offset-3{margin-left:25%}.col-lg-offset-2{margin-left:16.66666667%}.col-lg-offset-1{margin-left:8.33333333%}.col-lg-offset-0{margin-left:0}}fieldset{margin:0;min-width:0}legend{display:block;width:100%;margin-bottom:20px;font-size:21px;line-height:inherit;color:#333;border-bottom:1px solid #e5e5e5}label{margin-bottom:5px;font-weight:700}input[type=search]{-webkit-box-sizing:border-box;-moz-box-sizing:border-box;box-sizing:border-box;-webkit-appearance:none}input[type=checkbox],input[type=radio]{margin:4px 0 0;margin-top:1px\9;line-height:normal}.form-control,output{font-size:14px;line-height:1.42857143;color:#555;display:block}input[type=file]{display:block}input[type=range]{display:block;width:100%}select[multiple],select[size]{height:auto}input[type=checkbox]:focus,input[type=radio]:focus,input[type=file]:focus{outline:dotted thin;outline:-webkit-focus-ring-color auto 5px;outline-offset:-2px}output{padding-top:7px}.form-control{width:100%;height:34px;padding:6px 12px;background-image:none;border:1px solid #ccc;border-radius:4px;-webkit-box-shadow:inset 0 1px 1px rgba(0,0,0,.075);box-shadow:inset 0 1px 1px rgba(0,0,0,.075);-webkit-transition:border-color ease-in-out .15s,box-shadow ease-in-out .15s;transition:border-color ease-in-out .15s,box-shadow ease-in-out .15s}.form-control:focus{border-color:#66afe9;outline:0;-webkit-box-shadow:inset 0 1px 1px rgba(0,0,0,.075),0 0 8px rgba(102,175,233,.6);box-shadow:inset 0 1px 1px rgba(0,0,0,.075),0 0 8px rgba(102,175,233,.6)}.form-control::-moz-placeholder{color:#999;opacity:1}.form-control:-ms-input-placeholder{color:#999}.form-control::-webkit-input-placeholder{color:#999}.has-success .checkbox,.has-success .checkbox-inline,.has-success .control-label,.has-success .form-control-feedback,.has-success .help-block,.has-success .radio,.has-success .radio-inline{color:#3c763d}.form-control[disabled],.form-control[readonly],fieldset[disabled] .form-control{cursor:not-allowed;background-color:#eee;opacity:1}textarea.form-control{height:auto}input[type=date]{line-height:34px}.form-group{margin-bottom:15px}.checkbox,.radio{display:block;min-height:20px;margin-top:10px;margin-bottom:10px;padding-left:20px}.checkbox label,.radio label{display:inline;font-weight:400;cursor:pointer}.checkbox input[type=checkbox],.checkbox-inline input[type=checkbox],.radio input[type=radio],.radio-inline input[type=radio]{float:left;margin-left:-20px}.checkbox+.checkbox,.radio+.radio{margin-top:-5px}.checkbox-inline,.radio-inline{display:inline-block;padding-left:20px;margin-bottom:0;vertical-align:middle;font-weight:400;cursor:pointer}.checkbox-inline+.checkbox-inline,.radio-inline+.radio-inline{margin-top:0;margin-left:10px}.checkbox-inline[disabled],.checkbox[disabled],.radio-inline[disabled],.radio[disabled],fieldset[disabled] .checkbox,fieldset[disabled] .checkbox-inline,fieldset[disabled] .radio,fieldset[disabled] .radio-inline,fieldset[disabled] input[type=checkbox],fieldset[disabled] input[type=radio],input[type=checkbox][disabled],input[type=radio][disabled]{cursor:not-allowed}.input-sm{height:30px;padding:5px 10px;font-size:12px;line-height:1.5;border-radius:3px}select.input-sm{height:30px;line-height:30px}select[multiple].input-sm,textarea.input-sm{height:auto}.input-lg{height:46px;padding:10px 16px;font-size:18px;line-height:1.33;border-radius:6px}select.input-lg{height:46px;line-height:46px}select[multiple].input-lg,textarea.input-lg{height:auto}.has-feedback{position:relative}.has-feedback .form-control{padding-right:42.5px}.has-feedback .form-control-feedback{position:absolute;top:25px;right:0;display:block;width:34px;height:34px;line-height:34px;text-align:center}.has-success .form-control{border-color:#3c763d;-webkit-box-shadow:inset 0 1px 1px rgba(0,0,0,.075);box-shadow:inset 0 1px 1px rgba(0,0,0,.075)}.has-success .form-control:focus{border-color:#2b542c;-webkit-box-shadow:inset 0 1px 1px rgba(0,0,0,.075),0 0 6px #67b168;box-shadow:inset 0 1px 1px rgba(0,0,0,.075),0 0 6px #67b168}.has-success .input-group-addon{color:#3c763d;border-color:#3c763d;background-color:#dff0d8}.has-warning .checkbox,.has-warning .checkbox-inline,.has-warning .control-label,.has-warning .form-control-feedback,.has-warning .help-block,.has-warning .radio,.has-warning .radio-inline{color:#8a6d3b}.has-warning .form-control{border-color:#8a6d3b;-webkit-box-shadow:inset 0 1px 1px rgba(0,0,0,.075);box-shadow:inset 0 1px 1px rgba(0,0,0,.075)}.has-warning .form-control:focus{border-color:#66512c;-webkit-box-shadow:inset 0 1px 1px rgba(0,0,0,.075),0 0 6px #c0a16b;box-shadow:inset 0 1px 1px rgba(0,0,0,.075),0 0 6px #c0a16b}.has-warning .input-group-addon{color:#8a6d3b;border-color:#8a6d3b;background-color:#fcf8e3}.has-error .checkbox,.has-error .checkbox-inline,.has-error .control-label,.has-error .form-control-feedback,.has-error .help-block,.has-error .radio,.has-error .radio-inline{color:#a94442}.has-error .form-control{border-color:#a94442;-webkit-box-shadow:inset 0 1px 1px rgba(0,0,0,.075);box-shadow:inset 0 1px 1px rgba(0,0,0,.075)}.has-error .form-control:focus{border-color:#843534;-webkit-box-shadow:inset 0 1px 1px rgba(0,0,0,.075),0 0 6px #ce8483;box-shadow:inset 0 1px 1px rgba(0,0,0,.075),0 0 6px #ce8483}.has-error .input-group-addon{color:#a94442;border-color:#a94442;background-color:#f2dede}.form-control-static{margin-bottom:0}.help-block{display:block;margin-top:5px;margin-bottom:10px;color:#737373}@media (min-width:768px){.form-inline .checkbox,.form-inline .form-control,.form-inline .form-group,.form-inline .radio{display:inline-block;vertical-align:middle}.form-inline .control-label,.form-inline .form-group{margin-bottom:0;vertical-align:middle}.form-inline .form-control{width:auto}.form-inline .input-group>.form-control{width:100%}.form-inline .checkbox,.form-inline .radio{margin-top:0;margin-bottom:0;padding-left:0}.form-inline .checkbox input[type=checkbox],.form-inline .radio input[type=radio]{float:none;margin-left:0}.form-inline .has-feedback .form-control-feedback{top:0}.form-horizontal .control-label{text-align:right}}.form-horizontal .checkbox,.form-horizontal .checkbox-inline,.form-horizontal .control-label,.form-horizontal .radio,.form-horizontal .radio-inline{margin-top:0;margin-bottom:0;padding-top:7px}.form-horizontal .checkbox,.form-horizontal .radio{min-height:27px}.form-horizontal .form-group{margin-left:-15px;margin-right:-15px}.form-horizontal .form-control-static{padding-top:7px}.form-horizontal .has-feedback .form-control-feedback{top:0;right:15px}.fade{opacity:0;-webkit-transition:opacity .15s linear;transition:opacity .15s linear}.fade.in,.post-body img{opacity:1}.collapse{display:none}.collapse.in{display:block}.collapsing{position:relative;height:0;overflow:hidden;-webkit-transition:height .35s ease;transition:height .35s ease}@font-face{font-family:'Glyphicons Halflings';src:url(../fonts/glyphicons-halflings-regular.eot);src:url(../fonts/glyphicons-halflings-regular.eot?#iefix) format('embedded-opentype'),url(../fonts/glyphicons-halflings-regular.woff) format('woff'),url(../fonts/glyphicons-halflings-regular.ttf) format('truetype'),url(../fonts/glyphicons-halflings-regular.svg#glyphicons_halflingsregular) format('svg')}.glyphicon{position:relative;top:1px;display:inline-block;font-family:'Glyphicons Halflings';font-style:normal;font-weight:400;line-height:1;-webkit-font-smoothing:antialiased;-moz-osx-font-smoothing:grayscale}.nav-justified>.dropdown .dropdown-menu,.nav-tabs.nav-justified>.dropdown .dropdown-menu{top:auto;left:auto}.nav>li,.nav>li>a{display:block;position:relative}.glyphicon-asterisk:before{content:"\2a"}.glyphicon-plus:before{content:"\2b"}.glyphicon-euro:before{content:"\20ac"}.glyphicon-minus:before{content:"\2212"}.glyphicon-cloud:before{content:"\2601"}.glyphicon-envelope:before{content:"\2709"}.glyphicon-pencil:before{content:"\270f"}.glyphicon-glass:before{content:"\e001"}.glyphicon-music:before{content:"\e002"}.glyphicon-search:before{content:"\e003"}.glyphicon-heart:before{content:"\e005"}.glyphicon-star:before{content:"\e006"}.glyphicon-star-empty:before{content:"\e007"}.glyphicon-user:before{content:"\e008"}.glyphicon-film:before{content:"\e009"}.glyphicon-th-large:before{content:"\e010"}.glyphicon-th:before{content:"\e011"}.glyphicon-th-list:before{content:"\e012"}.glyphicon-ok:before{content:"\e013"}.glyphicon-remove:before{content:"\e014"}.glyphicon-zoom-in:before{content:"\e015"}.glyphicon-zoom-out:before{content:"\e016"}.glyphicon-off:before{content:"\e017"}.glyphicon-signal:before{content:"\e018"}.glyphicon-cog:before{content:"\e019"}.glyphicon-trash:before{content:"\e020"}.glyphicon-home:before{content:"\e021"}.glyphicon-file:before{content:"\e022"}.glyphicon-time:before{content:"\e023"}.glyphicon-road:before{content:"\e024"}.glyphicon-download-alt:before{content:"\e025"}.glyphicon-download:before{content:"\e026"}.glyphicon-upload:before{content:"\e027"}.glyphicon-inbox:before{content:"\e028"}.glyphicon-play-circle:before{content:"\e029"}.glyphicon-repeat:before{content:"\e030"}.glyphicon-refresh:before{content:"\e031"}.glyphicon-list-alt:before{content:"\e032"}.glyphicon-lock:before{content:"\e033"}.glyphicon-flag:before{content:"\e034"}.glyphicon-headphones:before{content:"\e035"}.glyphicon-volume-off:before{content:"\e036"}.glyphicon-volume-down:before{content:"\e037"}.glyphicon-volume-up:before{content:"\e038"}.glyphicon-qrcode:before{content:"\e039"}.glyphicon-barcode:before{content:"\e040"}.glyphicon-tag:before{content:"\e041"}.glyphicon-tags:before{content:"\e042"}.glyphicon-book:before{content:"\e043"}.glyphicon-bookmark:before{content:"\e044"}.glyphicon-print:before{content:"\e045"}.glyphicon-camera:before{content:"\e046"}.glyphicon-font:before{content:"\e047"}.glyphicon-bold:before{content:"\e048"}.glyphicon-italic:before{content:"\e049"}.glyphicon-text-height:before{content:"\e050"}.glyphicon-text-width:before{content:"\e051"}.glyphicon-align-left:before{content:"\e052"}.glyphicon-align-center:before{content:"\e053"}.glyphicon-align-right:before{content:"\e054"}.glyphicon-align-justify:before{content:"\e055"}.glyphicon-list:before{content:"\e056"}.glyphicon-indent-left:before{content:"\e057"}.glyphicon-indent-right:before{content:"\e058"}.glyphicon-facetime-video:before{content:"\e059"}.glyphicon-picture:before{content:"\e060"}.glyphicon-map-marker:before{content:"\e062"}.glyphicon-adjust:before{content:"\e063"}.glyphicon-tint:before{content:"\e064"}.glyphicon-edit:before{content:"\e065"}.glyphicon-share:before{content:"\e066"}.glyphicon-check:before{content:"\e067"}.glyphicon-move:before{content:"\e068"}.glyphicon-step-backward:before{content:"\e069"}.glyphicon-fast-backward:before{content:"\e070"}.glyphicon-backward:before{content:"\e071"}.glyphicon-play:before{content:"\e072"}.glyphicon-pause:before{content:"\e073"}.glyphicon-stop:before{content:"\e074"}.glyphicon-forward:before{content:"\e075"}.glyphicon-fast-forward:before{content:"\e076"}.glyphicon-step-forward:before{content:"\e077"}.glyphicon-eject:before{content:"\e078"}.glyphicon-chevron-left:before{content:"\e079"}.glyphicon-chevron-right:before{content:"\e080"}.glyphicon-plus-sign:before{content:"\e081"}.glyphicon-minus-sign:before{content:"\e082"}.glyphicon-remove-sign:before{content:"\e083"}.glyphicon-ok-sign:before{content:"\e084"}.glyphicon-question-sign:before{content:"\e085"}.glyphicon-info-sign:before{content:"\e086"}.glyphicon-screenshot:before{content:"\e087"}.glyphicon-remove-circle:before{content:"\e088"}.glyphicon-ok-circle:before{content:"\e089"}.glyphicon-ban-circle:before{content:"\e090"}.glyphicon-arrow-left:before{content:"\e091"}.glyphicon-arrow-right:before{content:"\e092"}.glyphicon-arrow-up:before{content:"\e093"}.glyphicon-arrow-down:before{content:"\e094"}.glyphicon-share-alt:before{content:"\e095"}.glyphicon-resize-full:before{content:"\e096"}.glyphicon-resize-small:before{content:"\e097"}.glyphicon-exclamation-sign:before{content:"\e101"}.glyphicon-gift:before{content:"\e102"}.glyphicon-leaf:before{content:"\e103"}.glyphicon-fire:before{content:"\e104"}.glyphicon-eye-open:before{content:"\e105"}.glyphicon-eye-close:before{content:"\e106"}.glyphicon-warning-sign:before{content:"\e107"}.glyphicon-plane:before{content:"\e108"}.glyphicon-calendar:before{content:"\e109"}.glyphicon-random:before{content:"\e110"}.glyphicon-comment:before{content:"\e111"}.glyphicon-magnet:before{content:"\e112"}.glyphicon-chevron-up:before{content:"\e113"}.glyphicon-chevron-down:before{content:"\e114"}.glyphicon-retweet:before{content:"\e115"}.glyphicon-shopping-cart:before{content:"\e116"}.glyphicon-folder-close:before{content:"\e117"}.glyphicon-folder-open:before{content:"\e118"}.glyphicon-resize-vertical:before{content:"\e119"}.glyphicon-resize-horizontal:before{content:"\e120"}.glyphicon-hdd:before{content:"\e121"}.glyphicon-bullhorn:before{content:"\e122"}.glyphicon-bell:before{content:"\e123"}.glyphicon-certificate:before{content:"\e124"}.glyphicon-thumbs-up:before{content:"\e125"}.glyphicon-thumbs-down:before{content:"\e126"}.glyphicon-hand-right:before{content:"\e127"}.glyphicon-hand-left:before{content:"\e128"}.glyphicon-hand-up:before{content:"\e129"}.glyphicon-hand-down:before{content:"\e130"}.glyphicon-circle-arrow-right:before{content:"\e131"}.glyphicon-circle-arrow-left:before{content:"\e132"}.glyphicon-circle-arrow-up:before{content:"\e133"}.glyphicon-circle-arrow-down:before{content:"\e134"}.glyphicon-globe:before{content:"\e135"}.glyphicon-wrench:before{content:"\e136"}.glyphicon-tasks:before{content:"\e137"}.glyphicon-filter:before{content:"\e138"}.glyphicon-briefcase:before{content:"\e139"}.glyphicon-fullscreen:before{content:"\e140"}.glyphicon-dashboard:before{content:"\e141"}.glyphicon-paperclip:before{content:"\e142"}.glyphicon-heart-empty:before{content:"\e143"}.glyphicon-link:before{content:"\e144"}.glyphicon-phone:before{content:"\e145"}.glyphicon-pushpin:before{content:"\e146"}.glyphicon-usd:before{content:"\e148"}.glyphicon-gbp:before{content:"\e149"}.glyphicon-sort:before{content:"\e150"}.glyphicon-sort-by-alphabet:before{content:"\e151"}.glyphicon-sort-by-alphabet-alt:before{content:"\e152"}.glyphicon-sort-by-order:before{content:"\e153"}.glyphicon-sort-by-order-alt:before{content:"\e154"}.glyphicon-sort-by-attributes:before{content:"\e155"}.glyphicon-sort-by-attributes-alt:before{content:"\e156"}.glyphicon-unchecked:before{content:"\e157"}.glyphicon-expand:before{content:"\e158"}.glyphicon-collapse-down:before{content:"\e159"}.glyphicon-collapse-up:before{content:"\e160"}.glyphicon-log-in:before{content:"\e161"}.glyphicon-flash:before{content:"\e162"}.glyphicon-log-out:before{content:"\e163"}.glyphicon-new-window:before{content:"\e164"}.glyphicon-record:before{content:"\e165"}.glyphicon-save:before{content:"\e166"}.glyphicon-open:before{content:"\e167"}.glyphicon-saved:before{content:"\e168"}.glyphicon-import:before{content:"\e169"}.glyphicon-export:before{content:"\e170"}.glyphicon-send:before{content:"\e171"}.glyphicon-floppy-disk:before{content:"\e172"}.glyphicon-floppy-saved:before{content:"\e173"}.glyphicon-floppy-remove:before{content:"\e174"}.glyphicon-floppy-save:before{content:"\e175"}.glyphicon-floppy-open:before{content:"\e176"}.glyphicon-credit-card:before{content:"\e177"}.glyphicon-transfer:before{content:"\e178"}.glyphicon-cutlery:before{content:"\e179"}.glyphicon-header:before{content:"\e180"}.glyphicon-compressed:before{content:"\e181"}.glyphicon-earphone:before{content:"\e182"}.glyphicon-phone-alt:before{content:"\e183"}.glyphicon-tower:before{content:"\e184"}.glyphicon-stats:before{content:"\e185"}.glyphicon-sd-video:before{content:"\e186"}.glyphicon-hd-video:before{content:"\e187"}.glyphicon-subtitles:before{content:"\e188"}.glyphicon-sound-stereo:before{content:"\e189"}.glyphicon-sound-dolby:before{content:"\e190"}.glyphicon-sound-5-1:before{content:"\e191"}.glyphicon-sound-6-1:before{content:"\e192"}.glyphicon-sound-7-1:before{content:"\e193"}.glyphicon-copyright-mark:before{content:"\e194"}.glyphicon-registration-mark:before{content:"\e195"}.glyphicon-cloud-download:before{content:"\e197"}.glyphicon-cloud-upload:before{content:"\e198"}.glyphicon-tree-conifer:before{content:"\e199"}.glyphicon-tree-deciduous:before{content:"\e200"}.nav{margin-bottom:0;padding-left:0}.nav>li>a{padding:10px 15px}.nav>li>a:focus,.nav>li>a:hover{background-color:#eee}.nav>li.disabled>a{color:#999}.nav>li.disabled>a:focus,.nav>li.disabled>a:hover{color:#999;text-decoration:none;background-color:transparent;cursor:not-allowed}.nav .open>a,.nav .open>a:focus,.nav .open>a:hover{background-color:#eee;border-color:#428bca}.nav .nav-divider{height:1px;margin:9px 0;overflow:hidden;background-color:#e5e5e5}.nav>li>a>img{max-width:none}.nav-tabs{border-bottom:1px solid #ddd}.nav-tabs>li{float:left;margin-bottom:-1px}.nav-tabs>li>a{margin-right:2px;line-height:1.42857143;border:1px solid transparent;border-radius:4px 4px 0 0}.nav-tabs>li>a:hover{border-color:#eee #eee #ddd}.nav-tabs>li.active>a,.nav-tabs>li.active>a:focus,.nav-tabs>li.active>a:hover{color:#555;background-color:#fff;border:1px solid #ddd;border-bottom-color:transparent;cursor:default}.nav-tabs.nav-justified{width:100%;border-bottom:0}.nav-tabs.nav-justified>li{float:none}.nav-tabs.nav-justified>li>a{text-align:center;margin-bottom:5px;margin-right:0;border-radius:4px}.nav-tabs.nav-justified>.active>a,.nav-tabs.nav-justified>.active>a:focus,.nav-tabs.nav-justified>.active>a:hover{border:1px solid #ddd}@media (min-width:768px){.nav-tabs.nav-justified>li{display:table-cell;width:1%}.nav-tabs.nav-justified>li>a{margin-bottom:0;border-bottom:1px solid #ddd;border-radius:4px 4px 0 0}.nav-tabs.nav-justified>.active>a,.nav-tabs.nav-justified>.active>a:focus,.nav-tabs.nav-justified>.active>a:hover{border-bottom-color:#fff}}.nav-pills>li{float:left}.nav-justified>li,.nav-stacked>li{float:none}.nav-pills>li>a{border-radius:4px}.nav-pills>li+li{margin-left:2px}.nav-pills>li.active>a,.nav-pills>li.active>a:focus,.nav-pills>li.active>a:hover{color:#fff;background-color:#428bca}.nav-stacked>li+li{margin-top:2px;margin-left:0}.nav-justified{width:100%}.nav-justified>li>a{text-align:center;margin-bottom:5px}.nav-tabs-justified{border-bottom:0}.nav-tabs-justified>li>a{margin-right:0;border-radius:4px}.nav-tabs-justified>.active>a,.nav-tabs-justified>.active>a:focus,.nav-tabs-justified>.active>a:hover{border:1px solid #ddd}@media (min-width:768px){.nav-justified>li{display:table-cell;width:1%}.nav-justified>li>a{margin-bottom:0}.nav-tabs-justified>li>a{border-bottom:1px solid #ddd;border-radius:4px 4px 0 0}.nav-tabs-justified>.active>a,.nav-tabs-justified>.active>a:focus,.nav-tabs-justified>.active>a:hover{border-bottom-color:#fff}}.tab-content>.tab-pane{display:none}.tab-content>.active{display:block}.nav-tabs .dropdown-menu{margin-top:-1px;border-top-right-radius:0;border-top-left-radius:0}.navbar{position:relative;min-height:50px;margin-bottom:20px;border:1px solid transparent}.navbar-collapse{overflow-x:visible;padding-right:15px;padding-left:15px;border-top:1px solid transparent;box-shadow:inset 0 1px 0 rgba(255,255,255,.1);-webkit-overflow-scrolling:touch}.navbar-collapse.in{overflow-y:auto}.container-fluid>.navbar-collapse,.container-fluid>.navbar-header,.container>.navbar-collapse,.container>.navbar-header{margin-right:-15px;margin-left:-15px}@media (min-width:768px){.navbar{border-radius:4px}.navbar-header{float:left}.navbar-collapse{width:auto;border-top:0;box-shadow:none}.navbar-collapse.collapse{display:block!important;height:auto!important;padding-bottom:0;overflow:visible!important}.navbar-collapse.in{overflow-y:visible}.navbar-fixed-bottom .navbar-collapse,.navbar-fixed-top .navbar-collapse,.navbar-static-top .navbar-collapse{padding-left:0;padding-right:0}.container-fluid>.navbar-collapse,.container-fluid>.navbar-header,.container>.navbar-collapse,.container>.navbar-header{margin-right:0;margin-left:0}.navbar-static-top{border-radius:0}}.navbar-static-top{z-index:1000;border-width:0 0 1px}.navbar-fixed-bottom,.navbar-fixed-top{position:fixed;right:0;left:0;z-index:1030}.navbar-fixed-top{top:0;border-width:0 0 1px}.navbar-fixed-bottom{bottom:0;margin-bottom:0;border-width:1px 0 0}.navbar-brand{float:left;padding:15px;font-size:18px;line-height:20px;height:50px}@media (min-width:768px){.navbar-fixed-bottom,.navbar-fixed-top{border-radius:0}.navbar>.container .navbar-brand,.navbar>.container-fluid .navbar-brand{margin-left:-15px}}.navbar-toggle{margin-right:15px;padding:9px 10px;margin-top:8px;margin-bottom:8px;background-color:transparent;background-image:none;border:1px solid transparent;border-radius:4px}.navbar-toggle:focus{outline:0}.navbar-toggle .icon-bar{display:block;width:22px;height:2px;border-radius:1px}.navbar-toggle .icon-bar+.icon-bar{margin-top:4px}.navbar-nav{margin:7.5px -15px}.navbar-nav>li>a{padding-top:10px;padding-bottom:10px;line-height:20px}@media (max-width:767px){.navbar-nav .open .dropdown-menu{position:static;float:none;width:auto;margin-top:0;background-color:transparent;border:0;box-shadow:none}.navbar-nav .open .dropdown-menu .dropdown-header,.navbar-nav .open .dropdown-menu>li>a{padding:5px 15px 5px 25px}.navbar-nav .open .dropdown-menu>li>a{line-height:20px}.navbar-nav .open .dropdown-menu>li>a:focus,.navbar-nav .open .dropdown-menu>li>a:hover{background-image:none}}#sidebar,.affix{position:fixed}@media (min-width:768px){.navbar-toggle{display:none}.navbar-nav{float:left;margin:0}.navbar-nav>li{float:left}.navbar-nav>li>a{padding-top:15px;padding-bottom:15px}.navbar-nav.navbar-right:last-child{margin-right:-15px}.navbar-left{float:left!important}.navbar-right{float:right!important}}.navbar-form{padding:10px 15px;border-top:1px solid transparent;border-bottom:1px solid transparent;-webkit-box-shadow:inset 0 1px 0 rgba(255,255,255,.1),0 1px 0 rgba(255,255,255,.1);box-shadow:inset 0 1px 0 rgba(255,255,255,.1),0 1px 0 rgba(255,255,255,.1);margin:8px -15px}@media (min-width:768px){.navbar-form .checkbox,.navbar-form .form-control,.navbar-form .form-group,.navbar-form .radio{display:inline-block;vertical-align:middle}.navbar-form .control-label,.navbar-form .form-group{margin-bottom:0;vertical-align:middle}.navbar-form .form-control{width:auto}.navbar-form .input-group>.form-control{width:100%}.navbar-form .checkbox,.navbar-form .radio{margin-top:0;margin-bottom:0;padding-left:0}.navbar-form .checkbox input[type=checkbox],.navbar-form .radio input[type=radio]{float:none;margin-left:0}.navbar-form .has-feedback .form-control-feedback{top:0}.navbar-form{width:auto;border:0;margin-left:0;margin-right:0;padding-top:0;padding-bottom:0;-webkit-box-shadow:none;box-shadow:none}.navbar-form.navbar-right:last-child{margin-right:-15px}}@media (max-width:767px){.navbar-form .form-group{margin-bottom:5px}}.navbar-nav>li>.dropdown-menu{margin-top:0;border-top-right-radius:0;border-top-left-radius:0}.navbar-fixed-bottom .navbar-nav>li>.dropdown-menu{border-bottom-right-radius:0;border-bottom-left-radius:0}.navbar-btn{margin-top:8px;margin-bottom:8px}.navbar-btn.btn-sm{margin-top:10px;margin-bottom:10px}.navbar-btn.btn-xs{margin-top:14px;margin-bottom:14px}.navbar-text{margin-top:15px;margin-bottom:15px}@media (min-width:768px){.navbar-text{float:left;margin-left:15px;margin-right:15px}.navbar-text.navbar-right:last-child{margin-right:0}}.navbar-default{background-color:#f8f8f8;border-color:#e7e7e7}.navbar-default .navbar-brand{color:#777}.navbar-default .navbar-brand:focus,.navbar-default .navbar-brand:hover{color:#5e5e5e;background-color:transparent}.navbar-default .navbar-nav>li>a,.navbar-default .navbar-text{color:#777}.navbar-default .navbar-nav>li>a:focus,.navbar-default .navbar-nav>li>a:hover{color:#333;background-color:transparent}.navbar-default .navbar-nav>.active>a,.navbar-default .navbar-nav>.active>a:focus,.navbar-default .navbar-nav>.active>a:hover{color:#555;background-color:#e7e7e7}.navbar-default .navbar-nav>.disabled>a,.navbar-default .navbar-nav>.disabled>a:focus,.navbar-default .navbar-nav>.disabled>a:hover{color:#ccc;background-color:transparent}.navbar-default .navbar-toggle{border-color:#ddd}.navbar-default .navbar-toggle:focus,.navbar-default .navbar-toggle:hover{background-color:#ddd}.navbar-default .navbar-toggle .icon-bar{background-color:#888}.navbar-default .navbar-collapse,.navbar-default .navbar-form{border-color:#e7e7e7}.navbar-default .navbar-nav>.open>a,.navbar-default .navbar-nav>.open>a:focus,.navbar-default .navbar-nav>.open>a:hover{background-color:#e7e7e7;color:#555}@media (max-width:767px){.navbar-default .navbar-nav .open .dropdown-menu>li>a{color:#777}.navbar-default .navbar-nav .open .dropdown-menu>li>a:focus,.navbar-default .navbar-nav .open .dropdown-menu>li>a:hover{color:#333;background-color:transparent}.navbar-default .navbar-nav .open .dropdown-menu>.active>a,.navbar-default .navbar-nav .open .dropdown-menu>.active>a:focus,.navbar-default .navbar-nav .open .dropdown-menu>.active>a:hover{color:#555;background-color:#e7e7e7}.navbar-default .navbar-nav .open .dropdown-menu>.disabled>a,.navbar-default .navbar-nav .open .dropdown-menu>.disabled>a:focus,.navbar-default .navbar-nav .open .dropdown-menu>.disabled>a:hover{color:#ccc;background-color:transparent}}.navbar-default .navbar-link{color:#777}.navbar-default .navbar-link:hover{color:#333}.navbar-inverse{background-color:#222;border-color:#080808}.navbar-inverse .navbar-brand{color:#999}.navbar-inverse .navbar-brand:focus,.navbar-inverse .navbar-brand:hover{color:#fff;background-color:transparent}.navbar-inverse .navbar-nav>li>a,.navbar-inverse .navbar-text{color:#999}.navbar-inverse .navbar-nav>li>a:focus,.navbar-inverse .navbar-nav>li>a:hover{color:#fff;background-color:transparent}.navbar-inverse .navbar-nav>.active>a,.navbar-inverse .navbar-nav>.active>a:focus,.navbar-inverse .navbar-nav>.active>a:hover{color:#fff;background-color:#080808}.navbar-inverse .navbar-nav>.disabled>a,.navbar-inverse .navbar-nav>.disabled>a:focus,.navbar-inverse .navbar-nav>.disabled>a:hover{color:#444;background-color:transparent}.navbar-inverse .navbar-toggle{border-color:#333}.navbar-inverse .navbar-toggle:focus,.navbar-inverse .navbar-toggle:hover{background-color:#333}.navbar-inverse .navbar-toggle .icon-bar{background-color:#fff}.navbar-inverse .navbar-collapse,.navbar-inverse .navbar-form{border-color:#101010}.navbar-inverse .navbar-nav>.open>a,.navbar-inverse .navbar-nav>.open>a:focus,.navbar-inverse .navbar-nav>.open>a:hover{background-color:#080808;color:#fff}@media (max-width:767px){.navbar-inverse .navbar-nav .open .dropdown-menu>.dropdown-header{border-color:#080808}.navbar-inverse .navbar-nav .open .dropdown-menu .divider{background-color:#080808}.navbar-inverse .navbar-nav .open .dropdown-menu>li>a{color:#999}.navbar-inverse .navbar-nav .open .dropdown-menu>li>a:focus,.navbar-inverse .navbar-nav .open .dropdown-menu>li>a:hover{color:#fff;background-color:transparent}.navbar-inverse .navbar-nav .open .dropdown-menu>.active>a,.navbar-inverse .navbar-nav .open .dropdown-menu>.active>a:focus,.navbar-inverse .navbar-nav .open .dropdown-menu>.active>a:hover{color:#fff;background-color:#080808}.navbar-inverse .navbar-nav .open .dropdown-menu>.disabled>a,.navbar-inverse .navbar-nav .open .dropdown-menu>.disabled>a:focus,.navbar-inverse .navbar-nav .open .dropdown-menu>.disabled>a:hover{color:#444;background-color:transparent}}.navbar-inverse .navbar-link{color:#999}.navbar-inverse .navbar-link:hover{color:#fff}.clearfix:after,.clearfix:before,.container-fluid:after,.container-fluid:before,.container:after,.container:before,.form-horizontal .form-group:after,.form-horizontal .form-group:before,.nav:after,.nav:before,.navbar-collapse:after,.navbar-collapse:before,.navbar-header:after,.navbar-header:before,.navbar:after,.navbar:before,.row:after,.row:before{content:" ";display:table}.clearfix:after,.container-fluid:after,.container:after,.form-horizontal .form-group:after,.nav:after,.navbar-collapse:after,.navbar-header:after,.navbar:after,.row:after{clear:both}.center-block{display:block;margin-left:auto;margin-right:auto}.pull-right{float:right!important}.pull-left{float:left!important}.hide{display:none!important}.show{display:block!important}.hidden,.visible-lg,.visible-md,.visible-sm,.visible-xs{display:none!important}.invisible{visibility:hidden}.text-hide{font:0/0 a;color:transparent;text-shadow:none;background-color:transparent;border:0}.hidden{visibility:hidden!important}@-ms-viewport{width:device-width}@media (max-width:767px){.visible-xs{display:block!important}table.visible-xs{display:table}tr.visible-xs{display:table-row!important}td.visible-xs,th.visible-xs{display:table-cell!important}}@media (min-width:768px) and (max-width:991px){.visible-sm{display:block!important}table.visible-sm{display:table}tr.visible-sm{display:table-row!important}td.visible-sm,th.visible-sm{display:table-cell!important}}@media (min-width:992px) and (max-width:1199px){.visible-md{display:block!important}table.visible-md{display:table}tr.visible-md{display:table-row!important}td.visible-md,th.visible-md{display:table-cell!important}}@media (min-width:1200px){.visible-lg{display:block!important}table.visible-lg{display:table}tr.visible-lg{display:table-row!important}td.visible-lg,th.visible-lg{display:table-cell!important}.hidden-lg{display:none!important}}@media (max-width:767px){.hidden-xs{display:none!important}}@media (min-width:768px) and (max-width:991px){.hidden-sm{display:none!important}}@media (min-width:992px) and (max-width:1199px){.hidden-md{display:none!important}}.visible-print{display:none!important}@media print{.visible-print{display:block!important}table.visible-print{display:table}tr.visible-print{display:table-row!important}td.visible-print,th.visible-print{display:table-cell!important}.hidden-print{display:none!important}}#header-holder,#search-btn,body{background-color:#fff}#theme a,footer .menu li a,header,header .menu li a{color:#666e75}.widget img,article img{height:auto;max-width:100%}body{font-family:'Open Sans',serif;font-weight:300}a{color:#f76b61}a:hover{color:#20b2aa!important}h1,h2,h3,h4,h5,h6{font-weight:300;color:#787878}img{vertical-align:middle;width:100%;border-radius:10px}#header-holder{margin-bottom:15px;border-bottom:1px solid #e1e2e3}header{padding:15px 0}header #description p{margin:2px 0 0;float:left}header .menu{margin:1px 0 10px;padding:0 0 0 15px;float:left}footer .menu li,header .menu li{text-transform:uppercase;font-size:12px;margin-right:10px}header .menu li{display:inline;line-height:12px}header #nav-search{padding-left:0}#search-btn{color:#f76b61;float:right;padding:3px 7px;border:0;-webkit-border-radius:3px;-moz-border-radius:3px;border-radius:3px}#search-btn:hover{color:#20b2aa}#search-holder{display:none;width:100%;float:right}#search-holder input[type=search]{width:100%;margin-bottom:0}#footer-holder{background-color:#e3e6e8}footer{font-size:12px}footer .menu{padding:0}footer .menu li{display:inline}#copyright{float:left;margin-right:30px}#theme{float:right;padding-top:5px}#theme .glyphicon{color:#999}#credit{color:#666e75;margin-right:8px}.logo{color:#f76b61;padding-top:10px;margin-bottom:0;display:inline-block;font-size:50px;font-weight:700}#primary-menu ul{margin:15px 0 30px -15px;padding:0}#primary-menu li{display:block}#primary-menu li a{color:#ccc;font-weight:500;display:block;padding:0}#sidebar-right .widget h2,#sidebar-right .widget h3,#sidebar-right .widget h4,#sidebar .widget h2,#sidebar .widget h3,#sidebar .widget h4{font-weight:400;font-size:16px;margin:0 0 15px}#primary-menu .current-menu-item,#primary-menu .nav-clicked,#primary-menu li:hover,#primary-menu li:hover a,#primary-menu li:hover span{color:#fff}#primary-menu i{float:right;color:#555;margin-right:15px;position:relative;top:3px;font-size:16px}#primary-menu .nav-clicked a,#primary-menu .nav-clicked span,#primary-menu .sub-menu li a{color:#fff}#primary-menu .sub-menu{margin:0;display:none}#primary-menu .sub-menu .fa,#primary-menu .sub-menu .glyphicon{display:none}#primary-menu .sub-menu li{background-color:#1b1b1b;font-size:13px}#primary-menu .sub-menu li a:hover{color:#20b2aa}#sidebar{height:100%;background-color:#2b2b2b;text-align:center;padding-top:75px}#sidebar .widget{color:#ccc;margin-bottom:30px}#sidebar .widget h2,#sidebar .widget h3,#sidebar .widget h4{color:#fff;font-size:16px}#sidebar #s{width:60%}#sidebar #searchsubmit{background-color:#1b1b1b;border-bottom-color:#383838}.navbar-toggle{border-color:#555;position:absolute;top:10px;right:10px;float:right}.navbar-toggle span{background-color:#555}.navbar-collapse{padding:0;max-height:none}#sidebar-right{color:#666;padding-left:0}#sidebar-right .widget{padding:15px;border-bottom:1px solid #e1e2e3;margin-bottom:15px}#sidebar-right .zebra{background-color:#fff;color:#ddd;border-radius:8px}#sidebar .widget ul{margin:0 ;padding:0}#sidebar-right .widget ul{margin:0;padding:0;list-style:none}#sidebar-right .widget ul li{margin:0;padding:0 0 4px}.widget img{display:inline-block}.widget select{border:1px solid #e1e2e3;margin-right:5px;padding:10px;width:100%;color:#666;margin-bottom:10px}.widget_search label{display:none}.post-body{padding:10px 30px 15px;color:#ccc;font-size:14px;text-align:justify}.post-body:hover{color:#555}.post-title{text-align:left;margin:5px 0 10px;line-height:1.2;}div#blog-pager a {padding: 10px;border: 1px solid #ddd;display: block;float: left;border-radius: 10px;}#blog-pager,.aligncenter{text-align:center}#post-title,.post-title a{color:#787878;font-size:26px;font-weight:300;-webkit-text-stroke:.5px}.post-date-author{font-size:17px;margin:5px 0 10px}article,article blockquote{border-bottom:1px solid #e1e2e3;margin-bottom:30px}.post-date-author span{color:#ccc;font-size:15px;margin-right:8px}.post-date-author .glyphicon-user{margin-left:8px}article{font-size:16px;-webkit-text-stroke:.3px;background-color:#fff}article img{display:inline-block}article h1{font-size:32px}article h2{font-size:29px}article h3{font-size:26px}article h4{font-size:23px}article h5{font-size:20px}article h6{font-size:16px}article .attachment-featured{width:100%}article .gallery-caption,article .wp-caption{max-width:97%;font-size:14px}article ul{margin:0;padding-left:16px}article ol{margin:0;padding-left:22px}article blockquote{border-top:4px solid #e1e2e3;margin-top:30px}article blockquote p{font-size:20px}article blockquote cite{font-size:14px;width:100%;display:block;margin-top:15px}article table{width:100%}article table td,article table th{border:1px solid #e1e2e3;padding:8px}article table th{background-color:#f7f7f7;font-weight:400}article dt{font-weight:400}article dd{margin:0 0 15px}.alignleft{float:left;margin-right:15px}.alignright{float:right;margin-left:15px}.post-meta{padding:15px 30px}.post-meta p{display:inline;margin-right:15px;color:#999;font-size:12px}#navbar-iframe,.screen-reader-text,.widget-item-control,h2.date-header{display:none}.post-meta span{margin-right:5px;color:#ccc}input[type=password],input[type=search],input[type=text],textarea{border:1px solid #e1e2e3;margin-right:5px;padding:10px;width:70%;color:#666;margin-bottom:10px}input[type=reset],input[type=submit]{background-color:#f7f7f7;border:0;border-bottom:3px solid #e1e2e3;color:#999;padding:10px 12px;text-align:center}@media (max-width:767px){#search-holder,#sidebar #primary-menu li{padding-left:15px}header #description{float:left;width:90%}header #description p{margin-bottom:10px}.logo{margin-bottom:30px}#sidebar{height:auto;position:relative;padding-bottom:1px}#sidebar #primary-menu ul{margin:0 0 30px}.col-content{max-width:100%}footer .menu{float:left}#footer-widgets{margin-top:0}#footer-widgets .col{width:100%}}@media (min-width:768px) and (max-width:991px){#header-holder{float:left;width:100%}header .menu{margin:10px 0;padding:0}header #nav-search{padding-left:15px}#sidebar{height:auto;position:relative}#primary-menu ul{margin:0}#primary-menu li{float:left;margin-right:12px;font-size:16px}#primary-menu .current-menu-item,#primary-menu li:hover{background-color:transparent}#primary-menu li a{padding:0}#primary-menu li i{display:none}.navbar-collapse{margin-bottom:30px}.col-content{max-width:100%}#footer-widgets{margin-top:0}#footer-widgets .col{width:100%}}@media (min-width:992px) and (max-width:1199px){#sidebar-right{padding-left:15px}}@media (min-width:1200px){.col-content{max-width:800px}}h2.date-header{margin:10px 0}.main .widget{margin:0 0 5px;padding:0 0 2px}.main .Blog{border-bottom-width:0}#header .description{color:#fff;font-size:14px;text-shadow:0 1px 0 #000}#comments{padding:10px 30px 15px;margin-bottom:20px;background:#fff}#comments h4{font-size:22px;margin-bottom:10px}.deleted-comment{font-style:italic;color:gray}#blog-pager-newer-link{float:left}#blog-pager-older-link{float:right}#blog-pager{padding:5px;margin:10px 0}.feed-links{clear:both;margin:5px 0 10px}#navbar-iframe{height:0;visibility:hidden}.separator a[style="margin-left: 1em; margin-right: 1em;"]{margin-left:auto!important;margin-right:auto!important}.header-section .widget{margin:0 0 10px!important}.site-title{margin:10px 0;text-transform:uppercase;}.site-description{font-size:14px!important;display:none}.PopularPosts .widget-content ul li{padding:6px 0!important}.reaction-buttons table{margin-bottom:5px}.reaction-buttons table,.reaction-buttons td{border:none!important}.pbtthumbimg{float:left;margin:0 10px 5px 0;padding:0;border:0 solid #eee;background:#fff;width:200px;height:auto}.post a.morer{padding:10px;float:left;border:1px solid;border-radius:10px;color:#f76b61}.popular-posts{text-align:left;}.popular-posts li{border-bottom:1px solid rgba(0, 0, 0, 0.15); list-style:none;}.popular-posts img{border-radius:50%;box-shadow:-1px -1px 4px #8a8a8a;padding:0;width:70px;height:70px}#sidebar-right .Label ul li{padding:10px;display:block;border:1px solid #eee;float:left;margin:2px;border-radius:10px}.post a{color:#555}
::-webkit-scrollbar { width: 12px;}::-webkit-scrollbar-track {  -webkit-box-shadow: inset 0 0 6px rgba(0,0,0,0.3);border-radius: 10px;}::-webkit-scrollbar-thumb {border-radius: 10px;-webkit-box-shadow: inset 0 0 6px rgba(0,0,0,0.5); }.breadcrumbs {padding:5px 5px 5px 0px;margin: 0px 0px 15px 0px;font-size:95%;line-height: 1.4em;border-bottom:2px solid #e6e4e3;}.breadcrumbs :hover{border-bottom:2px dashed #e6e4e3;background:#f1f1f1;}.sosial {margin: 20px 0;padding: 10px 0;border-top: 1px solid #333;border-bottom: 1px solid #333;}.sosial a { display: inline-block;padding: 0 10px;color: #bdbdbd;}
#related-posts{float:left;width:100%;margin-top:30px}#related-posts a{width:192px;padding:0!important;margin-right:20px;background:#fff}#related-posts img{width:100%;height:auto!important}#related-posts a:last-child{margin:0}#related-posts a div{font-size:16px!important;text-align:center;margin:20px 10px!important;width:90%!important;color:#191919;line-height:27px!important}line-height: 40px!important; #related-posts h2{display:none}

    ]]></b:skin>
    <b:template-skin>
      body#layout{background-color:#fff;border:none}body#layout div#main-blog-section{background:#ff753f;border:none;}body#layout .locked-widget .widget-content,body#layout div.section{border-radius:10px; border:none;}body#layout:after { content: &quot;Copyrights @ widiyanata.com&quot;;}#layout body#layout div#sidebar-rightedt{float:right;width:25%}body#layout div#sidebar-left{background-color:#555} #layout .col-content{width: 65%;float:left}#layout div#sidebar-rightedt {float: left; width: 35%}body#layout:after { font-size: 14px;padding: 14.5px 0;float: left;background: #fff;color: #555;font-family: open sans;width: 100%;z-index: 100;position: relative;border-top: 1px solid #d2d2d2;}#layout div#sidebar::before {font-size: 30px;padding: 14.5px 0;float: left;color: #fb7a09;width: 100%;z-index: 100;position: relative;    margin-bottom: 20px;}
      #layout div#sidebar::before {content: &quot;Admin Panel&quot;;}
    </b:template-skin>
    <script src='https://code.jquery.com/jquery-2.2.4.min.js' type='text/javascript'/>
    <script type='text/javascript'>
      summary_noimg = 300;
      summary_img = 200;
      img_thumb_height = 150;
      img_thumb_width = 200; 
    </script>
    <script type='text/javascript'>
      //<![CDATA[
      function removeHtmlTag(e,n){if(-1!=e.indexOf("<")){for(var t=e.split("<"),i=0;i<t.length;i++)-1!=t[i].indexOf(">")&&(t[i]=t[i].substring(t[i].indexOf(">")+1,t[i].length));e=t.join("")}for(n=n<e.length-1?n:e.length-2;" "!=e.charAt(n-1)&&-1!=e.indexOf(" ",n);)n++;return e=e.substring(0,n-1),e+"..."}function createSummaryAndThumb(e){var n=document.getElementById(e),t="",i=n.getElementsByTagName("img"),m=summary_noimg;i.length>=1&&(t='<img src="'+i[0].src+'" class="pbtthumbimg"/>',m=summary_img);var r=t+'<div style="line-height:1.6;"><p>'+removeHtmlTag(n.innerHTML,m)+"</p></div>";n.innerHTML=r}
      //]]>
    </script>
    <!--Related Posts with thumbnails Scripts and Styles Start-->
    <b:if cond='data:blog.pageType == &quot;item&quot;'>
      <script type='text/javascript'>
        //<![CDATA[
        //Related Posts Setting
        var defaultnoimage="http://2.bp.blogspot.com/-A4vEH9M5EJM/V5_Vk6jiiwI/AAAAAAAAA-g/vPv5uuJK1i0/s000/no_image.jpg";
        var maxresults=3;
        var splittercolor="#fff";
        var relatedpoststitle=""
        //]]>
      </script>
      <script type='text/javascript'>
        //<![CDATA[
        function related_results_labels_thumbs(e){for(var t=0;t<e.feed.entry.length;t++){var l=e.feed.entry[t];relatedTitles[relatedTitlesNum]=l.title.$t;try{thumburl[relatedTitlesNum]=l.media$thumbnail.url,thumburl=thumburl.replace("/s72-c/","/s300-a/")}catch(r){s=l.content.$t,a=s.indexOf("<img"),b=s.indexOf('src="',a),c=s.indexOf('"',b+5),d=s.substr(b+5,c-b-5),-1!=a&&-1!=b&&-1!=c&&""!=d?thumburl[relatedTitlesNum]=d:"undefined"!=typeof defaultnoimage?thumburl[relatedTitlesNum]=defaultnoimage:thumburl[relatedTitlesNum]="http://2.bp.blogspot.com/-A4vEH9M5EJM/V5_Vk6jiiwI/AAAAAAAAA-g/vPv5uuJK1i0/s000/no_image.jpg"}relatedTitles[relatedTitlesNum].length>35&&(relatedTitles[relatedTitlesNum]=relatedTitles[relatedTitlesNum].substring(0,35)+"...");for(var n=0;n<l.link.length;n++)"alternate"==l.link[n].rel&&(relatedUrls[relatedTitlesNum]=l.link[n].href,relatedTitlesNum++)}}function removeRelatedDuplicates_thumbs(){for(var e=new Array(0),t=new Array(0),l=new Array(0),r=0;r<relatedUrls.length;r++)contains_thumbs(e,relatedUrls[r])||(e.length+=1,e[e.length-1]=relatedUrls[r],t.length+=1,l.length+=1,t[t.length-1]=relatedTitles[r],l[l.length-1]=thumburl[r]);relatedTitles=t,relatedUrls=e,thumburl=l}function contains_thumbs(e,t){for(var l=0;l<e.length;l++)if(e[l]==t)return!0;return!1}function printRelatedLabels_thumbs(e){var t;t="undefined"!=typeof splittercolor?splittercolor:"#DDDDDD";for(var l=0;l<relatedUrls.length;l++)relatedUrls[l]!=e&&relatedTitles[l]||(relatedUrls.splice(l,1),relatedTitles.splice(l,1),thumburl.splice(l,1),l--);var r=Math.floor((relatedTitles.length-1)*Math.random()),l=0;for(relatedTitles.length>0&&document.write("<h2>"+relatedpoststitle+"</h2>"),document.write('<div style="clear: both;"/>');l<relatedTitles.length&&20>l&&l<maxresults;)document.write('<a style="text-decoration:none;padding:5px;float:left; padding-right: 13px;'),0!=l?document.write("border-left:solid 0.5px "+t+';"'):document.write('"'),document.write(' href="'+relatedUrls[r]+'"><img style="width: 166; height: 115px;;" src="'+thumburl[r]+'"/><br/><div style="width:166px;padding-left:3px;height:65px;border: 0pt none ; margin: 3px 0pt 0pt; padding: 0pt; font-style: normal; font-variant: normal; font-weight: normal;font-size: 14px; line-height: 25px; font-size-adjust: none; font-stretch: normal;">'+relatedTitles[r]+"</div></a>"),l++,r<relatedTitles.length-1?r++:r=0;document.write("</div>"),relatedUrls.splice(0,relatedUrls.length),thumburl.splice(0,thumburl.length),relatedTitles.splice(0,relatedTitles.length)}var relatedTitles=new Array,relatedTitlesNum=0,relatedUrls=new Array,thumburl=new Array;
        //]]>
      </script>
    </b:if>
    <!--Related Posts with thumbnails Scripts and Styles End-->
  </head>
  <body>
    <div class='container-fluid'>
      <div class='row'>
        <div class='col-sm-12 col-md-3 col-lg-3' id='sidebar'>
          <b:section class='header-section' id='header-section' maxwidgets='1' showaddelement='no'>
            <b:widget id='Header1' locked='true' title='Rareti (Header)' type='Header' version='1' visible='true'>
              <b:includable id='main'>
                <b:if cond='data:useImage'>
                  <b:if cond='data:imagePlacement == &quot;REPLACE&quot;'>
                    <!--Show just the image, no text-->
                    <div id='header-inner'>
                      <a expr:href='data:blog.homepageUrl' style='display: block'>
                        <img expr:alt='data:title' expr:height='data:height' expr:id='data:widget.instanceId + &quot;_headerimg&quot;' expr:src='data:sourceUrl' expr:width='data:width' style='display: block;padding-left:0px;padding-top:0px;'/>
                      </a>
                    </div>
                    <b:else/>
                    <!--
Show image as background to text. You can't really calculate the width
reliably in JS because margins are not taken into account by any of
clientWidth, offsetWidth or scrollWidth, so we don't force a minimum
width if the user is using shrink to fit.
This results in a margin-width's worth of pixels being cropped. If the
user is not using shrink to fit then we expand the header.
-->
                    <div expr:style='&quot;background-image: url(\&quot;&quot; + data:sourceUrl + &quot;\&quot;); &quot;                      + &quot;background-position: &quot;                      + data:backgroundPositionStyleStr + &quot;; &quot;                      + data:widthStyleStr                      + &quot;min-height: &quot; + data:height + &quot;px;&quot;                      + &quot;_height: &quot; + data:height + &quot;px;&quot;                      + &quot;background-repeat: no-repeat; &quot;' id='header-inner'>
                      <div class='titlewrapper' style='background: transparent'>
                        <h1 class='site-title' style='background: transparent; border-width: 0px'>
                          <b:include name='title'/>
                        </h1>
                      </div>
                      <b:include name='description'/>
                    </div>
                  </b:if>
                  <b:else/>
                  <!--No header image -->
                  <div id='header-inner'>
                    <div class='titlewrapper'>
                      <h1 class='site-title'>
                        <b:include name='title'/>
                      </h1>
                    </div>
                    <b:include name='description'/>
                  </div>
                </b:if>
              </b:includable>
              <b:includable id='description'>
                <h2 class='site-description'>
                  <data:description/>
                </h2>
              </b:includable>
              <b:includable id='title'>
                <a class='logo' expr:href='data:blog.homepageUrl'>
                  <data:title/>
                </a>
              </b:includable>
            </b:widget>
          </b:section>
          

<!--
  _____    _ _ _     _
 | ____|__| (_) |_  | |__   ___ _ __ ___
 |  _| / _` | | __| | '_ \ / _ \ '__/ _ \
 | |__| (_| | | |_  | | | |  __/ | |  __/
 |_____\__,_|_|\__| |_| |_|\___|_|  \___|

 Edit the code below using your own information.
 Happy blogging from BTemplates.com :)
-->
<div class='sosial'>
            <a class='fa fa-2x fa-facebook' href='#'>
              <span class='sr-only'>
                facebook
              </span>
            </a>
            <a class='fa fa-2x fa-twitter' href='#'>
              <span class='sr-only'>
                twitter
              </span>
            </a>
            <a class='fa fa-2x fa-github' href='#'>
              <span class='sr-only'>
                github
              </span>
            </a>
            <a class='fa fa-2x fa-google-plus' href='#'>
              <span class='sr-only'>
                google plus
              </span>
            </a>
          </div>
          <button class='navbar-toggle' data-target='.navbar-collapse' data-toggle='collapse' type='button'>
            <span class='sr-only'>
              Toggle navigation
            </span>
            <span class='icon-bar'/>
            <span class='icon-bar'/>
            <span class='icon-bar'/>
          </button>
          <div class='collapse navbar-collapse'>
            <div class='menu-testing-menu-container' id='primary-menu'>
              <b:section class='top-menutop' id='top-menutop' maxwidgets='1' showaddelement='no'>
                <b:widget id='PageList8' locked='false' title='Pages - Menu' type='PageList' version='1' visible='true'>
                  <b:includable id='main'>
                    <b:if cond='data:title'>
                      <!--<h2><data:title/></h2>-->
                    </b:if>
                    <div class='widget-content'>
                      <ul class='menu'>
                        <b:loop values='data:links' var='link'>
                          <b:if cond='data:link.isCurrentPage'>
                            <li id='currentpage'>
                              <a expr:href='data:link.href'>
                                <data:link.title/>
                              </a>
                            </li>
                            <b:else/>
                            <li>
                              <a expr:href='data:link.href'>
                                <data:link.title/>
                              </a>
                            </li>
                          </b:if>
                        </b:loop>
                      </ul>
                      <b:include name='quickedit'/>
                    </div>
                  </b:includable>
                </b:widget>
              </b:section>
            </div>
          </div>
          <b:section class='sidebar-left' id='sidebar-left' preferred='yes'>
            <b:widget id='Attribution1' locked='true' title='' type='Attribution' visible='true'>
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
          </b:section>
        </div>
        <div id='header-holder'>
          <header class='clearfix'>
            <div class='col-sm-12 col-md-6 col-md-offset-3 col-lg-7 col-lg-offset-2 col-content' id='description'>
              <h1 class='sr-only'>
                <data:blog.pageName/>
              </h1>
              <p class='siteintro sr-only'/>
            </div>
            <div class='col-sm-12 col-md-3' id='nav-search'>
              <div id='search-holder'>
                <form expr:action='data:blog.homepageUrl + &quot;search/&quot;' id='search-form' method='get' role='search'>
                  <input class='search-field' name='q' type='search' value='Search...'/>
                </form>
              </div>
              <button id='search-btn'>
                <i class='fa fa-2x fa-search'/>
              </button>
            </div>
          </header>
        </div>
        <div class='col-sm-12 col-md-9 col-md-offset-3 col-lg-6 col-lg-offset-3 col-content'>
          <b:section class='main-blog-section' id='main-blog-section' showaddelement='no'>
            <b:widget id='Blog1' locked='true' title='Blog Posts' type='Blog' version='1' visible='true'>
              <b:includable id='main' var='top'>
                <b:if cond='data:mobile == &quot;false&quot;'>
                  <!-- posts -->
                  <div class='blog-posts hfeed'>
                    <b:include data='top' name='status-message'/>
                    <b:include data='posts' name='breadcrumb'/>
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
                          <b:if cond='data:post.showThreadedComments'>
                            <b:include data='post' name='threaded_comments'/>
                            <b:else/>
                            <b:include data='post' name='comments'/>
                          </b:if>
                        </b:if>
                        <b:if cond='data:blog.pageType == &quot;item&quot;'>
                          <b:if cond='data:post.showThreadedComments'>
                            <b:include data='post' name='threaded_comments'/>
                            <b:else/>
                            <b:include data='post' name='comments'/>
                          </b:if>
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
                  <div style='clear: both;'/>
                  <b:if cond='data:blog.pageType != &quot;item&quot;'>
                    <!-- navigation -->
                    <b:include name='nextprev'/>
                  </b:if>
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
              <b:includable id='breadcrumb' var='posts'>
                <b:if cond='data:blog.homepageUrl == data:blog.url'>
                  <!-- No breadcrumb on home page -->
                  <b:else/>
                  <b:if cond='data:blog.pageType == &quot;item&quot;'>
                    <!-- breadcrumb for the post page -->
                    <p class='breadcrumbs'>
                      <span class='post-labels'>
                        <a expr:href='data:blog.homepageUrl' rel='tag'>
                          Home
                        </a>
                        <b:loop values='data:posts' var='post'>
                          <b:if cond='data:post.labels'>
                            <b:loop values='data:post.labels' var='label'>
                              <b:if cond='data:label.isLast == &quot;true&quot;'>
                                &#187;
                                <a expr:href='data:label.url' rel='tag'>
                                  <data:label.name/>
                                </a>
                              </b:if>
                            </b:loop>
                            <b:else/>
                            &#187; Unlabelled
                          </b:if>
                          &#187; 
                          <span>
                            <data:post.title/>
                          </span>
                        </b:loop>
                      </span>
                    </p>
                    <b:else/>
                    <b:if cond='data:blog.pageType == &quot;archive&quot;'>
                      <!-- breadcrumb for the label archive page and search pages.. -->
                      <p class='breadcrumbs'>
                        <span class='post-labels'>
                          <a expr:href='data:blog.homepageUrl'>
                            Home
                          </a>
                          &#187; Archives for 
                          <data:blog.pageName/>
                        </span>
                      </p>
                      <b:else/>
                      <b:if cond='data:blog.pageType == &quot;index&quot;'>
                        <p class='breadcrumbs'>
                          <span class='post-labels'>
                            <b:if cond='data:blog.pageName == &quot;&quot;'>
                              <a expr:href='data:blog.homepageUrl'>
                                Home
                              </a>
                              &#187; All posts
                              <b:else/>
                              <a expr:href='data:blog.homepageUrl'>
                                Home
                              </a>
                              &#187; Posts filed under 
                              <data:blog.pageName/>
                            </b:if>
                          </span>
                        </p>
                      </b:if>
                    </b:if>
                  </b:if>
                </b:if>
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
                <b:if cond='data:post.commentSource == 1'>
                  <span class='cmt_count_iframe_holder' expr:data-count='data:post.numComments' expr:data-onclick='data:post.addCommentOnclick' expr:data-post-url='data:post.url' expr:data-url='data:post.canonicalUrl'>
                  </span>
                  <b:else/>
                  <a class='comment-link' expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'>
                    <data:post.commentLabelFull/>
                    :
                  </a>
                </b:if>
              </b:includable>
              <b:includable id='comment_picker' var='post'>
                <b:if cond='data:post.commentSource == 1'>
                  <b:include data='post' name='iframe_comments'/>
                  <b:else/>
                  <b:if cond='data:post.showThreadedComments'>
                    <b:include data='post' name='threaded_comments'/>
                    <b:else/>
                    <b:include data='post' name='comments'/>
                  </b:if>
                </b:if>
              </b:includable>
              <b:includable id='comments' var='post'>
                <div class='comments' id='comments'>
                  <a name='comments'/>
                  <b:if cond='data:post.allowComments'>
                    <h4>
                      <b:if cond='data:post.numComments == 1'>
                        1 
                        <data:commentLabel/>
                        :
                        <b:else/>
                        <data:post.numComments/>
                        <data:commentLabelPlural/>
                        :
                      </b:if>
                    </h4>
                    <b:if cond='data:post.commentPagingRequired'>
                      <span class='paging-control-container'>
                        <a expr:class='data:post.oldLinkClass' expr:href='data:post.oldestLinkUrl'>
                          <data:post.oldestLinkText/>
                        </a>
                        &#160;
                        <a expr:class='data:post.oldLinkClass' expr:href='data:post.olderLinkUrl'>
                          <data:post.olderLinkText/>
                        </a>
                        &#160;
                        <data:post.commentRangeText/>
                        &#160;
                        <a expr:class='data:post.newLinkClass' expr:href='data:post.newerLinkUrl'>
                          <data:post.newerLinkText/>
                        </a>
                        &#160;
                        <a expr:class='data:post.newLinkClass' expr:href='data:post.newestLinkUrl'>
                          <data:post.newestLinkText/>
                        </a>
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
                <b:if cond='data:post.allowComments'>
                  <script expr:src='data:post.commentSrc' type='text/javascript'/>
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
                      <h3 class='mobile-index-title entry-title'>
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
                            <a class='comment-link' expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'>
                              <b:if cond='data:post.numComments == 1'>
                                1 
                                <data:top.commentLabel/>
                                <b:else/>
                                <data:post.numComments/>
                                <data:top.commentLabelPlural/>
                              </b:if>
                            </a>
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
                  <b:include data='posts' name='breadcrumb'/>
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
                      <div class='post hentry uncustomized-post-template'>
                        <a expr:name='data:post.id'/>
                        <b:if cond='data:post.title'>
                          <h3 class='post-title entry-title'>
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
                          </h3>
                        </b:if>
                        <div class='post-header'>
                          <div class='post-header-line-1'/>
                        </div>
                        <div class='post-body entry-content' expr:id='&quot;post-body-&quot; + data:post.id'>
                          <data:post.body/>
                          <div style='clear: both;'/>
                          <!-- clear for photos floats -->
                        </div>
                        <div class='post-footer'>
                          <div class='post-footer-line post-footer-line-1'>
                            <span class='post-author vcard'>
                              <b:if cond='data:top.showAuthor'>
                                <b:if cond='data:post.authorProfileUrl'>
                                  <span class='fn'>
                                    <a expr:href='data:post.authorProfileUrl' rel='author' title='author profile'>
                                      <data:post.author/>
                                    </a>
                                  </span>
                                  <b:else/>
                                  <span class='fn'>
                                    <data:post.author/>
                                  </span>
                                </b:if>
                              </b:if>
                            </span>
                            <span class='post-timestamp'>
                              <b:if cond='data:top.showTimestamp'>
                                <data:top.timestampLabel/>
                                <b:if cond='data:post.url'>
                                  <a class='timestamp-link' expr:href='data:post.url' rel='bookmark' title='permanent link'>
                                    <abbr class='published' expr:title='data:post.timestampISO8601'>
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
                                    <a class='comment-link' expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'>
                                      <b:if cond='data:post.numComments == 1'>
                                        1 
                                        <data:top.commentLabel/>
                                        <b:else/>
                                        <data:post.numComments/>
                                        <data:top.commentLabelPlural/>
                                      </b:if>
                                    </a>
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
                        <b:if cond='data:post.showThreadedComments'>
                          <b:include data='post' name='threaded_comments'/>
                          <b:else/>
                          <b:include data='post' name='comments'/>
                        </b:if>
                      </b:if>
                      <b:if cond='data:blog.pageType == &quot;item&quot;'>
                        <b:if cond='data:post.showThreadedComments'>
                          <b:include data='post' name='threaded_comments'/>
                          <b:else/>
                          <b:include data='post' name='comments'/>
                        </b:if>
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
                <div class='article-holder'>
                  <article class='post hentry'>
                    <a expr:name='data:post.id'/>
                    <div class='post-header-line-1'/>
                    <div class='post-body entry-content'>
                      <h2 class='post-title entry-title'>
                        <b:if cond='data:post.link'>
                          <a expr:href='data:post.link'>
                            <data:post.title/>
                          </a>
                          <b:else/>
                          <b:if cond='data:post.url'>
                            <a expr:href='data:post.url'>
                              <data:post.title/>
                            </a>
                            <b:else/>
                            <data:post.title/>
                          </b:if>
                        </b:if>
                      </h2>
                      <b:if cond='data:blog.pageType != &quot;static_page&quot;'>
                        <p class='post-date-author'>
                          <i class='fa fa-calendar'/>
                          &amp;nbsp;&amp;nbsp;
                          <data:post.timestamp/>
                          &amp;nbsp;&amp;nbsp;
                          <i class='fa fa-user'/>
                          &amp;nbsp;&amp;nbsp;
                          <b:if cond='data:post.authorProfileUrl'>
                            <a expr:href='data:post.authorProfileUrl' rel='author' title='author profile'>
                              <data:post.author/>
                            </a>
                            <b:else/>
                            <data:post.author/>
                          </b:if>
                        </p>
                        <hr/>
                      </b:if>
                      <b:if cond='data:blog.pageType != &quot;static_page&quot;'>
                        <b:if cond='data:blog.pageType != &quot;item&quot;'>
                          <div expr:id='&quot;summary&quot; + data:post.id'>
                            <data:post.body/>
                          </div>
                          <script type='text/javascript'>
                            createSummaryAndThumb(&quot;summary<data:post.id/>&quot;);</script>
                        </b:if>
                      </b:if>
                      <b:if cond='data:blog.pageType == &quot;item&quot;'>
                        <data:post.body/>
                      </b:if>
                      <b:if cond='data:blog.pageType == &quot;static_page&quot;'>
                        <data:post.body/>
                      </b:if>
                      <b:if cond='data:blog.pageType != &quot;static_page&quot;'>
                        <b:if cond='data:blog.pageType != &quot;item&quot;'>
                          <div style='float:left;padding-right:10px;margin-top:10px;'>
                            <a class='morer' expr:href='data:post.url'>
                              Read More
                            </a>
                          </div>
                        </b:if>
                      </b:if>
                      <b:if cond='data:blog.pageType == &quot;item&quot;'>
                        <div style='clear:both;'/>
                        <div class='post-share-buttons'>
                          <b:include data='post' name='shareButtons'/>
                        </div>
                        <span class='reaction-buttons'>
                          <b:if cond='data:top.showReactions'>
                            <table border='0' cellpadding='0' width='100%'>
                              <tr>
                                <td style='font-size:12px;padding-top:2px;' valign='top'>
                                  <span class='reactions-label'>
                                    <data:top.reactionsLabel/>
                                  </span>
                                </td>
                                <td>
                                  <iframe allowtransparency='true' class='reactions-iframe' expr:src='data:post.reactionsUrl' frameborder='0' name='reactions' scrolling='no'/>
                                </td>
                              </tr>
                            </table>
                          </b:if>
                        </span>
                      </b:if>
                      <div style='clear: both;'/>
                      <!-- clear for photos floats -->
                    </div>
                    <div class='post-meta'>
                      <b:if cond='data:blog.pageType != &quot;static_page&quot;'>
                        <b:if cond='data:post.labels'>
                          <p>
                            <i class='fa fa-folder-open'/>
                            &amp;nbsp;&amp;nbsp;
                            <b:loop values='data:post.labels' var='label'>
                              <a expr:href='data:label.url' rel='tag'>
                                <data:label.name/>
                              </a>
                              <b:if cond='data:label.isLast != &quot;true&quot;'>
                                / 
                              </b:if>
                            </b:loop>
                          </p>
                        </b:if>
                        <b:if cond='data:post.allowComments'>
                          <p>
                            <i class='fa fa-comment'/>
                            &amp;nbsp;&amp;nbsp;
                            <a expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'>
                              <b:if cond='data:post.numComments == 0'>
                                No Comments
                              </b:if>
                              <b:if cond='data:post.numComments == 1'>
                                1 Comment
                              </b:if>
                              <b:if cond='data:post.numComments &gt;= 2'>
                                <data:post.numComments/>
                                Comments
                              </b:if>
                            </a>
                          </p>
                        </b:if>
                      </b:if>
                    </div>
                    <div class='post-footer sr-only'>
                      <div class='post-footer-line post-footer-line-1'>
                        <span class='post-author vcard'>
                          <b:if cond='data:top.showAuthor'>
                            <b:if cond='data:post.authorProfileUrl'>
                              <span class='fn'>
                                <a expr:href='data:post.authorProfileUrl' rel='author' title='author profile'>
                                  <data:post.author/>
                                </a>
                              </span>
                              <b:else/>
                              <span class='fn'>
                                <data:post.author/>
                              </span>
                            </b:if>
                          </b:if>
                        </span>
                        <span class='post-timestamp'>
                          <b:if cond='data:top.showTimestamp'>
                            <data:top.timestampLabel/>
                            <b:if cond='data:post.url'>
                              <a class='timestamp-link' expr:href='data:post.url' rel='bookmark' title='permanent link'>
                                <abbr class='published' expr:title='data:post.timestampISO8601'>
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
                                <a class='comment-link' expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'>
                                  <b:if cond='data:post.numComments == 1'>
                                    1 
                                    <data:top.commentLabel/>
                                    <b:else/>
                                    <data:post.numComments/>
                                    <data:top.commentLabelPlural/>
                                  </b:if>
                                </a>
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
                    <b:if cond='data:blog.pageType == &quot;item&quot;'>
                      <!--Related Posts-->
                      <div id='related-posts'>
                        <b:loop values='data:post.labels' var='label'>
                          <b:if cond='data:label.isLast != &quot;true&quot;'>
                          </b:if>
                          <script expr:src='&quot;/feeds/posts/default/-/&quot; + data:label.name + &quot;?alt=json-in-script&amp;callback=related_results_labels_thumbs&amp;max-results=6&quot;' type='text/javascript'/>
                        </b:loop>
                        <script type='text/javascript'>
                          removeRelatedDuplicates_thumbs();
                          printRelatedLabels_thumbs(&quot;<data:post.url/>&quot;);
                        </script>
                      </div>
                    </b:if>
                  </article>
                </div>
                <div style='clear: both;'/>
                <b:if cond='data:blog.pageType == &quot;item&quot;'>
                  <!-- navigation -->
                  <b:include name='nextprev'/>
                </b:if>
              </b:includable>
              <b:includable id='postQuickEdit' var='post'>
                <b:if cond='data:post.editUrl'>
                  <span expr:class='&quot;item-control &quot; + data:post.adminClass'>
                    <a expr:href='data:post.editUrl' expr:title='data:top.editPostMsg'>
                      <img alt='' class='icon-action' height='18' src='https://img2.blogblog.com/img/icon18_edit_allbkg.gif' width='18'/>
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
        <div class='col-sm-12 col-md-9 col-md-offset-3 col-lg-3 col-lg-offset-0' id='sidebar-rightedt'>
          <b:section class='sidebar-right' id='sidebar-right' preferred='yes'>
            <b:widget id='PopularPosts1' locked='false' title='Popular Posts' type='PopularPosts' version='1' visible='true'>
              <b:includable id='main'>
                <b:if cond='data:title'>
                  <h3>
                    <data:title/>
                  </h3>
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
                                  <a expr:href='data:post.href' target='_blank'>
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
                                  <a expr:href='data:post.href' target='_blank'>
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
            <b:widget id='HTML1' locked='false' title='' type='HTML' visible='true'>
              <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
            </b:widget>
            <b:widget id='HTML2' locked='false' title='' type='HTML' visible='true'>
              <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
            </b:widget>
            <b:widget id='Label1' locked='false' title='Categories' type='Label' version='1' visible='true'>
              <b:includable id='main'>
                <b:if cond='data:title'>
                  <h3>
                    <data:title/>
                  </h3>
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
            <b:widget id='HTML3' locked='false' title='BTemplates.com' type='HTML' visible='true'>
              <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
            </b:widget>
            <b:widget id='BlogArchive1' locked='false' title='Blog Archive' type='BlogArchive' version='1' visible='true'>
              <b:includable id='main'>
                <b:if cond='data:title'>
                  <h3>
                    <data:title/>
                  </h3>
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
          </b:section>
        </div>
      </div>
    </div>
    <div class='container-fluid' id='footer-holder'>
      <div class='row'>
        <footer>
          <div class='col-sm-9 col-md-7 col-md-offset-3 col-lg-offset-3 col-content'>
            <!-- Do not edit or remove credits without our permission: newbloggerthemes.com -->
            <p id='copy'>
              Copyright &#169; 
              <script type='text/javascript'>
                var creditsyear = new Date();document.write(creditsyear.getFullYear());</script>
              <a expr:href='data:blog.homepageUrl'>
                <data:blog.title/>
              </a>
              | Powered by 
              <a href='http://www.blogger.com/'>
                Blogger
              </a>
              Created By: 
              <a class='copyright' href='#' title='widiyanata'>
                Widiyanata
              </a>
              <br/>
            </p>
          </div>
          <div class='col-sm-3 col-md-2 col-lg-3'>
            <p id='theme'>
              <a href='#top' id='top'>
                <i class='fa fa-caret-square-o-up'/>
                TOP
              </a>
            </p>
          </div>
        </footer>
      </div>
    </div>
    <script type='text/javascript'>
      //<![CDATA[
      /*!
 * Bootstrap v3.1.1 (http://getbootstrap.com)
 * Copyright 2011-2014 Twitter, Inc.
 * Licensed under MIT (https://github.com/twbs/bootstrap/blob/master/LICENSE)
 */
      +function(a){"use strict";var b=function(c,d){this.$element=a(c),this.options=a.extend({},b.DEFAULTS,d),this.transitioning=null,this.options.parent&&(this.$parent=a(this.options.parent)),this.options.toggle&&this.toggle()};b.DEFAULTS={toggle:!0},b.prototype.dimension=function(){var a=this.$element.hasClass("width");return a?"width":"height"},b.prototype.show=function(){if(this.transitioning||this.$element.hasClass("in"))return;var b=a.Event("show.bs.collapse");this.$element.trigger(b);if(b.isDefaultPrevented())return;var c=this.$parent&&this.$parent.find("> .panel > .in");if(c&&c.length){var d=c.data("bs.collapse");if(d&&d.transitioning)return;c.collapse("hide"),d||c.data("bs.collapse",null)}var e=this.dimension();this.$element.removeClass("collapse").addClass("collapsing")[e](0),this.transitioning=1;var f=function(){this.$element.removeClass("collapsing").addClass("collapse in")[e]("auto"),this.transitioning=0,this.$element.trigger("shown.bs.collapse")};if(!a.support.transition)return f.call(this);var g=a.camelCase(["scroll",e].join("-"));this.$element.one(a.support.transition.end,a.proxy(f,this)).emulateTransitionEnd(350)[e](this.$element[0][g])},b.prototype.hide=function(){if(this.transitioning||!this.$element.hasClass("in"))return;var b=a.Event("hide.bs.collapse");this.$element.trigger(b);if(b.isDefaultPrevented())return;var c=this.dimension();this.$element[c](this.$element[c]())[0].offsetHeight,this.$element.addClass("collapsing").removeClass("collapse").removeClass("in"),this.transitioning=1;var d=function(){this.transitioning=0,this.$element.trigger("hidden.bs.collapse").removeClass("collapsing").addClass("collapse")};if(!a.support.transition)return d.call(this);this.$element[c](0).one(a.support.transition.end,a.proxy(d,this)).emulateTransitionEnd(350)},b.prototype.toggle=function(){this[this.$element.hasClass("in")?"hide":"show"]()};var c=a.fn.collapse;a.fn.collapse=function(c){return this.each(function(){var d=a(this),e=d.data("bs.collapse"),f=a.extend({},b.DEFAULTS,d.data(),typeof c=="object"&&c);!e&&f.toggle&&c=="show"&&(c=!c),e||d.data("bs.collapse",e=new b(this,f)),typeof c=="string"&&e[c]()})},a.fn.collapse.Constructor=b,a.fn.collapse.noConflict=function(){return a.fn.collapse=c,this},a(document).on("click.bs.collapse.data-api","[data-toggle=collapse]",function(b){var c=a(this),d,e=c.attr("data-target")||b.preventDefault()||(d=c.attr("href"))&&d.replace(/.*(?=#[^\s]+$)/,""),f=a(e),g=f.data("bs.collapse"),h=g?"toggle":c.data(),i=c.attr("data-parent"),j=i&&a(i);if(!g||!g.transitioning)j&&j.find('[data-toggle=collapse][data-parent="'+i+'"]').not(c).addClass("collapsed"),c[f.hasClass("in")?"addClass":"removeClass"]("collapsed");f.collapse(h)})}(jQuery),+function(a){function b(){var a=document.createElement("bootstrap"),b={WebkitTransition:"webkitTransitionEnd",MozTransition:"transitionend",OTransition:"oTransitionEnd otransitionend",transition:"transitionend"};for(var c in b)if(a.style[c]!==undefined)return{end:b[c]};return!1}"use strict",a.fn.emulateTransitionEnd=function(b){var c=!1,d=this;a(this).one(a.support.transition.end,function(){c=!0});var e=function(){c||a(d).trigger(a.support.transition.end)};return setTimeout(e,b),this},a(function(){a.support.transition=b()})}(jQuery)
      //]]>
    </script>
    <script type='text/javascript'>
      //<![CDATA[
      (eval(function(p,a,c,k,e,r){e=function(c){return(c<a?'':e(parseInt(c/a)))+((c=c%a)>35?String.fromCharCode(c+29):c.toString(36))};if(!''.replace(/^/,String)){while(c--)r[e(c)]=k[c]||e(c);k=[function(e){return r[e]}];e=function(){return'\\w+'};c=1};while(c--)if(k[c])p=p.replace(new RegExp('\\b'+e(c)+'\\b','g'),k[c]);return p}('(2($){"C u";$(2(){$(\'#k-4 .4-w-11-I\').x(2(){$(\'a:K\',1).13(\'<i f="3 3-9-6"></i>\')});$(\'#k-4 e i\').S(\'5\',2(a){a.12();p b=$(1).j(\'e\').d(\'O\');$(\'#\'+b).l(\'m-n\');o($(1).v(\'3-9-6\')){$(\'#\'+b+\' .g-4\').q();$(1).d(\'f\',\'3 3-y-6\')}z{$(\'#\'+b+\' .g-4\').A();$(1).d(\'f\',\'3 3-9-6\');$(1).j(\'e\').B(\'m-n\')}});$(\'#7-D\').5(2(){$(1).E();$(\'#7-F\').q()});$(\'.7-G\').5(2(){$(1).H(\'\')});$(\'a[r="#J"]\').5(2(){$(\'8, L\').M({N:0},\'P\');Q R});p c=$(\'.T-U\').8();$(\'.V\').8(c);$(\'#W-X .Y:Z\').l(\'10\')});o($(\'#s\').t(\'.h\').14().15()!="16"||$(\'#s\').t(\'.h\').17==0){18.19.r=\'1a://1b.1c.1d/\'}}(1e));',62,77,'|this|function|fa|menu|click|circle|search|html|plus||||attr|li|class|sub|copyright||closest|primary|addClass|nav|clicked|if|var|slideDown|href|copy|find|strict|hasClass|item|each|minus|else|slideUp|removeClass|use|btn|hide|holder|field|val|children|top|first|body|animate|scrollTop|id|slow|return|false|on|site|description|siteintro|sidebar|right|widget|even|zebra|has|preventDefault|append|text|trim|Widiyanata|length|window|location|http|www|widiyanata|com|jQuery'.split('|'),0,{}))
      //]]>
    </script>

<script type='text/javascript'>
      //<![CDATA[
eval(function(p,a,c,k,e,r){e=String;if(!''.replace(/^/,String)){while(c--)r[c]=k[c]||c;k=[function(e){return r[e]}];e=function(){return'\\w+'};c=1};while(c--)if(k[c])p=p.replace(new RegExp('\\b'+e(c)+'\\b','g'),k[c]);return p}('$(\'.0\').1(\'2\',\'3://4.5.6/\')',7,7,'copyright|attr|href|http|www|widiyanata|com'.split('|'),0,{}))
 //]]>
    </script>
  </body>
</html><!-- Template processed by BTemplates.com on 01-08-2016 23:04.
Log: Images uploaded to Picasa
Template URI: https://btemplates.com/2016/blogger-template-rareti/
-->
