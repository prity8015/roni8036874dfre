<!DOCTYPE html>

<!--[if IE 8]> <html lang="en" class="ie8 no-js"> <![endif]-->
<!--[if IE 9]> <html lang="en" class="ie9 no-js"> <![endif]-->
<!--[if !IE]><!-->
<html lang="en">
<!--<![endif]-->
<!-- BEGIN HEAD -->
<head>
 <meta charset="utf-8"/><title> ভূমি উন্নয়ন কর সিস্টেম অটোমেশন:
        LdtaxHoldings</title>
<meta http-equiv="X-UA-Compatible" content="IE=edge">

<meta content="width=600, initial-scale=1.0, minimum-scale=1.0, maximum-scale=3.0, user-scalable=no" name="viewport"/>

<meta content="" name="description"/>
<meta content="" name="author"/>
<!-- BEGIN GLOBAL MANDATORY STYLES -->
<link href="https://fonts.googleapis.com/css?family=Open+Sans:400,300,600,700&subset=all" rel="stylesheet" type="text/css"/>
<link href="https://ldtax.gov.bd/assets/global/plugins/font-awesome/css/font-awesome.min.css" rel="stylesheet" type="text/css"/>
<link href="https://ldtax.gov.bd/assets/global/plugins/simple-line-icons/simple-line-icons.min.css" rel="stylesheet" type="text/css"/>
<link href="https://ldtax.gov.bd/assets/global/plugins/bootstrap/css/bootstrap.min.css" rel="stylesheet" type="text/css"/>
<!-- remove checkbox add.ctp -->
<!-- <link href="https://ldtax.gov.bd/assets/global/plugins/uniform/css/uniform.default.css" rel="stylesheet" type="text/css"/> -->
<link href="https://ldtax.gov.bd/assets/global/plugins/bootstrap-switch/css/bootstrap-switch.min.css" rel="stylesheet" type="text/css"/>

<link href="https://ldtax.gov.bd/assets/global/css/components-rounded.css" id="style_components" rel="stylesheet" type="text/css"/>

<!-- remove checkbox add.ctp -->
<!-- <link href="https://ldtax.gov.bd/assets/global/css/plugins-md.css" rel="stylesheet" type="text/css"/> -->
<link href="https://ldtax.gov.bd/assets/admin/layout4/css/layout.css" rel="stylesheet" type="text/css"/>
<link href="https://ldtax.gov.bd/assets/admin/layout4/css/themes/light.css" rel="stylesheet" type="text/css" id="style_color"/>
<link href="https://ldtax.gov.bd/assets/admin/layout4/css/custom.css" rel="stylesheet" type="text/css"/>
<link href="https://ldtax.gov.bd/css/common.css" rel="stylesheet" type="text/css"/>
<link href="https://ldtax.gov.bd/css/custom.css" rel="stylesheet" type="text/css"/>

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/select2/4.0.5/css/select2.min.css">

            <link rel="shortcut icon" href="https://ldtax.gov.bd/img/favicon.ico"/>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/2.1.3/jquery.js"></script>
<style type="text/css">
    /* Chrome, Safari, Edge, Opera */
    input::-webkit-outer-spin-button,
    input::-webkit-inner-spin-button {
      -webkit-appearance: none;
      margin: 0;
    }

    /* Firefox */
    input[type=number] {
      -moz-appearance: textfield;
    }
    span.input-group-addon.addonExtra {
        background: #8dc642;
    }
</style>

<style>
        .loaderDiv{
          background: rgba(255,255,255,.95);
          width: 100%;
          height: 100%;
          z-index: 10000;
          position: fixed;
          top: 0;
          left: 0;
          display: none;
        }
        .loader {

          border: 5px solid #f3f3f3;
          border-radius: 50%;
          border-top: 5px solid blue;
          border-bottom: 5px solid green;
          -webkit-animation: spin 2s linear infinite;
          animation: spin 2s linear infinite;
          /*position: relative;*/
          display: none;
          left: 47%;
          top: 36%;
          height: 50px;
          width: 50px;

        }

        @-webkit-keyframes spin {
          0% { -webkit-transform: rotate(0deg); }
          100% { -webkit-transform: rotate(360deg); }
        }

        @keyframes spin {
          0% { transform: rotate(0deg); }
          100% { transform: rotate(360deg); }
        }
    </style>

