# CameraCalibrationGuide

---
## Camera Calibration Tools

### MRT Camera Calibration Toolbox [OpenCV, Python]
https://github.com/MT-MRT/MRT-Camera-Calibration-Toolbox

<img src="https://github.com/MT-MRT/MRT-Camera-Calibration-Toolbox/blob/master/docs/example_single_chessboard.gif" width="450" />

### Camera Calibration Using OpenCV and Python [OpenCV, Python]
https://nikatsanka.github.io/camera-calibration-using-opencv-and-python.html

### Projet+calibration-Paul.ipynb
https://mecaruco2.readthedocs.io/en/latest/notebooks_rst/Aruco/Projet+calibration-Paul.html

### Camera Calibration with GUI [OpenCV, Cpp]
https://github.com/erickTornero/Camera-Calibration

<img src="https://github.com/erickTornero/Camera-Calibration/blob/master/sample_calibration.gif" width="450" />

### BoofCV Computer Vision [Android, Java]
Camera Calibration (chessboard, circles, squares), desktop applications with Java.
https://boofcv.org/index.php?title=Applications#Camera_Calibration

---
## Calibration Pattern Generator

### OpenCVMarkerPrinter [OpenCV, Python]
https://github.com/opencv/opencv_contrib/tree/master/modules/aruco/misc/pattern_generator

### Pattern Generator from calib.io
Customize a pattern (ChArUco, Checkerboard, Circles, Asymetric Circles) to match your application perfectly and download a printable PDF file.
https://calib.io/pages/camera-calibration-pattern-generator

### Camera Calibration Pattern Generator [Python]
Checkerboard generator for camera calibration and saving to pdf.
https://github.com/ProximaB/Camera-Calibration-Pattern-Generator

### opencv_contrib/modules/aruco/samples/ [OpenCV, Cpp]
https://github.com/opencv/opencv_contrib/tree/master/modules/aruco/samples

---
End



<!DOCTYPE html>
<!-- saved from url=(0059)http://amroamroamro.github.io/mexopencv/opencv_contrib.html -->
<html lang="en"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
  
  <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
  <meta name="description" content="mexopencv examples and demos">
  <title>mexopencv Examples</title>
  <link rel="icon" href="http://amroamroamro.github.io/mexopencv/favicon.ico">
  <!-- CSS -->
  <link rel="stylesheet" href="./mexopencv Examples_files/bootstrap.min.css">
  <link rel="stylesheet" href="./mexopencv Examples_files/font-awesome.min.css">
  <link rel="stylesheet" href="./mexopencv Examples_files/style.min.css">