</head>
<!-- END HEAD -->
<!-- BEGIN BODY -->
<!-- DOC: Apply "page-header-fixed-mobile" and "page-footer-fixed-mobile" class to body element to force fixed header or footer in mobile devices -->
<!-- DOC: Apply "page-sidebar-closed" class to the body and "page-sidebar-menu-closed" class to the sidebar menu element to hide the sidebar by default -->
<!-- DOC: Apply "page-sidebar-hide" class to the body to make the sidebar completely hidden on toggle -->
<!-- DOC: Apply "page-sidebar-closed-hide-logo" class to the body element to make the logo hidden on sidebar toggle -->
<!-- DOC: Apply "page-sidebar-hide" class to body element to completely hide the sidebar on sidebar toggle -->
<!-- DOC: Apply "page-sidebar-fixed" class to have fixed sidebar -->
<!-- DOC: Apply "page-footer-fixed" class to the body element to have fixed footer -->
<!-- DOC: Apply "page-sidebar-reversed" class to put the sidebar on the right side -->
<!-- DOC: Apply "page-full-width" class to the body element to have full width page without the sidebar menu -->
<body class="page-md page-sidebar-page-sidebar-closed-hide-logo page-header-fixed page-footer-fixed">
  <div class="loaderDiv">
    <div class="loader" style="align-content: center; width:300px; height: 300px; top: 0;"></div>
    <div style="color:green; font-weight: bold; font-size:24px; text-align: center; position: fixed; width:100%; top: 18%;" class="loadMsg">লোড হচ্ছে। <br>অনুগ্রহ করে <span style="color: red;">অপেক্ষা</span> করুন।</div>
  </div>
    
<div class="page-header md-shadow-z-1-i navbar navbar-fixed-top">
    <!-- BEGIN HEADER INNER -->
    <div class="page-header-inner">
        <!-- BEGIN LOGO -->
        <div class="page-logo">
            <!-- <a href=""> -->
                
            <a href="https://office.land.gov.bd/"> 
                <img src="https://ldtax.gov.bd/assets/admin/layout4/img/logo-light.png" alt="logo" class="logo-default"/>
            </a>
                    </div>

        <a href="javascript:;" class="menu-toggler responsive-toggler" data-toggle="collapse" data-target=".navbar-collapse">
        </a>


        <div class="page-top">

            <div class="top-menu">
                <ul class="nav navbar-nav pull-right">

                    <li class="separator hide">
                    </li>
                    <li><br>

                    </li>

                    <li class="separator hide">
                    </li>

                                        <img src="https://ldtax.gov.bd/assets/admin/layout4/img/nagorik.png" />
                         
                    <!-- END USER LOGIN DROPDOWN -->
                </ul>
            </div>
            <!-- END TOP NAVIGATION MENU -->
        </div>
        <!-- END PAGE TOP -->
    </div>
    <!-- END HEADER INNER -->
</div>
<!-- END HEADER-->

<!-- <div>You will be auto logged out in <span id="timeOut"></span> seconds.</div> -->
<div class="clearfix">
</div>
    <!-- BEGIN CONTAINER -->


        <div class="page-container">
        <!-- BEGIN SIDEBAR -->
            <!-- END SIDEBAR -->


        <div class="page-content-wrapper">
                            <div class="">
                                                                   <!-- end -->

<div class="row">
    <div class="col-md-12">
        <div class="portlet box blue">
            <div class="portlet-title">
                <div class="caption">
                    <i class="fa fa-globe"></i>ভূমি উন্নয়ন কর পরিশোধ রসিদ                </div>
                <div class="tools">
                    <a href="javascript:;" class="collapse">
                    </a>
                    <a href="#portlet-config" data-toggle="modal" class="config">
                    </a>
                    <a href="javascript:;" class="reload">
                    </a>
                    <a href="javascript:;" class="remove">
                    </a>
                </div>
            </div>

            <div class="portlet-body">
                <div id="printArea" style="width: 815px; margin: 0 auto;">
                <div class="col-md-12">
                    <style type="text/css">
                        body{
                            font-family: "kalpurush",Arial,sans-serif;
                            font-size: 13px !important;
                            line-height: 1.2;
                            color: #333;
                            background-color: #fff;
                        }
                        .dotted_botton{
                            border:none;
                            border-bottom:1px dotted #000;
                            background-color:#fff;
                        }
                        .border_none{
                            border-top: none !important;
                        }
                        .table-bordered {
                            border: 1px solid #ddd;
                        }
                        .qrcode-print{
                           width:100%;
                           display: list-item;
                           list-style-image: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAFIAAABSAQMAAAD94hHYAAAABlBMVEX///8AAABVwtN+AAAACXBIWXMAAA7EAAAOxAGVKw4bAAABIUlEQVQokZXSMaoFMQgFUMFWyFaEtEK2LqQV3IqQNuDPvOExk7zqWwynMM4tLsA/p6T6nJVy7iawzgWn0uH15SbsdtpdueuvO0ow/RhcasG47z8uaZ+58zwGwFgP5536cZlZE3xU3o2K1pKtxm4aA6T7nfnlMpAsZTbeTaOXYMR7/zE6dJFKEIezz+E9r3RvF5CYXW3Q4RypnJq2GwbQCk0ch31QQ6oyd2MvBg5DaDfEdOHsPg9LM81x33wZMeZYyZvsLoZrjSRoN2h4Vb9vvkzBRsLAfBjUpMNwOUzXTeVJh+e1sk7q7pWCyuoqwe7VmQgyum6+vf6FmmBEh6crsGfGj7m16J+3m62x91Wcw6vDUah9+/x1SccWTT8dePmf8wd0mmb8PyrBzAAAAABJRU5ErkJggg==);
                           list-style-position: inside;
                           background-repeat: no-repeat;
                        }
                        .b1 {border: 1px dotted; padding: 2px;}
                    </style>
                    <style type="text/css" media="print">
                        @page {
                            size:  a4;   /* auto is the initial value */
                            margin: 0mm;  /* this affects the margin in the printer settings */
                        }
                        html{
                            background-color: #FFFFFF; 
                            margin: 0px;  /* this affects the margin on the html before sending to printer */
                        }
                        body{
                            border: solid 0px blue ;
                            margin: 0mm; /* margin you want for the content */
                        }
                    </style>

                    <div style="font-family:'kalpurush',Arial,sans-serif; font-size:14px !important; line-height:1.2;color: #333; background-color: #fff; width: 7.9in; border-radius: 10px; border: dotted 1px; padding: 10px; float: left; margin: 30px auto;">
                        <div class="row">
                            <div class="col-md-12">
                                <div style="">
                                    <table style="width: 100%;">
                                        <tr>
                                            <td class="text-left">বাংলাদেশ ফরম নং ১০৭৭</td>
                                            <td class="text-right">(পরিশিষ্ট: ৩৮)</td>
                                        </tr>
                                        <tr>
                                            <td class="text-left">(সংশোধিত)</td>
                                            <td class="text-right input_bangla">ক্রমিক নং 728323012185</td>
                                        </tr>
                                        <tr>
                                            <td class="text-center" colspan="2">
                                                ভূমি উন্নয়ন কর পরিশোধ রসিদ                                            </td>
                                        </tr>
                                        <tr>
                                            <td class="text-center" colspan="2">
                                                (অনুচ্ছেদ ৩৯২ দ্রষ্টব্য)                                            </td>
                                        </tr>
                                    </table>
                                    <div style="width: 100%; height: 20px;"></div>
                                    <table style="width:100%;">
                                        <tr>
                                            <td style="width: 320px;">সিটি কর্পোরেশন /পৌর /ইউনিয়ন ভূমি অফিসের নাম  :</td>
                                            <td class="dotted_botton"> ইউনিয়ন ভূমি অফিস</td>
                                        </tr>
                                    </table>
                                    <table style="margin-top:5px; width:100%;">
                                        <tr>
                                            <td style="width: 130px;">মৌজার ও জে. এল. নং:</td>
                                            <td class="dotted_botton input_bangla" style="padding: 0 10px 0 5px;">আগিয়া - 21</td>
                                            <td style="width: 105px">উপজেলা / থানা  :</td>
                                            <td class="dotted_botton" style="padding: 0 10px 0 5px;">আগিয়া</td>
                                            <td style="width: 40px">জেলা:</td>
                                            <td class="dotted_botton" style="padding: 0 10px 0 5px;">নেত্রকোনা</td>
                                        </tr>
                                    </table>
                                    
                                    <table style="margin-top:5px; width:100%;">
                                        <tr>
                                            <td style="width: 90px">মালিকের নাম :</td>
                                            <td class="dotted_botton" style="padding-left: 10px;">
                                                রাজন চন্দ্র সরকার                                            </td>
                                        </tr>
                                    </table>

                                    <table style="margin-top:5px; width:100%;">
                                        <tr>
                                            <td style="width: 225px"><!-- ২ নং রেজিস্টার অনুযায়ী হোল্ডিং নম্বার -->
                                            ২ নং রেজিস্টার অনুযায়ী হোল্ডিং নম্বর:</td>
                                            <td class="dotted_botton numeric_bangla" style="padding-left: 10px;">
                                                1387                                            </td>
                                        </tr>
                                    </table>

                                    <table style="margin-top:5px; width:100%;">
                                        <tr>
                                            <td style="width: 75px">খতিয়ান নং:</td>
                                            <td class="dotted_botton numeric_bangla" style="padding-left: 10px;">
                                                1417                                            </td>
                                        </tr>
                                    </table>
                                    <div style="height: 10px"></div>
                                </div>
                                                <table class="b1" style="border-collapse: collapse; margin:10px 2px ; width: 99%; font-size: 9px; float: left;">
                                    <thead>
                                        <tr>
                                            <th class="b1">ক্রমঃ</th>
                                            <!-- <th class="b1">খতিয়ান নং</th> -->
                                            <th class="b1">দাগ নং</th>
                                            <th class="b1">জমির শ্রেণী</th>
                                            <th class="b1">জমির পরিমাণ (শতক)</th>
                                        </tr>
                                    </thead>
                                    <tbody style="height: 126px;">
                                                                        <tr>
                                            <td class="b1 input_bangla">1</td>
                                            <!-- <td class="b1 input_bangla">1417</td> -->
                                            <td class="b1 input_bangla">513</td>
                                            <td class="b1">
                                                কান্দা(                                                কৃষি)                                            </td>
                                            <td class="b1 input_bangla">32.00000</td>
                                        </tr>
                                                                        <tr>
                                            <td class="b1 input_bangla">2</td>
                                            <!-- <td class="b1 input_bangla">1417</td> -->
                                            <td class="b1 input_bangla">519</td>
                                            <td class="b1">
                                                ভিটা(                                                আবাসিক)                                            </td>
                                            <td class="b1 input_bangla">9.00000</td>
                                        </tr>
                                                                        <tr>
                                            <td class="b1 input_bangla">3</td>
                                            <!-- <td class="b1 input_bangla">1417</td> -->
                                            <td class="b1 input_bangla">523</td>
                                            <td class="b1">
                                                ভিটা(                                                আবাসিক)                                            </td>
                                            <td class="b1 input_bangla">9.00000</td>
                                        </tr>
                                                                        <tr>
                                            <td class="b1 input_bangla">4</td>
                                            <!-- <td class="b1 input_bangla">1417</td> -->
                                            <td class="b1 input_bangla">453</td>
                                            <td class="b1">
                                                কান্দা(                                                কৃষি)                                            </td>
                                            <td class="b1 input_bangla">26.00000</td>
                                        </tr>
                                                                        <tr>
                                            <td class="b1 input_bangla">5</td>
                                            <!-- <td class="b1 input_bangla">1417</td> -->
                                            <td class="b1 input_bangla">500</td>
                                            <td class="b1">
                                                কান্দা(                                                কৃষি)                                            </td>
                                            <td class="b1 input_bangla">48.00000</td>
                                        </tr>
                                                                        <tr>
                                            <td class="b1 input_bangla">6</td>
                                            <!-- <td class="b1 input_bangla">1417</td> -->
                                            <td class="b1 input_bangla">513</td>
                                            <td class="b1">
                                                কান্দা(                                                কৃষি)                                            </td>
                                            <td class="b1 input_bangla">8.00000</td>
                                        </tr>
                                                                        <tr>
                                            <td class="b1 input_bangla">7</td>
                                            <!-- <td class="b1 input_bangla">1417</td> -->
                                            <td class="b1 input_bangla">449</td>
                                            <td class="b1">
                                                কান্দা(                                                কৃষি)                                            </td>
                                            <td class="b1 input_bangla">40.00000</td>
                                        </tr>
                                                                    </tbody>
                                </table>
                            </div>
                        </div>     
                                   
                        
                        <table style="width: 100%;">
                            <tr>
                                <td class="b1 text-center" style="width: 50%;">সর্বমোট জমি (শতক)</td>
                                <td class="b1 input_bangla" style="width: 50%;">172</td>
                            </tr>
                        </table>
                        <table class="table table-striped table-bordered table-hover" style="width:100% !important;">
                            <tr>
                                <th style="text-align: center;" colspan="8">আদায়ের বিবরণ </th>
                            </tr>

                            <tr>
                                <th style="text-align: center;" >তিন বৎসরের ঊর্ধ্বের বকেয়া</th>
                                <th style="text-align: center;">গত তিন বৎসরের বকেয়া
                                </th>
                                <th style="text-align: center;">বকেয়ার সুদ ও ক্ষতিপূরণ
                                </th>
                                <th style="text-align: center;" >হাল দাবি
                                </th>
                                <th style="text-align: center;" >মোট দাবি</th>
                                <th style="text-align: center;" >মোট আদায়
                                </th>
                                <th style="text-align: center;" >মোট বকেয়া</th>
                                <th style="text-align: center;" >মন্তব্য</th>
                            </tr>

                            <tr>
                                <td align="center">০</td>
                                <td align="center">০</td>
                                <td align="center">০</td>
                                <td align="center">৪৮৮</td>
                                <td align="center">
                                    ৪৮৮</td>

                                <td align="center">৪৮৮</td>
                                <td align="center">
                                    ০                                </td>
                                <td align="center"></td>
                            </tr>
                        </table>
                        <div style="width:100% !important;">
                            <p class="dotted_botton"> সর্বমোট (কথায়):
                                                                চার শত আটাশি টাকা মাত্র ।
                            </p>
                        </div>
                        <div class="row" style="width:100% !important; justify-content: center;">
                            <div class="col-md-12">
                                <div style="width: 290px; float: left;" align="left">
                                    <p style="margin: 0 !important;"><p style="margin: 0 !important;">নোট: সর্বশেষ কর পরিশোধের সাল - ১৪৩০</p></p>
                                    <p class="input_bangla"> চালান নং : 2324-0003074875</p>
                                    <p>
                                        তারিখ : <div style="margin-top: -37px;margin-left: 10px;"><p style="width: 115px;padding: 0;margin: 0;margin-left: 38px;margin-bottom: 2px;">৯ শ্রাবণ ১৪৩০</p><span style="border-top:1px solid; margin-left:36px;">২৪ জুলাই, ২০২৩</span></p></div>
                                    </p>
                                </div>
                                <div style="width: 125px; float: left;" align="center">
                                    <!-- <img style="-webkit-print-color-adjust: exact; max-width: 100%; height: auto; " src="https://ldtax.gev.ba/img/qrimg/5213296.png" width="100" height="100"> -->
                                    <div class="qrcode-print"></div>
                                </div>
                                <div style="width: 265px; float: right; text-align: right;font-size: 12px;font-family: 'kalpurush',Arial,sans-serif;" >
                                                                            <p class="text-center" style="padding: 5px; ">এই দাখিলা ইলেক্ট্রনিকভাবে তৈরি করা হয়েছে, <br> কোন স্বাক্ষর প্রয়োজন নেই।</p>
                                                                    </div>
                            </div>   
                        </div>   
                        
                        <div class="row">
                            <div class="col-md-12 text-right">
                                <div style="width: 100%; border-top: 1px dotted gray; margin-top:15px;"></div>
                                <div class="from-controll">1/1</div>
                            </div>
                        </div>                 
                    </div>
                </div>
                </div>
                <!-- // -->
                <div class="row">
                    <div class="col-md-12">
                        <div style="text-align: center !important; display: block !important;">
                            <input style="margin-top: 10px; padding: 10px;" id="print" class="btn btn-md blue" type="button" onclick="printDiv('printArea')" value="প্রিন্ট" />
                            <!-- <a class="btn btn-md btn-success" href="https://ldtax.gov.bd/ldtax-holdings/individual-rashid-print-offline-previe/GVHZhamp4VG92UT09" target="_blank" style="margin-top: 10px;padding:10px;">PDF</a> -->
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>