<style type="text/css">.MathJax_Hover_Frame {border-radius: .25em; -webkit-border-radius: .25em; -moz-border-radius: .25em; -khtml-border-radius: .25em; box-shadow: 0px 0px 15px #83A; -webkit-box-shadow: 0px 0px 15px #83A; -moz-box-shadow: 0px 0px 15px #83A; -khtml-box-shadow: 0px 0px 15px #83A; border: 1px solid #A6D ! important; display: inline-block; position: absolute}
.MathJax_Menu_Button .MathJax_Hover_Arrow {position: absolute; cursor: pointer; display: inline-block; border: 2px solid #AAA; border-radius: 4px; -webkit-border-radius: 4px; -moz-border-radius: 4px; -khtml-border-radius: 4px; font-family: 'Courier New',Courier; font-size: 9px; color: #F0F0F0}
.MathJax_Menu_Button .MathJax_Hover_Arrow span {display: block; background-color: #AAA; border: 1px solid; border-radius: 3px; line-height: 0; padding: 4px}
.MathJax_Hover_Arrow:hover {color: white!important; border: 2px solid #CCC!important}
.MathJax_Hover_Arrow:hover span {background-color: #CCC!important}
</style><style type="text/css">#MathJax_About {position: fixed; left: 50%; width: auto; text-align: center; border: 3px outset; padding: 1em 2em; background-color: #DDDDDD; color: black; cursor: default; font-family: message-box; font-size: 120%; font-style: normal; text-indent: 0; text-transform: none; line-height: normal; letter-spacing: normal; word-spacing: normal; word-wrap: normal; white-space: nowrap; float: none; z-index: 201; border-radius: 15px; -webkit-border-radius: 15px; -moz-border-radius: 15px; -khtml-border-radius: 15px; box-shadow: 0px 10px 20px #808080; -webkit-box-shadow: 0px 10px 20px #808080; -moz-box-shadow: 0px 10px 20px #808080; -khtml-box-shadow: 0px 10px 20px #808080; filter: progid:DXImageTransform.Microsoft.dropshadow(OffX=2, OffY=2, Color='gray', Positive='true')}
#MathJax_About.MathJax_MousePost {outline: none}
.MathJax_Menu {position: absolute; background-color: white; color: black; width: auto; padding: 2px; border: 1px solid #CCCCCC; margin: 0; cursor: default; font: menu; text-align: left; text-indent: 0; text-transform: none; line-height: normal; letter-spacing: normal; word-spacing: normal; word-wrap: normal; white-space: nowrap; float: none; z-index: 201; box-shadow: 0px 10px 20px #808080; -webkit-box-shadow: 0px 10px 20px #808080; -moz-box-shadow: 0px 10px 20px #808080; -khtml-box-shadow: 0px 10px 20px #808080; filter: progid:DXImageTransform.Microsoft.dropshadow(OffX=2, OffY=2, Color='gray', Positive='true')}
.MathJax_MenuItem {padding: 2px 2em; background: transparent}
.MathJax_MenuArrow {position: absolute; right: .5em; padding-top: .25em; color: #666666; font-size: .75em}
.MathJax_MenuActive .MathJax_MenuArrow {color: white}
.MathJax_MenuArrow.RTL {left: .5em; right: auto}
.MathJax_MenuCheck {position: absolute; left: .7em}
.MathJax_MenuCheck.RTL {right: .7em; left: auto}
.MathJax_MenuRadioCheck {position: absolute; left: 1em}
.MathJax_MenuRadioCheck.RTL {right: 1em; left: auto}
.MathJax_MenuLabel {padding: 2px 2em 4px 1.33em; font-style: italic}
.MathJax_MenuRule {border-top: 1px solid #CCCCCC; margin: 4px 1px 0px}
.MathJax_MenuDisabled {color: GrayText}
.MathJax_MenuActive {background-color: Highlight; color: HighlightText}
.MathJax_MenuDisabled:focus, .MathJax_MenuLabel:focus {background-color: #E8E8E8}
.MathJax_ContextMenu:focus {outline: none}
.MathJax_ContextMenu .MathJax_MenuItem:focus {outline: none}
#MathJax_AboutClose {top: .2em; right: .2em}
.MathJax_Menu .MathJax_MenuClose {top: -10px; left: -10px}
.MathJax_MenuClose {position: absolute; cursor: pointer; display: inline-block; border: 2px solid #AAA; border-radius: 18px; -webkit-border-radius: 18px; -moz-border-radius: 18px; -khtml-border-radius: 18px; font-family: 'Courier New',Courier; font-size: 24px; color: #F0F0F0}
.MathJax_MenuClose span {display: block; background-color: #AAA; border: 1.5px solid; border-radius: 18px; -webkit-border-radius: 18px; -moz-border-radius: 18px; -khtml-border-radius: 18px; line-height: 0; padding: 8px 0 6px}
.MathJax_MenuClose:hover {color: white!important; border: 2px solid #CCC!important}
.MathJax_MenuClose:hover span {background-color: #CCC!important}
.MathJax_MenuClose:hover:focus {outline: none}
</style><style type="text/css">.MathJax_Preview .MJXf-math {color: inherit!important}
</style><style type="text/css">.MJX_Assistive_MathML {position: absolute!important; top: 0; left: 0; clip: rect(1px, 1px, 1px, 1px); padding: 1px 0 0 0!important; border: 0!important; height: 1px!important; width: 1px!important; overflow: hidden!important; display: block!important; -webkit-touch-callout: none; -webkit-user-select: none; -khtml-user-select: none; -moz-user-select: none; -ms-user-select: none; user-select: none}
.MJX_Assistive_MathML.MJX_Assistive_MathML_Block {width: 100%!important}
</style><style type="text/css">#MathJax_Zoom {position: absolute; background-color: #F0F0F0; overflow: auto; display: block; z-index: 301; padding: .5em; border: 1px solid black; margin: 0; font-weight: normal; font-style: normal; text-align: left; text-indent: 0; text-transform: none; line-height: normal; letter-spacing: normal; word-spacing: normal; word-wrap: normal; white-space: nowrap; float: none; -webkit-box-sizing: content-box; -moz-box-sizing: content-box; box-sizing: content-box; box-shadow: 5px 5px 15px #AAAAAA; -webkit-box-shadow: 5px 5px 15px #AAAAAA; -moz-box-shadow: 5px 5px 15px #AAAAAA; -khtml-box-shadow: 5px 5px 15px #AAAAAA; filter: progid:DXImageTransform.Microsoft.dropshadow(OffX=2, OffY=2, Color='gray', Positive='true')}
#MathJax_ZoomOverlay {position: absolute; left: 0; top: 0; z-index: 300; display: inline-block; width: 100%; height: 100%; border: 0; padding: 0; margin: 0; background-color: white; opacity: 0; filter: alpha(opacity=0)}
#MathJax_ZoomFrame {position: relative; display: inline-block; height: 0; width: 0}
#MathJax_ZoomEventTrap {position: absolute; left: 0; top: 0; z-index: 302; display: inline-block; border: 0; padding: 0; margin: 0; background-color: white; opacity: 0; filter: alpha(opacity=0)}
</style><style type="text/css">.MathJax_Preview {color: #888}
#MathJax_Message {position: fixed; left: 1em; bottom: 1.5em; background-color: #E6E6E6; border: 1px solid #959595; margin: 0px; padding: 2px 8px; z-index: 102; color: black; font-size: 80%; width: auto; white-space: nowrap}
#MathJax_MSIE_Frame {position: absolute; top: 0; left: 0; width: 0px; z-index: 101; border: 0px; margin: 0px; padding: 0px}
.MathJax_Error {color: #CC0000; font-style: italic}
</style><style type="text/css">.MJXp-script {font-size: .8em}
.MJXp-right {-webkit-transform-origin: right; -moz-transform-origin: right; -ms-transform-origin: right; -o-transform-origin: right; transform-origin: right}
.MJXp-bold {font-weight: bold}
.MJXp-italic {font-style: italic}
.MJXp-scr {font-family: MathJax_Script,'Times New Roman',Times,STIXGeneral,serif}
.MJXp-frak {font-family: MathJax_Fraktur,'Times New Roman',Times,STIXGeneral,serif}
.MJXp-sf {font-family: MathJax_SansSerif,'Times New Roman',Times,STIXGeneral,serif}
.MJXp-cal {font-family: MathJax_Caligraphic,'Times New Roman',Times,STIXGeneral,serif}
.MJXp-mono {font-family: MathJax_Typewriter,'Times New Roman',Times,STIXGeneral,serif}
.MJXp-largeop {font-size: 150%}
.MJXp-largeop.MJXp-int {vertical-align: -.2em}
.MJXp-math {display: inline-block; line-height: 1.2; text-indent: 0; font-family: 'Times New Roman',Times,STIXGeneral,serif; white-space: nowrap; border-collapse: collapse}
.MJXp-display {display: block; text-align: center; margin: 1em 0}
.MJXp-math span {display: inline-block}
.MJXp-box {display: block!important; text-align: center}
.MJXp-box:after {content: " "}
.MJXp-rule {display: block!important; margin-top: .1em}
.MJXp-char {display: block!important}
.MJXp-mo {margin: 0 .15em}
.MJXp-mfrac {margin: 0 .125em; vertical-align: .25em}
.MJXp-denom {display: inline-table!important; width: 100%}
.MJXp-denom > * {display: table-row!important}
.MJXp-surd {vertical-align: top}
.MJXp-surd > * {display: block!important}
.MJXp-script-box > *  {display: table!important; height: 50%}
.MJXp-script-box > * > * {display: table-cell!important; vertical-align: top}
.MJXp-script-box > *:last-child > * {vertical-align: bottom}
.MJXp-script-box > * > * > * {display: block!important}
.MJXp-mphantom {visibility: hidden}
.MJXp-munderover {display: inline-table!important}
.MJXp-over {display: inline-block!important; text-align: center}
.MJXp-over > * {display: block!important}
.MJXp-munderover > * {display: table-row!important}
.MJXp-mtable {vertical-align: .25em; margin: 0 .125em}
.MJXp-mtable > * {display: inline-table!important; vertical-align: middle}
.MJXp-mtr {display: table-row!important}
.MJXp-mtd {display: table-cell!important; text-align: center; padding: .5em 0 0 .5em}
.MJXp-mtr > .MJXp-mtd:first-child {padding-left: 0}
.MJXp-mtr:first-child > .MJXp-mtd {padding-top: 0}
.MJXp-mlabeledtr {display: table-row!important}
.MJXp-mlabeledtr > .MJXp-mtd:first-child {padding-left: 0}
.MJXp-mlabeledtr:first-child > .MJXp-mtd {padding-top: 0}
.MJXp-merror {background-color: #FFFF88; color: #CC0000; border: 1px solid #CC0000; padding: 1px 3px; font-style: normal; font-size: 90%}
.MJXp-scale0 {-webkit-transform: scaleX(.0); -moz-transform: scaleX(.0); -ms-transform: scaleX(.0); -o-transform: scaleX(.0); transform: scaleX(.0)}
.MJXp-scale1 {-webkit-transform: scaleX(.1); -moz-transform: scaleX(.1); -ms-transform: scaleX(.1); -o-transform: scaleX(.1); transform: scaleX(.1)}
.MJXp-scale2 {-webkit-transform: scaleX(.2); -moz-transform: scaleX(.2); -ms-transform: scaleX(.2); -o-transform: scaleX(.2); transform: scaleX(.2)}
.MJXp-scale3 {-webkit-transform: scaleX(.3); -moz-transform: scaleX(.3); -ms-transform: scaleX(.3); -o-transform: scaleX(.3); transform: scaleX(.3)}
.MJXp-scale4 {-webkit-transform: scaleX(.4); -moz-transform: scaleX(.4); -ms-transform: scaleX(.4); -o-transform: scaleX(.4); transform: scaleX(.4)}
.MJXp-scale5 {-webkit-transform: scaleX(.5); -moz-transform: scaleX(.5); -ms-transform: scaleX(.5); -o-transform: scaleX(.5); transform: scaleX(.5)}
.MJXp-scale6 {-webkit-transform: scaleX(.6); -moz-transform: scaleX(.6); -ms-transform: scaleX(.6); -o-transform: scaleX(.6); transform: scaleX(.6)}
.MJXp-scale7 {-webkit-transform: scaleX(.7); -moz-transform: scaleX(.7); -ms-transform: scaleX(.7); -o-transform: scaleX(.7); transform: scaleX(.7)}
.MJXp-scale8 {-webkit-transform: scaleX(.8); -moz-transform: scaleX(.8); -ms-transform: scaleX(.8); -o-transform: scaleX(.8); transform: scaleX(.8)}
.MJXp-scale9 {-webkit-transform: scaleX(.9); -moz-transform: scaleX(.9); -ms-transform: scaleX(.9); -o-transform: scaleX(.9); transform: scaleX(.9)}
.MathJax_PHTML .noError {vertical-align: ; font-size: 90%; text-align: left; color: black; padding: 1px 3px; border: 1px solid}
</style></head>

<body id="page-top"><div id="MathJax_Message" style="display: none;"></div>

  <!-- Navigation -->
  <header>
    <nav class="navbar navbar-expand-md navbar-dark bg-dark fixed-top d-print-none" id="mainNav">
      <div class="container">
        <!-- brand -->
        <a class="navbar-brand" href="http://amroamroamro.github.io/mexopencv/">mexopencv</a>
        <!-- collapse button -->
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarResponsive" aria-controls="navbarResponsive" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <!-- collapsible content -->
        <div class="navbar-collapse collapse" id="navbarResponsive">
          <ul class="navbar-nav ml-auto">
            <li class="nav-item">
              <a class="nav-link" href="http://amroamroamro.github.io/mexopencv/index.html">Home</a>
            </li>
            <li class="nav-item dropdown">
              <a class="nav-link dropdown-toggle" href="http://amroamroamro.github.io/mexopencv/opencv.html" id="navbarDropdownMain" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">opencv</a>
              <div class="dropdown-menu dropdown-menu-right" role="menu" aria-labelledby="navbarDropdownMain">
                <a class="dropdown-item" href="http://amroamroamro.github.io/mexopencv/opencv.html#page-top">opencv</a>
                <div class="dropdown-divider"></div>
                <a class="dropdown-item" href="http://amroamroamro.github.io/mexopencv/opencv.html#core">core</a>
                <a class="dropdown-item" href="http://amroamroamro.github.io/mexopencv/opencv.html#imgproc">imgproc</a>
                <a class="dropdown-item" href="http://amroamroamro.github.io/mexopencv/opencv.html#imgcodecs">imgcodecs</a>
                <a class="dropdown-item" href="http://amroamroamro.github.io/mexopencv/opencv.html#videoio">videoio</a>
                <a class="dropdown-item" href="http://amroamroamro.github.io/mexopencv/opencv.html#video">video</a>
                <a class="dropdown-item" href="http://amroamroamro.github.io/mexopencv/opencv.html#calib3d">calib3d</a>
                <a class="dropdown-item" href="http://amroamroamro.github.io/mexopencv/opencv.html#feature2d">feature2d</a>
                <a class="dropdown-item" href="http://amroamroamro.github.io/mexopencv/opencv.html#objdetect">objdetect</a>
                <a class="dropdown-item" href="http://amroamroamro.github.io/mexopencv/opencv.html#dnn">dnn</a>
                <a class="dropdown-item" href="http://amroamroamro.github.io/mexopencv/opencv.html#ml">ml</a>
                <a class="dropdown-item" href="http://amroamroamro.github.io/mexopencv/opencv.html#photo">photo</a>
                <a class="dropdown-item" href="http://amroamroamro.github.io/mexopencv/opencv.html#stitching">stitching</a>
                <a class="dropdown-item" href="http://amroamroamro.github.io/mexopencv/opencv.html#shape">shape</a>
                <a class="dropdown-item" href="http://amroamroamro.github.io/mexopencv/opencv.html#superres">superres</a>
                <a class="dropdown-item" href="http://amroamroamro.github.io/mexopencv/opencv.html#videostab">videostab</a>
              </div>
            </li>
            <li class="nav-item dropdown active">
              <a class="nav-link dropdown-toggle active" href="http://amroamroamro.github.io/mexopencv/opencv_contrib.html#" id="navbarDropdownContrib" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">opencv_contrib</a>
              <div class="dropdown-menu dropdown-menu-right" id="dropdownModules" role="menu" aria-labelledby="navbarDropdownContrib">
                <a class="dropdown-item js-scroll-trigger" href="http://amroamroamro.github.io/mexopencv/opencv_contrib.html#page-top">opencv_contrib</a>
                <div class="dropdown-divider"></div>
                <a class="dropdown-item js-scroll-trigger active" href="http://amroamroamro.github.io/mexopencv/opencv_contrib.html#aruco">aruco</a>
                <a class="dropdown-item js-scroll-trigger" href="http://amroamroamro.github.io/mexopencv/opencv_contrib.html#bgsegm">bgsegm</a>
                <a class="dropdown-item js-scroll-trigger" href="http://amroamroamro.github.io/mexopencv/opencv_contrib.html#bioinspired">bioinspired</a>
                <a class="dropdown-item js-scroll-trigger" href="http://amroamroamro.github.io/mexopencv/opencv_contrib.html#datasets">datasets</a>
                <a class="dropdown-item js-scroll-trigger" href="http://amroamroamro.github.io/mexopencv/opencv_contrib.html#dnn_objdetect">dnn_objdetect</a>
                <a class="dropdown-item js-scroll-trigger" href="http://amroamroamro.github.io/mexopencv/opencv_contrib.html#face">face</a>
                <a class="dropdown-item js-scroll-trigger" href="http://amroamroamro.github.io/mexopencv/opencv_contrib.html#hfs">hfs</a>
                <a class="dropdown-item js-scroll-trigger" href="http://amroamroamro.github.io/mexopencv/opencv_contrib.html#line_descriptor">line_descriptor</a>
                <a class="dropdown-item js-scroll-trigger" href="http://amroamroamro.github.io/mexopencv/opencv_contrib.html#optflow">optflow</a>
                <a class="dropdown-item js-scroll-trigger" href="http://amroamroamro.github.io/mexopencv/opencv_contrib.html#plot">plot</a>
                <a class="dropdown-item js-scroll-trigger" href="http://amroamroamro.github.io/mexopencv/opencv_contrib.html#saliency">saliency</a>
                <a class="dropdown-item js-scroll-trigger" href="http://amroamroamro.github.io/mexopencv/opencv_contrib.html#text">text</a>
                <a class="dropdown-item js-scroll-trigger" href="http://amroamroamro.github.io/mexopencv/opencv_contrib.html#xfeatures2d">xfeatures2d</a>
                <a class="dropdown-item js-scroll-trigger" href="http://amroamroamro.github.io/mexopencv/opencv_contrib.html#ximgproc">ximgproc</a>
                <a class="dropdown-item js-scroll-trigger" href="http://amroamroamro.github.io/mexopencv/opencv_contrib.html#xphoto">xphoto</a>
              </div>
            </li>
          </ul>
        </div>
        <!-- /collapsible content -->
      </div>
    </nav>
  </header>
  <!-- /Navigation -->

  <!-- Main Layout -->
  <main>

    <div class="container">

      <section class="section mb-5" id="aruco">
        <h1 class="my-4">
          <i class="fa fa-book" aria-hidden="true"></i>
          aruco: <small class="text-muted">ArUco Marker Detection</small>
        </h1>
        <table class="table table-striped table-bordered">
          <tbody><tr>
            <td class="thumb">
              <img src="./mexopencv Examples_files/aruco_create_marker_demo.png" alt="thumbnail">
            </td>
            <td>
              <h5><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib/aruco_create_marker_demo.html">ArUco Marker Image</a></h5>
              <p>This example shows how to create an ArUco marker image.</p>
            </td>
          </tr>
          <tr>
            <td class="thumb">
              <img src="./mexopencv Examples_files/aruco_detect_markers_demo.png" alt="thumbnail">
            </td>
            <td>
              <h5><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib/aruco_detect_markers_demo.html">Detection of ArUco Markers</a></h5>
              <p>Basic marker detection and pose estimation from single ArUco markers.</p>
            </td>
          </tr>
          <tr>
            <td class="thumb">
              <img src="./mexopencv Examples_files/aruco_create_board_demo.png" alt="thumbnail">
            </td>
            <td>
              <h5><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib/aruco_create_board_demo.html">ArUco Grid Board Image</a></h5>
              <p>This example shows how to create an ArUco grid board image.</p>
            </td>
          </tr>
          <tr>
            <td class="thumb">
              <img src="./mexopencv Examples_files/aruco_detect_board_demo.png" alt="thumbnail">
            </td>
            <td>
              <h5><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib/aruco_detect_board_demo.html">Detection of ArUco Board</a></h5>
              <p>Detection and pose estimation using a Board of markers (an ArUco Planar Grid board).</p>
            </td>
          </tr>
          <tr>
            <td class="thumb">
              <img src="./mexopencv Examples_files/aruco_create_board_charuco_demo.png" alt="thumbnail">
            </td>
            <td>
              <h5><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib/aruco_create_board_charuco_demo.html">ChArUco Board Image</a></h5>
              <p>This example shows how to create a ChArUco board image.</p>
            </td>
          </tr>
          <tr>
            <td class="thumb">
              <img src="./mexopencv Examples_files/aruco_detect_board_charuco_demo.png" alt="thumbnail">
            </td>
            <td>
              <h5><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib/aruco_detect_board_charuco_demo.html">Detection of ChArUco Corners</a></h5>
              <p>The example shows how to do pose estimation using a ChArUco board.</p>
            </td>
          </tr>
          <tr>
            <td class="thumb">
              <img src="./mexopencv Examples_files/aruco_create_diamond_demo.png" alt="thumbnail">
            </td>
            <td>
              <h5><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib/aruco_create_diamond_demo.html">ChArUco Diamond Image</a></h5>
              <p>This example shows how to create a ChArUco marker image.</p>
            </td>
          </tr>
          <tr>
            <td class="thumb">
              <img src="./mexopencv Examples_files/aruco_detect_diamonds_demo.png" alt="thumbnail">
            </td>
            <td>
              <h5><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib/aruco_detect_diamonds_demo.html">Detection of Diamond Markers</a></h5>
              <p>Detection and pose estimation using ChArUco markers.</p>
            </td>
          </tr>
          <tr>
            <td class="thumb">
              <img src="./mexopencv Examples_files/aruco_calibrate_camera_demo.png" alt="thumbnail">
            </td>
            <td>
              <h5><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib/aruco_calibrate_camera_demo.html">Camera Calibration using ArUco Board</a></h5>
              <p>Calibration using a ArUco Planar Grid board.</p>
            </td>
          </tr>
          <tr>
            <td class="thumb">
              <img src="./mexopencv Examples_files/aruco_calibrate_camera_charuco_demo.png" alt="thumbnail">
            </td>
            <td>
              <h5><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib/aruco_calibrate_camera_charuco_demo.html">Camera Calibration using ChArUco Board</a></h5>
              <p>Calibration using a ChArUco board.</p>
            </td>
          </tr>
        </tbody></table>
      </section>

      <section class="section mb-5" id="bgsegm">
        <h1 class="my-4">
          <i class="fa fa-book" aria-hidden="true"></i>
          bgsegm: <small class="text-muted">Improved Background-Foreground Segmentation Methods</small>
        </h1>
        <table class="table table-striped table-bordered">
          <tbody><tr>
            <td class="thumb">
              <img src="./mexopencv Examples_files/BackgroundSubtractorDemo.png" alt="thumbnail">
            </td>
            <td>
              <h5><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib/BackgroundSubtractorDemo.html">Background Subtractor</a></h5>
              <p>This demos shows how to use background subtraction methods provided by OpenCV.</p>
            </td>
          </tr>
          <tr>
            <td class="thumb">
              <img src="./mexopencv Examples_files/bgsegm_synthetic_seq_demo.png" alt="thumbnail">
            </td>
            <td>
              <h5><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib/bgsegm_synthetic_seq_demo.html">Evaluation of background subtraction algorithms</a></h5>
              <p>Evaluation of background subtraction algorithms on synthetic sequence.</p>
            </td>
          </tr>
        </tbody></table>
      </section>

      <section class="section mb-5" id="bioinspired">
        <h1 class="my-4">
          <i class="fa fa-book" aria-hidden="true"></i>
          bioinspired: <small class="text-muted">Biologically Inspired Vision Models and Derivated Tools</small>
        </h1>
        <table class="table table-striped table-bordered">
          <tbody><tr>
            <td class="thumb">
              <img src="./mexopencv Examples_files/retina_demo.png" alt="thumbnail">
            </td>
            <td>
              <h5><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib/retina_demo.html">Retina demonstration</a></h5>
              <p>Demonstrates the use of wrapper class of the Gipsa/Listic Labs retina model.</p>
            </td>
          </tr>
          <tr>
            <td class="thumb">
              <img src="./mexopencv Examples_files/retina_hdr_tonemapping_demo_gui.png" alt="thumbnail">
            </td>
            <td>
              <h5><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib/retina_hdr_tonemapping_demo_gui.html">OpenEXR images HDR Retina tone mapping</a> <small class="badge badge-secondary">GUI</small></h5>
              <p>High Dynamic Range retina tone mapping with the help of the Gipsa/Listic's retina.</p>
            </td>
          </tr>
        </tbody></table>
      </section>

      <section class="section mb-5" id="datasets">
        <h1 class="my-4">
          <i class="fa fa-book" aria-hidden="true"></i>
          datasets: <small class="text-muted">Framework for Working with Different Datasets</small>
        </h1>
        <table class="table table-striped table-bordered">
          <tbody><tr>
            <td class="thumb">
              <img src="./mexopencv Examples_files/dataset_mnist_demo.png" alt="thumbnail">
            </td>
            <td>
              <h5><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib/dataset_mnist_demo.html">The MNIST dataset of handwritten digits</a></h5>
              <p>Demonstrates loading the MNIST dataset.</p>
            </td>
          </tr>
        </tbody></table>
      </section>

      <section class="section mb-5" id="dnn_objdetect">
        <h1 class="my-4">
          <i class="fa fa-book" aria-hidden="true"></i>
          dnn_objdetect: <small class="text-muted">DNN used for Object Detection</small>
        </h1>
        <table class="table table-striped table-bordered">
          <tbody><tr>
            <td class="thumb">
              <img src="./mexopencv Examples_files/demo.png" alt="thumbnail">
            </td>
            <td>
              <h5><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib/dnn_img_classify_demo.html">DNN for image classification</a></h5>
              <p>An example of how to use the SqueezeNet model to classify an image.</p>
            </td>
          </tr>
          <tr>
            <td class="thumb">
              <img src="./mexopencv Examples_files/dnn_objdetect_demo.png" alt="thumbnail">
            </td>
            <td>
              <h5><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib/dnn_objdetect_demo.html">Object Detection using Convolutional Neural Networks</a></h5>
              <p>An example of how to use the SqueezeDet model to predict object bounding boxes.</p>
            </td>
          </tr>
        </tbody></table>
      </section>

      <section class="section mb-5" id="face">
        <h1 class="my-4">
          <i class="fa fa-book" aria-hidden="true"></i>
          face: <small class="text-muted">Face Analysis</small>
        </h1>
        <table class="table table-striped table-bordered">
          <tbody><tr>
            <td class="thumb">
              <img src="./mexopencv Examples_files/facerec_demo.png" alt="thumbnail">
            </td>
            <td>
              <h5><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib/facerec_demo.html">Face recognition</a></h5>
              <p>Demonstration of face recognition with OpenCV.</p>
            </td>
          </tr>
          <tr>
            <td class="thumb">
              <img src="./mexopencv Examples_files/facemark_kazemi_detect_img_demo.png" alt="thumbnail">
            </td>
            <td>
              <h5><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib/facemark_kazemi_detect_img_demo.html">Face landmark detection in an image</a></h5>
              <p>Face landmark detection in an image using ensemble of regression trees (Kazemi).</p>
            </td>
          </tr>
          <tr>
            <td class="thumb">
              <img src="./mexopencv Examples_files/facemark_kazemi_detect_vid_demo.png" alt="thumbnail">
            </td>
            <td>
              <h5><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib/facemark_kazemi_detect_vid_demo.html">Face landmark detection in a video</a></h5>
              <p>Detect faces in video and finds facial landmarks (Kazemi).</p>
            </td>
          </tr>
          <tr>
            <td class="thumb">
              <img src="./mexopencv Examples_files/demo.png" alt="thumbnail">
            </td>
            <td>
              <h5><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib/facemark_kazemi_train_demo.html">Training face landmark detector</a></h5>
              <p>Trains Kazemi model for facial landmarks detection.</p>
            </td>
          </tr>
          <tr>
            <td class="thumb">
              <img src="./mexopencv Examples_files/demo.png" alt="thumbnail">
            </td>
            <td>
              <h5><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib/facemark_kazemi_train2_demo.html">Training face landmark detector</a></h5>
              <p>Trains Kazemi model for facial landmarks detection.</p>
            </td>
          </tr>
          <tr>
            <td class="thumb">
              <img src="./mexopencv Examples_files/demo.png" alt="thumbnail">
            </td>
            <td>
              <h5><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib/facemark_kazemi_train_config_demo.html">Parameters for training face landmark detector</a></h5>
              <p>Create configuration file with training parameters for Kazemi model.</p>
            </td>
          </tr>
          <tr>
            <td class="thumb">
              <img src="./mexopencv Examples_files/facemark_aam_train_demo.png" alt="thumbnail">
            </td>
            <td>
              <h5><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib/facemark_aam_train_demo.html">Facemark AAM training</a></h5>
              <p>Trains active appearance model (AAM) for facial landmarks detection.</p>
            </td>
          </tr>
          <tr>
            <td class="thumb">
              <img src="./mexopencv Examples_files/facemark_lbf_train_demo.png" alt="thumbnail">
            </td>
            <td>
              <h5><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib/facemark_lbf_train_demo.html">Facemark LBF training</a></h5>
              <p>Trains regressed local binary features (LBF) for facial landmarks detection.</p>
            </td>
          </tr>
          <tr>
            <td class="thumb">
              <img src="./mexopencv Examples_files/facemark_lbf_fitting_demo.png" alt="thumbnail">
            </td>
            <td>
              <h5><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib/facemark_lbf_fitting_demo.html">Face landmark detection in a video</a></h5>
              <p>Detect faces in video and finds facial landmarks (LBF).</p>
            </td>
          </tr>
          <tr>
            <td class="thumb">
              <img src="./mexopencv Examples_files/face_swapping_demo.png" alt="thumbnail">
            </td>
            <td>
              <h5><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib/face_swapping_demo.html">Face swapping using face landmark detection</a></h5>
              <p>Swap face in one image with another face in another image.</p>
            </td>
          </tr>
        </tbody></table>
      </section>

      <section class="section mb-5" id="hfs">
        <h1 class="my-4">
          <i class="fa fa-book" aria-hidden="true"></i>
          hfs: <small class="text-muted">Hierarchical Feature Selection for Efficient Image Segmentation</small>
        </h1>
        <table class="table table-striped table-bordered">
          <tbody><tr>
            <td class="thumb">
              <img src="./mexopencv Examples_files/hfs_segment_demo.png" alt="thumbnail">
            </td>
            <td>
              <h5><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib/hfs_segment_demo.html">Image Segmentation using Hierachical Feature Selection (HFS)</a></h5>
              <p>Demonstrates Image Segmentation using HFS.</p>
            </td>
          </tr>
        </tbody></table>
      </section>

      <section class="section mb-5" id="line_descriptor">
        <h1 class="my-4">
          <i class="fa fa-book" aria-hidden="true"></i>
          line_descriptor: <small class="text-muted">Binary Descriptors for Lines Extracted from an Image</small>
        </h1>
        <table class="table table-striped table-bordered">
          <tbody><tr>
            <td class="thumb">
              <img src="./mexopencv Examples_files/line_extraction_demo.png" alt="thumbnail">
            </td>
            <td>
              <h5><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib/line_extraction_demo.html">Lines features</a></h5>
              <p>This example shows the functionalities of lines extraction and descriptors computation furnished by <code>cv.LSDDetector</code> and <code>cv.BinaryDescriptor</code> classes.</p>
            </td>
          </tr>
          <tr>
            <td class="thumb">
              <img src="./mexopencv Examples_files/line_matching_demo.png" alt="thumbnail">
            </td>
            <td>
              <h5><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib/line_matching_demo.html">Line descriptors matching</a></h5>
              <p>This example shows the functionalities of line descriptors matching furnished by <code>cv.BinaryDescriptorMatcher</code> class.</p>
            </td>
          </tr>
          <tr>
            <td class="thumb">
              <img src="./mexopencv Examples_files/demo.png" alt="thumbnail">
            </td>
            <td>
              <h5><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib/line_radius_matching_demo.html">Line descriptors radius matching</a></h5>
              <p>This example shows the functionalities of radius matching.</p>
            </td>
          </tr>
        </tbody></table>
      </section>

      <section class="section mb-5" id="optflow">
        <h1 class="my-4">
          <i class="fa fa-book" aria-hidden="true"></i>
          optflow: <small class="text-muted">Optical Flow Algorithms</small>
        </h1>
        <table class="table table-striped table-bordered">
          <tbody><tr>
            <td class="thumb">
              <img src="./mexopencv Examples_files/optical_flow_evaluation_demo.png" alt="thumbnail">
            </td>
            <td>
              <h5><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib/optical_flow_evaluation_demo.html">Optical Flow Evaluation</a></h5>
              <p>Computes flow field between two images using various methods and display it (deepflow, simpleflow, sparsetodenseflow, Farneback, TV-L1).</p>
            </td>
          </tr>
          <tr>
            <td class="thumb">
              <img src="./mexopencv Examples_files/gpc_demo.png" alt="thumbnail">
            </td>
            <td>
              <h5><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib/gpc_demo.html">Global Patch Collider</a></h5>
              <p>This sample trains the forest for the Global Patch Collider. It then finds correspondences between two images and calculates error using provided ground truth flow.</p>
            </td>
          </tr>
        </tbody></table>
      </section>

      <section class="section mb-5" id="plot">
        <h1 class="my-4">
          <i class="fa fa-book" aria-hidden="true"></i>
          plot: <small class="text-muted">Plot function for Mat data</small>
        </h1>
        <table class="table table-striped table-bordered">
          <tbody><tr>
            <td class="thumb">
              <img src="./mexopencv Examples_files/plotting_demo.png" alt="thumbnail">
            </td>
            <td>
              <h5><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib/plotting_demo.html">Plotting demo</a></h5>
              <p>Demonstrates OpenCV and MATLAB plotting.</p>
            </td>
          </tr>
        </tbody></table>
      </section>

      <section class="section mb-5" id="saliency">
        <h1 class="my-4">
          <i class="fa fa-book" aria-hidden="true"></i>
          saliency: <small class="text-muted">Saliency API</small>
        </h1>
        <table class="table table-striped table-bordered">
          <tbody><tr>
            <td class="thumb">
              <img src="./mexopencv Examples_files/computeSaliency_demo.png" alt="thumbnail">
            </td>
            <td>
              <h5><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib/computeSaliency_demo.html">Saliency Algorithms</a></h5>
              <p>This example shows the functionality of "Saliency".</p>
            </td>
          </tr>
        </tbody></table>
      </section>

      <section class="section mb-5" id="text">
        <h1 class="my-4">
          <i class="fa fa-book" aria-hidden="true"></i>
          text: <small class="text-muted">Scene Text Detection and Recognition</small>
        </h1>
        <table class="table table-striped table-bordered">
          <tbody><tr>
            <td class="thumb">
              <img src="./mexopencv Examples_files/textboxes_demo.png" alt="thumbnail">
            </td>
            <td>
              <h5><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib/textboxes_demo.html">Scene Text Detection using CNN</a></h5>
              <p>An example of how to detect text in a scene.</p>
            </td>
          </tr>
          <tr>
            <td class="thumb">
              <img src="./mexopencv Examples_files/textboxes_dnn_demo.png" alt="thumbnail">
            </td>
            <td>
              <h5><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib/textboxes_dnn_demo.html">Scene Text Detection using CNN</a></h5>
              <p>An example of how to detect text in a scene.</p>
            </td>
          </tr>
        </tbody></table>
      </section>

      <section class="section mb-5" id="xfeatures2d">
        <h1 class="my-4">
          <i class="fa fa-book" aria-hidden="true"></i>
          xfeatures2d: <small class="text-muted">Extra 2D Features Framework</small>
        </h1>
        <table class="table table-striped table-bordered">
          <tbody><tr>
            <td class="thumb">
              <img src="./mexopencv Examples_files/SIFT_detector.png" alt="thumbnail">
            </td>
            <td>
              <h5><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib/SIFT_detector.html">Introduction to SIFT (Scale-Invariant Feature Transform)</a></h5>
              <p>In this sample, we we show how to find SIFT Keypoints and Descriptors.</p>
            </td>
          </tr>
          <tr>
            <td class="thumb">
              <img src="./mexopencv Examples_files/SURF_detector.png" alt="thumbnail">
            </td>
            <td>
              <h5><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib/SURF_detector.html">Introduction to SURF (Speeded-Up Robust Features)</a></h5>
              <p>SURF keypoint detection + keypoint drawing with OpenCV functions.</p>
            </td>
          </tr>
          <tr>
            <td class="thumb">
              <img src="./mexopencv Examples_files/demo.png" alt="thumbnail">
            </td>
            <td>
              <h5><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib/descriptor_extractor_brief_demo.html">BRIEF (Binary Robust Independent Elementary Features)</a></h5>
              <p>In this demo, we will see the basics of BRIEF algorithm.</p>
            </td>
          </tr>
          <tr>
            <td class="thumb">
              <img src="./mexopencv Examples_files/SURF_descriptor.png" alt="thumbnail">
            </td>
            <td>
              <h5><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib/SURF_descriptor.html">Feature Matching</a></h5>
              <p>SURF detector + descriptor + BruteForce/FLANN Matcher + drawing matches with OpenCV functions.</p>
            </td>
          </tr>
          <tr>
            <td class="thumb">
              <img src="./mexopencv Examples_files/gms_matcher_img_demo.png" alt="thumbnail">
            </td>
            <td>
              <h5><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib/gms_matcher_img_demo.html">GMS matching strategy (image)</a></h5>
              <p>Sample demonstrates the GMS matching strategy.</p>
            </td>
          </tr>
          <tr>
            <td class="thumb">
              <img src="./mexopencv Examples_files/gms_matcher_vid_demo.png" alt="thumbnail">
            </td>
            <td>
              <h5><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib/gms_matcher_vid_demo.html">GMS matching strategy (video)</a></h5>
              <p>Sample demonstrates the GMS matching strategy applied on video frames.</p>
            </td>
          </tr>
        </tbody></table>
      </section>

      <section class="section mb-5" id="ximgproc">
        <h1 class="my-4">
          <i class="fa fa-book" aria-hidden="true"></i>
          ximgproc: <small class="text-muted">Extended Image Processing</small>
        </h1>
        <table class="table table-striped table-bordered">
          <tbody><tr>
            <td class="thumb">
              <img src="./mexopencv Examples_files/superpixels_demo.png" alt="thumbnail">
            </td>
            <td>
              <h5><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib/superpixels_demo.html">Superpixels Segmentation</a></h5>
              <p>This program demonstrates superpixels segmentation using OpenCV classes <code>cv.SuperpixelSEEDS</code>, <code>cv.SuperpixelSLIC</code>, and <code>cv.SuperpixelLSC</code>.</p>
            </td>
          </tr>
          <tr>
            <td class="thumb">
              <img src="./mexopencv Examples_files/fast_hough_transform_demo.png" alt="thumbnail">
            </td>
            <td>
              <h5><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib/fast_hough_transform_demo.html">Line Finding with the Fast Hough transform</a></h5>
              <p>This program demonstrates line finding with the Fast Hough transform.</p>
            </td>
          </tr>
          <tr>
            <td class="thumb">
              <img src="./mexopencv Examples_files/structured_edge_detection_demo.png" alt="thumbnail">
            </td>
            <td>
              <h5><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib/structured_edge_detection_demo.html">Structured Forests for Fast Edge Detection</a></h5>
              <p>This sample demonstrates structured forests for fast edge detection, and edgeboxes.</p>
            </td>
          </tr>
          <tr>
            <td class="thumb">
              <img src="./mexopencv Examples_files/graphsegmentation_demo.png" alt="thumbnail">
            </td>
            <td>
              <h5><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib/graphsegmentation_demo.html">Graph-Based Image Segmentation</a></h5>
              <p>A program demonstrating the use and capabilities of a particular graph based image segmentation algorithm.</p>
            </td>
          </tr>
          <tr>
            <td class="thumb">
              <img src="./mexopencv Examples_files/niblack_thresholding_demo.png" alt="thumbnail">
            </td>
            <td>
              <h5><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib/niblack_thresholding_demo.html">Niblack Thresholding</a></h5>
              <p>Sample to compare Niblack thresholding against other algorithms (global thresholding and adaptive thresholding) for an image with varying illumination.</p>
            </td>
          </tr>
          <tr>
            <td class="thumb">
              <img src="./mexopencv Examples_files/dtFilter_demo_gui.png" alt="thumbnail">
            </td>
            <td>
              <h5><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib/dtFilter_demo_gui.html">Domain Transform Filter</a> <small class="badge badge-secondary">GUI</small></h5>
              <p>This program demonstrates Domain Transform filtering using <code>cv.DTFilter</code>.</p>
            </td>
          </tr>
          <tr>
            <td class="thumb">
              <img src="./mexopencv Examples_files/disparity_filtering_demo.png" alt="thumbnail">
            </td>
            <td>
              <h5><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib/disparity_filtering_demo.html">Disparity Map Filtering</a></h5>
              <p>In this tutorial you will learn how to use the disparity map post-filtering to improve the results of <code>cv.StereoBM</code> and <code>cv.StereoSGBM</code> algorithms.</p>
            </td>
          </tr>
          <tr>
            <td class="thumb">
              <img src="./mexopencv Examples_files/fld_lines_demo.png" alt="thumbnail">
            </td>
            <td>
              <h5><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib/fld_lines_demo.html">Fast Line Detector</a></h5>
              <p>Compares <code>cv.FastLineDetector</code> against <code>cv.LineSegmentDetector</code>.</p>
            </td>
          </tr>
          <tr>
            <td class="thumb">
              <img src="./mexopencv Examples_files/anisodiff_demo_gui.png" alt="thumbnail">
            </td>
            <td>
              <h5><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib/anisodiff_demo_gui.html">Perona-Malik Anisotropic Diffusion</a> <small class="badge badge-secondary">GUI</small></h5>
              <p>This sample demonstrates Perona-Malik anisotropic diffusion.</p>
            </td>
          </tr>
          <tr>
            <td class="thumb">
              <img src="./mexopencv Examples_files/peilin_demo.png" alt="thumbnail">
            </td>
            <td>
              <h5><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib/peilin_demo.html">Pei&amp;Lin Normalization</a></h5>
              <p>This program demonstrates Pei&amp;Lin Normalization.</p>
            </td>
          </tr>
          <tr>
            <td class="thumb">
              <img src="./mexopencv Examples_files/brightedges_demo_gui.png" alt="thumbnail">
            </td>
            <td>
              <h5><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib/brightedges_demo_gui.html">Bright edges detection</a> <small class="badge badge-secondary">GUI</small></h5>
              <p>This sample demonstrates BrightEdges detector.</p>
            </td>
          </tr>
          <tr>
            <td class="thumb">
              <img src="./mexopencv Examples_files/fourier_descriptors_demo_gui.png" alt="thumbnail">
            </td>
            <td>
              <h5><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib/fourier_descriptors_demo_gui.html">Fourier Descriptors</a> <small class="badge badge-secondary">GUI</small></h5>
              <p>This sample demonstrates using Fourier descriptors for contour matching.</p>
            </td>
          </tr>
        </tbody></table>
      </section>

      <section class="section mb-5" id="xphoto">
        <h1 class="my-4">
          <i class="fa fa-book" aria-hidden="true"></i>
          xphoto: <small class="text-muted">Additional Photo Processing Algorithms</small>
        </h1>
        <table class="table table-striped table-bordered">
          <tbody><tr>
            <td class="thumb">
              <img src="./mexopencv Examples_files/color_balance_demo.png" alt="thumbnail">
            </td>
            <td>
              <h5><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib/color_balance_demo.html">White Balancing</a></h5>
              <p>OpenCV color balance demonstration sample.</p>
            </td>
          </tr>
        </tbody></table>
      </section>

    </div>

  </main>
  <!-- /Main Layout -->

  <!-- Footer -->
  <footer class="bg-dark text-light pt-3">
    <div class="container">
      <div class="row">
        <div class="col-md-3 col-sm-6">
          <ul class="list-unstyled">
            <li class="text-uppercase"><strong>mexopencv</strong></li>
            <li><a href="http://amroamroamro.github.io/mexopencv/index.html">Home</a></li>
            <li><a href="https://github.com/kyamagu/mexopencv">GitHub</a></li>
          </ul>
        </div>
        <div class="col-md-3 col-sm-6">
          <ul class="list-unstyled">
            <li class="text-uppercase"><strong>Documentation</strong></li>
            <li><a href="https://github.com/kyamagu/mexopencv/wiki">Wiki</a></li>
            <li><a href="http://amroamroamro.github.io/mexopencv/matlab/">User Docs</a></li>
            <li><a href="http://amroamroamro.github.io/mexopencv/cpp/">Dev Docs</a></li>
          </ul>
        </div>
        <div class="col-md-3 col-sm-6">
          <ul class="list-unstyled">
            <li class="text-uppercase"><strong>External Docs</strong></li>
            <li><a href="https://docs.opencv.org/3.4.1/">OpenCV</a></li>
            <li><a href="https://www.mathworks.com/help/matlab/index.html">MATLAB</a></li>
            <li><a href="https://www.gnu.org/software/octave/doc/interpreter/">Octave</a></li>
          </ul>
        </div>
        <div class="col-md-3 col-sm-6">
          <ul class="list-unstyled">
            <li class="text-uppercase"><strong>Examples</strong></li>
            <li><a href="http://amroamroamro.github.io/mexopencv/opencv.html">opencv</a></li>
            <li><a href="http://amroamroamro.github.io/mexopencv/opencv_contrib.html">opencv_contrib</a></li>
          </ul>
        </div>
      </div>
    </div>
    <div class="footer-copyright text-muted">
      <ul class="list-unstyled mb-0">
        <li>mexopencv is free software under the <a rel="license" href="https://github.com/kyamagu/mexopencv/blob/master/LICENSE">BSD-3 Licence</a></li>
        <li>Copyright © 2011-2018 mexopencv team</li>
      </ul>
    </div>
  </footer>
  <!-- /Footer -->

  <!-- "scroll to top" button (only visible on small screen sizes) -->
  <div class="scroll-top d-md-none d-print-none">
    <a class="btn btn-primary js-scroll-trigger" href="http://amroamroamro.github.io/mexopencv/opencv_contrib.html#page-top">
      <i class="fa fa-chevron-up"></i>
    </a>
  </div>

  <!-- JavaScript -->
  <script src="./mexopencv Examples_files/jquery.slim.min.js.Download"></script>
  <script src="./mexopencv Examples_files/bootstrap.bundle.min.js.Download"></script>
  <script src="./mexopencv Examples_files/script.min.js.Download"></script>

  <!-- MathJax -->
  <script type="text/x-mathjax-config;executed=true">
  MathJax.Hub.Config({
    tex2jax: {
      inlineMath: [ ['$', '$'], ['\\(', '\\)'] ]
    }
  });
  </script>
  <script src="./mexopencv Examples_files/MathJax.js.Download"></script>




</body></html>