<script type="text/javascript">
    function printDiv(divName) {
        var printContents = document.getElementById(divName).innerHTML;
        var originalContents = document.body.innerHTML;

        document.body.innerHTML = printContents;
        setTimeout(function() {}, 500);
        window.print();

        document.body.innerHTML = originalContents;
    }
</script>

                    </div>
		</div>

        </div>
        <style>
    .title{
        font-size: 15px;
        color: #592e80;
        text-align: center;
        font-weight: 600;
        padding-bottom: 7px;
    }

</style>

<div class="page-footer">
	<div class="page-footer-inner">
            <a href="http://www.bangladesh.gov.bd/" target="_blank">
	<img src="https://ldtax.gov.bd/assets/admin/layout4/img/bd.png" alt=""/>
	</a> <span class="title">ভূমি সংস্কার বোর্ড, ভূমি  মন্ত্রণালয়, গণপ্রজাতন্ত্রী বাংলাদেশ সরকার</span>
<!--   <a href="http://www.a2i.pmo.gov.bd/" target="_blank">
	<img src="https://ldtax.gov.bd/assets/admin/layout4/img/a2i.png" alt=""/>
            </a> -->
        &nbsp;&nbsp;
	</div>
    <div class="page-footer-inner pull-right">
        <span class="title">কারিগরি সহায়তায়</span>
        <a href="http://mysoftheaven.com/" target="_blank">
	        <img src="https://ldtax.gov.bd/img/auto.png" alt="" style="width: 140px;"/>
	    </a>
        &nbsp;&nbsp;
	</div>
</div>

<!--<div id="lang-vis-control" style="width:50%;float:right;text-align: right;">
	<h6>  </h6>
	</div>
	<div class="scroll-to-top">
		<i class="icon-arrow-up"></i>
	</div>
</div>-->

    <!-- END FOOTER -->
<!-- BEGIN JAVASCRIPTS(Load javascripts at bottom, this will reduce page load time) -->
<!-- BEGIN CORE PLUGINS -->
<!--[if lt IE 9]>
<script src="https://ldtax.gov.bd/assets/global/plugins/respond.min.js"></script>
<script src="https://ldtax.gov.bd/assets/global/plugins/excanvas.min.js"></script>
<![endif]-->
<script src="https://ldtax.gov.bd/assets/global/plugins/jquery.min.js" type="text/javascript"></script>
<script src="https://ldtax.gov.bd/assets/global/plugins/jquery-migrate.min.js" type="text/javascript"></script>
<!-- IMPORTANT! Load jquery-ui.min.js before bootstrap.min.js to fix bootstrap tooltip conflict with jquery ui tooltip -->
<script src="https://ldtax.gov.bd/assets/global/plugins/jquery-ui/jquery-ui.min.js" type="text/javascript"></script>
<script src="https://ldtax.gov.bd/assets/global/plugins/bootstrap/js/bootstrap.min.js" type="text/javascript"></script>
<script src="https://ldtax.gov.bd/assets/global/plugins/bootstrap-hover-dropdown/bootstrap-hover-dropdown.min.js" type="text/javascript"></script>
<script src="https://ldtax.gov.bd/assets/global/plugins/jquery-slimscroll/jquery.slimscroll.min.js" type="text/javascript"></script>
<script src="https://ldtax.gov.bd/assets/global/plugins/jquery.blockui.min.js" type="text/javascript"></script>
<script src="https://ldtax.gov.bd/assets/global/plugins/jquery.cokie.min.js" type="text/javascript"></script>
<script src="https://ldtax.gov.bd/assets/global/plugins/uniform/jquery.uniform.min.js" type="text/javascript"></script>
<script src="https://ldtax.gov.bd/assets/global/plugins/bootstrap-switch/js/bootstrap-switch.min.js" type="text/javascript"></script>
<!-- END CORE PLUGINS -->
<!-- Latest compiled JavaScript -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/select2/4.0.5/js/select2.min.js"></script>


<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery-validate/1.19.3/jquery.validate.js"></script>


<!-- END PAGE LEVEL PLUGINS -->
<!-- BEGIN PAGE LEVEL SCRIPTS -->
<script src="https://ldtax.gov.bd/assets/global/plugins/jquery-notific8/jquery.notific8.min.js"></script>
<script src="https://ldtax.gov.bd/assets/global/plugins/bootstrap-toastr/toastr.min.js"></script>
<script src="https://ldtax.gov.bd/assets/global/scripts/metronic.js" type="text/javascript"></script>
<script src="https://ldtax.gov.bd/assets/admin/layout4/scripts/layout.js" type="text/javascript"></script>
<script src="https://ldtax.gov.bd/assets/admin/layout4/scripts/demo.js" type="text/javascript"></script>
<script src="https://ldtax.gov.bd/js/style.js?v=2023092114"></script>
<!--<script src="https://ldtax.gov.bd/assets/admin/pages/scripts/charts-amcharts.js"></script>-->
<script src="https://cdnjs.cloudflare.com/ajax/libs/jQuery-slimScroll/1.3.8/jquery.slimscroll.min.js" integrity="sha512-cJMgI2OtiquRH4L9u+WQW+mz828vmdp9ljOcm/vKTQ7+ydQUktrPVewlykMgozPP+NUBbHdeifE6iJ6UVjNw5Q==" crossorigin="anonymous"></script>

<script src="/js/jquery.form.min.js"></script><script src="/js/jquery.jqprint-0.3.js"></script><script src="/js/application_receipt.js"></script><script src="https://ldtax.gov.bd/js/tinymce/js/tinymce/tinymce.min.js"></script>
<script>
        // New script for session
        var IdealTimeOut = 180*60; //30 minute
        var idleSecondsTimer = null;
        var idleSecondsCounter = 0;
        document.onclick = function () { idleSecondsCounter = 0; };
        document.onmousemove = function () { idleSecondsCounter = 0; };
        document.onkeypress = function () { idleSecondsCounter = 0; };
        idleSecondsTimer = window.setInterval(CheckIdleTime, 1000);

        function CheckIdleTime() {
            idleSecondsCounter++;
            var oPanel = document.getElementById("timeOut");
            if (oPanel) {
                oPanel.innerHTML = (IdealTimeOut - idleSecondsCounter);
            }
            if (idleSecondsCounter >= IdealTimeOut) {
                window.clearInterval(idleSecondsTimer);
                alert("Your Session has expired. Please login again.");
                window.location = "http://lims.land.gov.bd/limslrb/ldtax/dashboard/logout";
            }

        }

jQuery(document).ready(function() {

    $('#demandType, #chnageOwner,#demand-type').change(function(){
        var item=$(this).val();
        if(item==0){
            $('.ownerPlaceholder').attr('placeholder','পিতার নাম/ স্বামীর নাম');
            $('#ownerText').html('পিতার নাম/ স্বামীর নাম');
        }
        else{
           $('.ownerPlaceholder').attr('placeholder','সংস্থা  নাম');
           $('#ownerText').html('সংস্থা  নাম');
        }
    })

    $('textarea').removeClass('input_bangla');

    $('.page-sidebar-menu').slimscroll({
          height : '450px'
    });


    $(':input[type=file]').on('change', function(){ //on file input change

        if (window.File && window.FileReader && window.FileList && window.Blob) //check File API supported browser
        {
            $('#thumb-output').html(''); //clear html of output element
                var data = $(this)[0].files; //this file data

                $.each(data, function(index, file){ //loop though each file
                    if(/(\.|\/)(gif|jpe?g|png)$/i.test(file.type)){ //check supported file type
                        var fRead = new FileReader(); //new filereader
                        fRead.onload = (function(file){ //trigger function on successful read
                        return function(e) {
                            var img = $('<img/>').addClass('thumb').attr('src', e.target.result); //create image element
                            $('#thumb-output').append(img); //append image to output element
                        };
                        })(file);
                        fRead.readAsDataURL(file); //URL representing the file's data.
                    }
                });
        }else{
            alert("Your browser doesn't support File API!"); //if File API is absent
        }
    });

    // $("#chnageOwner,#mouja_id,#ldtax_holdings_tax_clear_year,#ldtax-holding-land-schedules-1-land-type,#ldtax-holding-land-schedules-1-ldtax-holding-usable-informations-1-land-type,#ldtax-holding-land-schedules-1-ldtax-holding-usable-informations-1-start-year,#ldtax-holding-land-schedules-1-ldtax-holding-usable-informations-1-end-year").select2();

    $('#demand_type,#tax_clear_year,#khatian_survey_id,#block,#sectorSection,#housingName').select2({ width: '100%' });
    //$('#tax_clear_year').select2();

    // validate mobile number

    $('#ldtax-holding-owners-1-land-portion,#amount_of_land').bind('keydown', function(e){

        var num = this.value;
        if(num.indexOf(".")>=0){
            if(e.key == '।' || e.key == '.'){
            $(this).val('');
            e.preventDefault();
            }
            if(e.key!= 0 && e.key != 1 && e.key!= 2 && e.key!= 3 && e.key!= 4 && e.key!= 5 && e.key!= 6 && e.key!= 7 && e.key!= 8 && e.key!= 9 && e.key!= '০' && e.key != '১' && e.key!= '২' && e.key!= '৩' && e.key!= '৪' && e.key!= '৫' && e.key!= '৬' && e.key!= '৭' && e.key!= '৮' && e.key!= '৯' && e.keyCode!= 8 && e.keyCode!= 9 && e.keyCode!= 16 && e.keyCode!= 37 && e.keyCode!= 38 && e.keyCode!= 39 && e.keyCode!= 40){
                e.preventDefault();
            }
        }else{
            if(e.key == '।'){
                num +='।';
                var res = num.replace("।",".");
                $(this).val(res);
                e.preventDefault();
            }

            if(e.keyCode== 32){
                e.preventDefault();
            }

            if(e.key!= 0 && e.key != 1 && e.key!= 2 && e.key!= 3 && e.key!= 4 && e.key!= 5 && e.key!= 6 && e.key!= 7 && e.key!= 8 && e.key!= 9 && e.key!= '০' && e.key != '১' && e.key!= '২' && e.key!= '৩' && e.key!= '৪' && e.key!= '৫' && e.key!= '৬' && e.key!= '৭' && e.key!= '৮' && e.key!= '৯' && e.key!= '.' && e.keyCode!= 8 && e.keyCode!= 9 && e.keyCode!= 16 && e.keyCode!= 37 && e.keyCode!= 38 && e.keyCode!= 39 && e.keyCode!= 40){
                e.preventDefault();
            }
        }

    });

    $(document).on('focus', '.select2.select2-container', function (e) {

      var isOriginalEvent = e.originalEvent // don't re-open on closing focus event
      var isSingleSelect = $(this).find(".select2-selection--single").length > 0 // multi-select will pass focus to input

      if (isOriginalEvent && isSingleSelect) {
        $(this).siblings('select:enabled').select2('open');
        // $('input[type=search]').addClass('input_bangla');
      }
    });

    $(document).on('keyup', '.select2-search__field', function (e) {
        var input = $(this).val();
        console.log(input);
        var numbers =  { 0: '০',1: '১',2: '২',3: '৩',4: '৪',5: '৫',6: '৬',7: '৭',8: '৮',9: '৯'};
        var output = [];
        for (var i = 0; i < input.length; ++i) {
            if (numbers.hasOwnProperty(input[i])) {
                output.push(numbers[input[i]]);
            } else {
                output.push(input[i]);
            }
        }
        $(this).val(output.join('')).trigger('input');
    });


    // initiate layout and plugins
    Metronic.init(); // init metronic core components
    Layout.init(); // init current layout
    Demo.init(); // init demo features
    //ChartsAmcharts.init();

});

const convertBanglaToEnglishNumber=(str)=>{
        let banglaNumber=
            {'০': 0,
            '১': 1,
            '২': 2,
            '৩': 3,
            '৪': 4,
            '৫': 5,
            '৬': 6,
            '৭': 7,
            '৮': 8,
            '৯': 9}
        for (var x in banglaNumber) {
            str = str.toString().replace(new RegExp(x, 'g'), banglaNumber[x]);
        }
        return str;
    }

    $('.land_portion').on('keyup',function(){
        var land_portion = parseFloat(0);

        $(".land_portion").each(function() {
            if($(this).val().length<1){
                var value =  0;
            }else{
                var value =  $(this).val();
            }
            land_portion += parseFloat(convertBanglaToEnglishNumber(value));
        });

        if(land_portion.toFixed(6) > 1){
            $(this).val(0);
        }
    });

    $("#chnageOwner,#mouja_id,#ldtax_holdings_tax_clear_year,#ldtax-holding-land-schedules-1-land-type,#ldtax-holding-land-schedules-1-ldtax-holding-usable-informations-1-land-type,#ldtax-holding-land-schedules-1-ldtax-holding-usable-informations-1-start-year,#ldtax-holding-land-schedules-1-ldtax-holding-usable-informations-1-end-year").addClass('select2');

    $('.select2').select2({});



</script>

<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-MGR6JSR2BN"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-MGR6JSR2BN');
</script>

<script type="text/javascript">


       jQuery('#housingName').change(function () {
            jQuery('.sectorSection').html('<img src="' + webPath + 'assets/global/img/loading-spinner-blue.gif' + '">');
            jQuery.get(webPath + 'LdTaxholdingReports/getSector/' + jQuery('#housingName').val(), function (data) {
                jQuery('.sectorSection').html(data);
            });
            jQuery('.block').html('<img src="' + webPath + 'assets/global/img/loading-spinner-blue.gif' + '">');
            jQuery.get(webPath + 'LdTaxholdingReports/getBlock/' + jQuery('#housingName').val(), function (data) {
                jQuery('.block').html(data);
            });
        });

</script>

<!-- Global site tag (gtag.js) - Google Analytics -->
<!-- <script async src="https://www.googletagmanager.com/gtag/js?id=G-T53D39JLTB"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-T53D39JLTB');
</script> -->
<!-- <script type="text/javascript">
    function deleteAllCookies() {
        var cookies = document.cookie.split(";");

        for (var i = 0; i < cookies.length; i++) {
            var cookie = cookies[i];
            var eqPos = cookie.indexOf("=");
            var name = eqPos > -1 ? cookie.substr(0, eqPos) : cookie;
            document.cookie = name + "=;expires=Thu, 01 Jan 1970 00:00:00 GMT";
        }
    }

deleteAllCookies();
</script> -->

    <!-- <script src="http://devlims.land.gov.bd/limslrb/ldtax/js/style.js"></script> -->
</body>
</html>
