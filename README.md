###

<style>
body {
  background: #0d1117;
}
@keyframes float {
	0% {
		box-shadow: 0 5px 15px 0px rgba(0,0,0,0.6);
		transform: translatey(0px);
	}
	50% {
		box-shadow: 0 25px 15px 0px rgba(0,0,0,0.2);
		transform: translatey(-20px);
	}
	100% {
		box-shadow: 0 5px 15px 0px rgba(0,0,0,0.6);
		transform: translatey(0px);
	}
}
/* .art {
  	animation: float 6s ease-in-out infinite;
} */

/* @-webkit-keyframes animateBubble {
    100% {
        margin-top: 50px;
    }
}

@-moz-keyframes animateBubble {
    100% {
        margin-top: 50px;
    }
} */

@keyframes animateBubble {
    from  { 
        height: 0px;

    }
    to {
        margin-top: 50%;
        height: 250px;
    }
}

@-webkit-keyframes sideWays { 
    0% { 
        margin-left:0px;
    }
    100% { 
        margin-left:50px;
    }
}

@-moz-keyframes sideWays { 
    0% { 
        margin-left:0px;
    }
    100% { 
        margin-left:50px;
    }
}

@keyframes sideWays { 
    0% { 
        margin-left:0px;
    }
    100% { 
        margin-left:100px;
    }
}

/* ANIMATIONS */


.bubble {
  height: 450px;
	width: 450px;
  position: absolute;
  top: -3%;
}

.bubbleG {
  /* height: 180px; */
	width: 180px;
  position: absolute;
  top: -5%;
  height: 0;
}

.x1 {
  animation: animateBubble 20s linear infinite, sideWays 2s ease-in-out infinite alternate;
  animation-delay: 5s;
  -moz-animation-delay: 5;
   -webkit-animation-delay: 5s;
   -o-animation-delay: 5s;


	left: -10%;
	-webkit-transform: scale(0.22);
	-moz-transform: scale(0.22);
	transform: scale(0.22);
}

.x2 {
  -webkit-animation: animateBubble 20s linear infinite, sideWays 4s ease-in-out infinite alternate;
	-moz-animation: animateBubble 20s linear infinite, sideWays 4s ease-in-out infinite alternate;
	animation: animateBubble 20s linear infinite, sideWays 4s ease-in-out infinite alternate;
	animation-delay: 5s;
  -moz-animation-delay: 5;
   -webkit-animation-delay: 5s;
   -o-animation-delay: 5s;
	left: 40%;

	
	-webkit-transform: scale(0.22);
	-moz-transform: scale(0.22);
	transform: scale(0.22);
}

.x3 {
  -webkit-animation: animateBubble 28s linear infinite, sideWays 2s ease-in-out infinite alternate;
	-moz-animation: animateBubble 28s linear infinite, sideWays 2s ease-in-out infinite alternate;
	animation: animateBubble 28s linear infinite, sideWays 2s ease-in-out infinite alternate;
	animation-delay: 5s;
  -moz-animation-delay: 5;
   -webkit-animation-delay: 5s;
   -o-animation-delay: 5s;
	left: 20%;
	
	-webkit-transform: scale(0.22);
	-moz-transform: scale(0.22);
	transform: scale(0.22);
}

.x4 {
    -webkit-animation: animateBubble 22s linear infinite, sideWays 3s ease-in-out infinite alternate;
	-moz-animation: animateBubble 22s linear infinite, sideWays 3s ease-in-out infinite alternate;
	animation: animateBubble 22s linear infinite, sideWays 3s ease-in-out infinite alternate;
	
	animation-delay: 5s;
  -moz-animation-delay: 5;
   -webkit-animation-delay: 5s;
   -o-animation-delay: 5s;
	left: 50%;
	-webkit-transform: scale(0.22);
	-moz-transform: scale(0.22);
	transform: scale(0.22);
}

.x5 {
    -webkit-animation: animateBubble 29s linear infinite, sideWays 4s ease-in-out infinite alternate;
	-moz-animation: animateBubble 29s linear infinite, sideWays 4s ease-in-out infinite alternate;
	animation: animateBubble 29s linear infinite, sideWays 4s ease-in-out infinite alternate;
	
	animation-delay: 5s;
  -moz-animation-delay: 5;
   -webkit-animation-delay: 5s;
   -o-animation-delay: 5s;
	left: 40%;
	-webkit-transform: scale(0.22);
	-moz-transform: scale(0.22);
	transform: scale(0.22);
}

.x6 {
    -webkit-animation: animateBubble 21s linear infinite, sideWays 2s ease-in-out infinite alternate;
	-moz-animation: animateBubble 21s linear infinite, sideWays 2s ease-in-out infinite alternate;
	animation: animateBubble 21s linear infinite, sideWays 2s ease-in-out infinite alternate;
	
	animation-delay: 5s;
  -moz-animation-delay: 5;
   -webkit-animation-delay: 5s;
   -o-animation-delay: 5s;
	left: 30%;
	-webkit-transform: scale(0.22);
	-moz-transform: scale(0.22);
	transform: scale(0.22);
}

.x7 {
    -webkit-animation: animateBubble 20s linear infinite, sideWays 2s ease-in-out infinite alternate;
	-moz-animation: animateBubble 20s linear infinite, sideWays 2s ease-in-out infinite alternate;
	animation: animateBubble 20s linear infinite, sideWays 2s ease-in-out infinite alternate;
	animation-delay: 5s;
  -moz-animation-delay: 5;
   -webkit-animation-delay: 5s;
   -o-animation-delay: 5s;
	
	left: 65%;
	top: 70%;
	
	-webkit-transform: scale(0.4);
	-moz-transform: scale(0.4);
	transform: scale(0.4);
}

.x8 {
    -webkit-animation: animateBubble 22s linear infinite, sideWays 3s ease-in-out infinite alternate;
	-moz-animation: animateBubble 22s linear infinite, sideWays 3s ease-in-out infinite alternate;
	animation: animateBubble 22s linear infinite, sideWays 3s ease-in-out infinite alternate;
	animation-delay: 5s;
  -moz-animation-delay: 5;
   -webkit-animation-delay: 5s;
   -o-animation-delay: 5s;
	
	left: 70%;
	top: 10%;
	
	-webkit-transform: scale(0.3);
	-moz-transform: scale(0.3);
	transform: scale(0.3);
}

.x9 {
    -webkit-animation: animateBubble 29s linear infinite, sideWays 4s ease-in-out infinite alternate;
	-moz-animation: animateBubble 29s linear infinite, sideWays 4s ease-in-out infinite alternate;
	animation: animateBubble 29s linear infinite, sideWays 4s ease-in-out infinite alternate;
	animation-delay: 5s;
  -moz-animation-delay: 5;
   -webkit-animation-delay: 5s;
   -o-animation-delay: 5s;
	
	left: 50%;
	top: 50%;
	
	-webkit-transform: scale(0.6);
	-moz-transform: scale(0.6);
	transform: scale(0.6);
}

.x10 {
    -webkit-animation: animateBubble 26s linear infinite, sideWays 3s ease-in-out infinite alternate;
	-moz-animation: animateBubble 26s linear infinite, sideWays 3s ease-in-out infinite alternate;
	animation: animateBubble 26s linear infinite, sideWays 3s ease-in-out infinite alternate;
	animation-delay: 5s;
  -moz-animation-delay: 5;
   -webkit-animation-delay: 5s;
   -o-animation-delay: 5s;
	
	-webkit-transform: scale(0.3);
	-moz-transform: scale(0.3);
	transform: scale(0.3);
}

.x11 {
    -webkit-animation: animateBubble 29s linear infinite, sideWays 3s ease-in-out infinite alternate;
	-moz-animation: animateBubble 29s linear infinite, sideWays 3s ease-in-out infinite alternate;
	animation: animateBubble 29s linear infinite, sideWays 3s ease-in-out infinite alternate;
	animation-delay: 5s;
  -moz-animation-delay: 5;
   -webkit-animation-delay: 5s;
   -o-animation-delay: 5s;
	left: 55%;
	
	-webkit-transform: scale(0.3);
	-moz-transform: scale(0.3);
	transform: scale(0.3);
}
.x12 {
    -webkit-animation: animateBubble 32s linear infinite, sideWays 6s ease-in-out infinite alternate;
	-moz-animation: animateBubble 32s linear infinite, sideWays 6s ease-in-out infinite alternate;
	animation: animateBubble 32s linear infinite, sideWays 6s ease-in-out infinite alternate;
	animation-delay: 5s;
  -moz-animation-delay: 5;
   -webkit-animation-delay: 5s;
   -o-animation-delay: 5s;
	left: 77%;
	
	-webkit-transform: scale(0.3);
	-moz-transform: scale(0.3);
	transform: scale(0.3);
}
.x13 {
    -webkit-animation: animateBubble 35s linear infinite, sideWays 2.5s ease-in-out infinite alternate;
	-moz-animation: animateBubble 35s linear infinite, sideWays 2.5s ease-in-out infinite alternate;
	animation: animateBubble 35s linear infinite, sideWays 2.5s ease-in-out infinite alternate;
	animation-delay: 5s;
  -moz-animation-delay: 5;
   -webkit-animation-delay: 5s;
   -o-animation-delay: 5s;
	left: 350%;
	
	-webkit-transform: scale(0.3);
	-moz-transform: scale(0.3);
	transform: scale(0.3);
}
</style>

<style>
  <style type="text/css">.anychart-credits{position:absolute;overflow:hidden;right:9px;bottom:6px;height:10px;}.anychart-credits a {text-decoration:none;}.anychart-credits-logo{border:none;margin-right:2px;height:10px;width:10px;display:inline-block;vertical-align:top;}.anychart-credits-text{font-size:10px;line-height:9px;display:inline-block;vertical-align:top;text-decoration:none;font-family:"Helvetica Neue",Helvetica,Arial,sans-serif;color:#929292;height:10px;}
  
  .apexcharts-canvas {
  position: relative;
  user-select: none;
  /* cannot give overflow: hidden as it will crop tooltips which overflow outside chart area */
}


/* scrollbar is not visible by default for legend, hence forcing the visibility */
.apexcharts-canvas ::-webkit-scrollbar {
  -webkit-appearance: none;
  width: 6px;
}

.apexcharts-canvas ::-webkit-scrollbar-thumb {
  border-radius: 4px;
  background-color: rgba(0, 0, 0, .5);
  box-shadow: 0 0 1px rgba(255, 255, 255, .5);
  -webkit-box-shadow: 0 0 1px rgba(255, 255, 255, .5);
}


.apexcharts-inner {
  position: relative;
}

.apexcharts-text tspan {
  font-family: inherit;
}

.legend-mouseover-inactive {
  transition: 0.15s ease all;
  opacity: 0.20;
}

.apexcharts-series-collapsed {
  opacity: 0;
}

.apexcharts-tooltip {
  border-radius: 5px;
  box-shadow: 2px 2px 6px -4px #999;
  cursor: default;
  font-size: 14px;
  left: 62px;
  opacity: 0;
  pointer-events: none;
  position: absolute;
  top: 20px;
  display: flex;
  flex-direction: column;
  overflow: hidden;
  white-space: nowrap;
  z-index: 12;
  transition: 0.15s ease all;
}

.apexcharts-tooltip.apexcharts-active {
  opacity: 1;
  transition: 0.15s ease all;
}

.apexcharts-tooltip.apexcharts-theme-light {
  border: 1px solid #e3e3e3;
  background: rgba(255, 255, 255, 0.96);
}

.apexcharts-tooltip.apexcharts-theme-dark {
  color: #fff;
  background: rgba(30, 30, 30, 0.8);
}

.apexcharts-tooltip * {
  font-family: inherit;
}


.apexcharts-tooltip-title {
  padding: 6px;
  font-size: 15px;
  margin-bottom: 4px;
}

.apexcharts-tooltip.apexcharts-theme-light .apexcharts-tooltip-title {
  background: #ECEFF1;
  border-bottom: 1px solid #ddd;
}

.apexcharts-tooltip.apexcharts-theme-dark .apexcharts-tooltip-title {
  background: rgba(0, 0, 0, 0.7);
  border-bottom: 1px solid #333;
}

.apexcharts-tooltip-text-y-value,
.apexcharts-tooltip-text-goals-value,
.apexcharts-tooltip-text-z-value {
  display: inline-block;
  font-weight: 600;
  margin-left: 5px;
}

.apexcharts-tooltip-text-y-label:empty,
.apexcharts-tooltip-text-y-value:empty,
.apexcharts-tooltip-text-goals-label:empty,
.apexcharts-tooltip-text-goals-value:empty,
.apexcharts-tooltip-text-z-value:empty {
  display: none;
}

.apexcharts-tooltip-text-y-value,
.apexcharts-tooltip-text-goals-value,
.apexcharts-tooltip-text-z-value {
  font-weight: 600;
}

.apexcharts-tooltip-text-goals-label, 
.apexcharts-tooltip-text-goals-value {
  padding: 6px 0 5px;
}

.apexcharts-tooltip-goals-group, 
.apexcharts-tooltip-text-goals-label, 
.apexcharts-tooltip-text-goals-value {
  display: flex;
}
.apexcharts-tooltip-text-goals-label:not(:empty),
.apexcharts-tooltip-text-goals-value:not(:empty) {
  margin-top: -6px;
}

.apexcharts-tooltip-marker {
  width: 12px;
  height: 12px;
  position: relative;
  top: 0px;
  margin-right: 10px;
  border-radius: 50%;
}

.apexcharts-tooltip-series-group {
  padding: 0 10px;
  display: none;
  text-align: left;
  justify-content: left;
  align-items: center;
}

.apexcharts-tooltip-series-group.apexcharts-active .apexcharts-tooltip-marker {
  opacity: 1;
}

.apexcharts-tooltip-series-group.apexcharts-active,
.apexcharts-tooltip-series-group:last-child {
  padding-bottom: 4px;
}

.apexcharts-tooltip-series-group-hidden {
  opacity: 0;
  height: 0;
  line-height: 0;
  padding: 0 !important;
}

.apexcharts-tooltip-y-group {
  padding: 6px 0 5px;
}

.apexcharts-tooltip-box, .apexcharts-custom-tooltip {
  padding: 4px 8px;
}

.apexcharts-tooltip-boxPlot {
  display: flex;
  flex-direction: column-reverse;
}

.apexcharts-tooltip-box>div {
  margin: 4px 0;
}

.apexcharts-tooltip-box span.value {
  font-weight: bold;
}

.apexcharts-tooltip-rangebar {
  padding: 5px 8px;
}

.apexcharts-tooltip-rangebar .category {
  font-weight: 600;
  color: #777;
}

.apexcharts-tooltip-rangebar .series-name {
  font-weight: bold;
  display: block;
  margin-bottom: 5px;
}

.apexcharts-xaxistooltip {
  opacity: 0;
  padding: 9px 10px;
  pointer-events: none;
  color: #373d3f;
  font-size: 13px;
  text-align: center;
  border-radius: 2px;
  position: absolute;
  z-index: 10;
  background: #ECEFF1;
  border: 1px solid #90A4AE;
  transition: 0.15s ease all;
}

.apexcharts-xaxistooltip.apexcharts-theme-dark {
  background: rgba(0, 0, 0, 0.7);
  border: 1px solid rgba(0, 0, 0, 0.5);
  color: #fff;
}

.apexcharts-xaxistooltip:after,
.apexcharts-xaxistooltip:before {
  left: 50%;
  border: solid transparent;
  content: " ";
  height: 0;
  width: 0;
  position: absolute;
  pointer-events: none;
}

.apexcharts-xaxistooltip:after {
  border-color: rgba(236, 239, 241, 0);
  border-width: 6px;
  margin-left: -6px;
}

.apexcharts-xaxistooltip:before {
  border-color: rgba(144, 164, 174, 0);
  border-width: 7px;
  margin-left: -7px;
}

.apexcharts-xaxistooltip-bottom:after,
.apexcharts-xaxistooltip-bottom:before {
  bottom: 100%;
}

.apexcharts-xaxistooltip-top:after,
.apexcharts-xaxistooltip-top:before {
  top: 100%;
}

.apexcharts-xaxistooltip-bottom:after {
  border-bottom-color: #ECEFF1;
}

.apexcharts-xaxistooltip-bottom:before {
  border-bottom-color: #90A4AE;
}

.apexcharts-xaxistooltip-bottom.apexcharts-theme-dark:after {
  border-bottom-color: rgba(0, 0, 0, 0.5);
}

.apexcharts-xaxistooltip-bottom.apexcharts-theme-dark:before {
  border-bottom-color: rgba(0, 0, 0, 0.5);
}

.apexcharts-xaxistooltip-top:after {
  border-top-color: #ECEFF1
}

.apexcharts-xaxistooltip-top:before {
  border-top-color: #90A4AE;
}

.apexcharts-xaxistooltip-top.apexcharts-theme-dark:after {
  border-top-color: rgba(0, 0, 0, 0.5);
}

.apexcharts-xaxistooltip-top.apexcharts-theme-dark:before {
  border-top-color: rgba(0, 0, 0, 0.5);
}

.apexcharts-xaxistooltip.apexcharts-active {
  opacity: 1;
  transition: 0.15s ease all;
}

.apexcharts-yaxistooltip {
  opacity: 0;
  padding: 4px 10px;
  pointer-events: none;
  color: #373d3f;
  font-size: 13px;
  text-align: center;
  border-radius: 2px;
  position: absolute;
  z-index: 10;
  background: #ECEFF1;
  border: 1px solid #90A4AE;
}

.apexcharts-yaxistooltip.apexcharts-theme-dark {
  background: rgba(0, 0, 0, 0.7);
  border: 1px solid rgba(0, 0, 0, 0.5);
  color: #fff;
}

.apexcharts-yaxistooltip:after,
.apexcharts-yaxistooltip:before {
  top: 50%;
  border: solid transparent;
  content: " ";
  height: 0;
  width: 0;
  position: absolute;
  pointer-events: none;
}

.apexcharts-yaxistooltip:after {
  border-color: rgba(236, 239, 241, 0);
  border-width: 6px;
  margin-top: -6px;
}

.apexcharts-yaxistooltip:before {
  border-color: rgba(144, 164, 174, 0);
  border-width: 7px;
  margin-top: -7px;
}

.apexcharts-yaxistooltip-left:after,
.apexcharts-yaxistooltip-left:before {
  left: 100%;
}

.apexcharts-yaxistooltip-right:after,
.apexcharts-yaxistooltip-right:before {
  right: 100%;
}

.apexcharts-yaxistooltip-left:after {
  border-left-color: #ECEFF1;
}

.apexcharts-yaxistooltip-left:before {
  border-left-color: #90A4AE;
}

.apexcharts-yaxistooltip-left.apexcharts-theme-dark:after {
  border-left-color: rgba(0, 0, 0, 0.5);
}

.apexcharts-yaxistooltip-left.apexcharts-theme-dark:before {
  border-left-color: rgba(0, 0, 0, 0.5);
}

.apexcharts-yaxistooltip-right:after {
  border-right-color: #ECEFF1;
}

.apexcharts-yaxistooltip-right:before {
  border-right-color: #90A4AE;
}

.apexcharts-yaxistooltip-right.apexcharts-theme-dark:after {
  border-right-color: rgba(0, 0, 0, 0.5);
}

.apexcharts-yaxistooltip-right.apexcharts-theme-dark:before {
  border-right-color: rgba(0, 0, 0, 0.5);
}

.apexcharts-yaxistooltip.apexcharts-active {
  opacity: 1;
}

.apexcharts-yaxistooltip-hidden {
  display: none;
}

.apexcharts-xcrosshairs,
.apexcharts-ycrosshairs {
  pointer-events: none;
  opacity: 0;
  transition: 0.15s ease all;
}

.apexcharts-xcrosshairs.apexcharts-active,
.apexcharts-ycrosshairs.apexcharts-active {
  opacity: 1;
  transition: 0.15s ease all;
}

.apexcharts-ycrosshairs-hidden {
  opacity: 0;
}

.apexcharts-selection-rect {
  cursor: move;
}

.svg_select_boundingRect, .svg_select_points_rot {
  pointer-events: none;
  opacity: 0;
  visibility: hidden;
}
.apexcharts-selection-rect + g .svg_select_boundingRect,
.apexcharts-selection-rect + g .svg_select_points_rot {
  opacity: 0;
  visibility: hidden;
}

.apexcharts-selection-rect + g .svg_select_points_l,
.apexcharts-selection-rect + g .svg_select_points_r {
  cursor: ew-resize;
  opacity: 1;
  visibility: visible;
}

.svg_select_points {
  fill: #efefef;
  stroke: #333;
  rx: 2;
}

.apexcharts-svg.apexcharts-zoomable.hovering-zoom {
  cursor: crosshair
}

.apexcharts-svg.apexcharts-zoomable.hovering-pan {
  cursor: move
}

.apexcharts-zoom-icon,
.apexcharts-zoomin-icon,
.apexcharts-zoomout-icon,
.apexcharts-reset-icon,
.apexcharts-pan-icon,
.apexcharts-selection-icon,
.apexcharts-menu-icon,
.apexcharts-toolbar-custom-icon {
  cursor: pointer;
  width: 20px;
  height: 20px;
  line-height: 24px;
  color: #6E8192;
  text-align: center;
}

.apexcharts-zoom-icon svg,
.apexcharts-zoomin-icon svg,
.apexcharts-zoomout-icon svg,
.apexcharts-reset-icon svg,
.apexcharts-menu-icon svg {
  fill: #6E8192;
}

.apexcharts-selection-icon svg {
  fill: #444;
  transform: scale(0.76)
}

.apexcharts-theme-dark .apexcharts-zoom-icon svg,
.apexcharts-theme-dark .apexcharts-zoomin-icon svg,
.apexcharts-theme-dark .apexcharts-zoomout-icon svg,
.apexcharts-theme-dark .apexcharts-reset-icon svg,
.apexcharts-theme-dark .apexcharts-pan-icon svg,
.apexcharts-theme-dark .apexcharts-selection-icon svg,
.apexcharts-theme-dark .apexcharts-menu-icon svg,
.apexcharts-theme-dark .apexcharts-toolbar-custom-icon svg {
  fill: #f3f4f5;
}

.apexcharts-canvas .apexcharts-zoom-icon.apexcharts-selected svg,
.apexcharts-canvas .apexcharts-selection-icon.apexcharts-selected svg,
.apexcharts-canvas .apexcharts-reset-zoom-icon.apexcharts-selected svg {
  fill: #008FFB;
}

.apexcharts-theme-light .apexcharts-selection-icon:not(.apexcharts-selected):hover svg,
.apexcharts-theme-light .apexcharts-zoom-icon:not(.apexcharts-selected):hover svg,
.apexcharts-theme-light .apexcharts-zoomin-icon:hover svg,
.apexcharts-theme-light .apexcharts-zoomout-icon:hover svg,
.apexcharts-theme-light .apexcharts-reset-icon:hover svg,
.apexcharts-theme-light .apexcharts-menu-icon:hover svg {
  fill: #333;
}

.apexcharts-selection-icon,
.apexcharts-menu-icon {
  position: relative;
}

.apexcharts-reset-icon {
  margin-left: 5px;
}

.apexcharts-zoom-icon,
.apexcharts-reset-icon,
.apexcharts-menu-icon {
  transform: scale(0.85);
}

.apexcharts-zoomin-icon,
.apexcharts-zoomout-icon {
  transform: scale(0.7)
}

.apexcharts-zoomout-icon {
  margin-right: 3px;
}

.apexcharts-pan-icon {
  transform: scale(0.62);
  position: relative;
  left: 1px;
  top: 0px;
}

.apexcharts-pan-icon svg {
  fill: #fff;
  stroke: #6E8192;
  stroke-width: 2;
}

.apexcharts-pan-icon.apexcharts-selected svg {
  stroke: #008FFB;
}

.apexcharts-pan-icon:not(.apexcharts-selected):hover svg {
  stroke: #333;
}

.apexcharts-toolbar {
  position: absolute;
  z-index: 11;
  max-width: 176px;
  text-align: right;
  border-radius: 3px;
  padding: 0px 6px 2px 6px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.apexcharts-menu {
  background: #fff;
  position: absolute;
  top: 100%;
  border: 1px solid #ddd;
  border-radius: 3px;
  padding: 3px;
  right: 10px;
  opacity: 0;
  min-width: 110px;
  transition: 0.15s ease all;
  pointer-events: none;
}

.apexcharts-menu.apexcharts-menu-open {
  opacity: 1;
  pointer-events: all;
  transition: 0.15s ease all;
}

.apexcharts-menu-item {
  padding: 6px 7px;
  font-size: 12px;
  cursor: pointer;
}

.apexcharts-theme-light .apexcharts-menu-item:hover {
  background: #eee;
}

.apexcharts-theme-dark .apexcharts-menu {
  background: rgba(0, 0, 0, 0.7);
  color: #fff;
}

@media screen and (min-width: 768px) {
  .apexcharts-canvas:hover .apexcharts-toolbar {
    opacity: 1;
  }
}

.apexcharts-datalabel.apexcharts-element-hidden {
  opacity: 0;
}

.apexcharts-pie-label,
.apexcharts-datalabels,
.apexcharts-datalabel,
.apexcharts-datalabel-label,
.apexcharts-datalabel-value {
  cursor: default;
  pointer-events: none;
}

.apexcharts-pie-label-delay {
  opacity: 0;
  animation-name: opaque;
  animation-duration: 0.3s;
  animation-fill-mode: forwards;
  animation-timing-function: ease;
}

.apexcharts-canvas .apexcharts-element-hidden {
  opacity: 0;
}

.apexcharts-hide .apexcharts-series-points {
  opacity: 0;
}

.apexcharts-gridline,
.apexcharts-annotation-rect,
.apexcharts-tooltip .apexcharts-marker,
.apexcharts-area-series .apexcharts-area,
.apexcharts-line,
.apexcharts-zoom-rect,
.apexcharts-toolbar svg,
.apexcharts-area-series .apexcharts-series-markers .apexcharts-marker.no-pointer-events,
.apexcharts-line-series .apexcharts-series-markers .apexcharts-marker.no-pointer-events,
.apexcharts-radar-series path,
.apexcharts-radar-series polygon {
  pointer-events: none;
}


/* markers */

.apexcharts-marker {
  transition: 0.15s ease all;
}

@keyframes opaque {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}


/* Resize generated styles */

@keyframes resizeanim {
  from {
    opacity: 0;
  }
  to {
    opacity: 0;
  }
}

.resize-triggers {
  animation: 1ms resizeanim;
  visibility: hidden;
  opacity: 0;
}

.resize-triggers,
.resize-triggers>div,
.contract-trigger:before {
  content: " ";
  display: block;
  position: absolute;
  top: 0;
  left: 0;
  height: 100%;
  width: 100%;
  overflow: hidden;
}

.resize-triggers>div {
  background: #eee;
  overflow: auto;
}

.contract-trigger:before {
  width: 200%;
  height: 200%;
}
 
.MuiTypography-root {
color: #121828;
margin: 0;
}
.MuiTypography-body2 {
color: #37474f;
font-size: 12px;
font-family: "Roboto", "Helvetica", "Arial", sans-serif;
font-weight: 400;
line-height: 18px;
letter-spacing: -0.04px;
}
.MuiTypography-body1 {
color: #121828;
font-size: 14px;
font-family: "Roboto", "Helvetica", "Arial", sans-serif;
font-weight: 400;
line-height: 21px;
letter-spacing: -0.05px;
}
.MuiTypography-caption {
color: #37474f;
font-size: 11px;
font-family: "Roboto", "Helvetica", "Arial", sans-serif;
font-weight: 400;
line-height: 13px;
letter-spacing: 0.33px;
}
.MuiTypography-button {
color: #121828;
font-size: 14px;
font-family: "Roboto", "Helvetica", "Arial", sans-serif;
font-weight: 500;
line-height: 1.75;
letter-spacing: 0.02857em;
text-transform: uppercase;
}
.MuiTypography-h1 {
color: #121828;
font-size: 35px;
font-family: "Roboto", "Helvetica", "Arial", sans-serif;
font-weight: 500;
line-height: 40px;
letter-spacing: -0.24px;
}
.MuiTypography-h2 {
color: #121828;
font-size: 29px;
font-family: "Roboto", "Helvetica", "Arial", sans-serif;
font-weight: 500;
line-height: 32px;
letter-spacing: -0.24px;
}
.MuiTypography-h3 {
color: #121828;
font-size: 24px;
font-family: "Roboto", "Helvetica", "Arial", sans-serif;
font-weight: 500;
line-height: 28px;
letter-spacing: -0.06px;
}
.MuiTypography-h4 {
color: #121828;
font-size: 20px;
font-family: "Roboto", "Helvetica", "Arial", sans-serif;
font-weight: 500;
line-height: 24px;
letter-spacing: -0.06px;
}
.MuiTypography-h5 {
color: #121828;
font-size: 16px;
font-family: "Roboto", "Helvetica", "Arial", sans-serif;
font-weight: 500;
line-height: 20px;
letter-spacing: -0.05px;
}
.MuiTypography-h6 {
color: #121828;
font-size: 14px;
font-family: "Roboto", "Helvetica", "Arial", sans-serif;
font-weight: 500;
line-height: 20px;
letter-spacing: -0.05px;
}
.MuiTypography-subtitle1 {
color: #121828;
font-size: 16px;
font-family: "Roboto", "Helvetica", "Arial", sans-serif;
font-weight: 400;
line-height: 25px;
letter-spacing: -0.05px;
}
.MuiTypography-subtitle2 {
color: #37474f;
font-size: 14px;
font-family: "Roboto", "Helvetica", "Arial", sans-serif;
font-weight: 400;
line-height: 21px;
letter-spacing: -0.05px;
}
.MuiTypography-overline {
color: #37474f;
font-size: 11px;
font-family: "Roboto", "Helvetica", "Arial", sans-serif;
font-weight: 500;
line-height: 13px;
letter-spacing: 0.33px;
text-transform: uppercase;
}
.MuiTypography-srOnly {
width: 1px;
height: 1px;
overflow: hidden;
position: absolute;
}
.MuiTypography-alignLeft {
text-align: left;
}
.MuiTypography-alignCenter {
text-align: center;
}
.MuiTypography-alignRight {
text-align: right;
}
.MuiTypography-alignJustify {
text-align: justify;
}
.MuiTypography-noWrap {
overflow: hidden;
white-space: nowrap;
text-overflow: ellipsis;
}
.MuiTypography-gutterBottom {
margin-bottom: 8px;
}
.MuiTypography-paragraph {
margin-bottom: 16px;
}
.MuiTypography-colorInherit {
color: inherit;
}
.MuiTypography-colorPrimary {
color: #1ED760;
}
.MuiTypography-colorSecondary {
color: #FFF;
}
.MuiTypography-colorTextPrimary {
color: #121828;
}
.MuiTypography-colorTextSecondary {
color: #37474f;
}
.MuiTypography-colorError {
color: #e53935;
}
.MuiTypography-displayInline {
display: inline;
}
.MuiTypography-displayBlock {
display: block;
}
 
.MuiSvgIcon-root {
fill: currentColor;
width: 1em;
height: 1em;
display: inline-block;
font-size: 1.5rem;
transition: fill 200ms cubic-bezier(0.4, 0, 0.2, 1) 0ms;
flex-shrink: 0;
user-select: none;
}
.MuiSvgIcon-colorPrimary {
color: #1ED760;
}
.MuiSvgIcon-colorSecondary {
color: #FFF;
}
.MuiSvgIcon-colorAction {
color: rgba(0, 0, 0, 0.54);
}
.MuiSvgIcon-colorError {
color: #e53935;
}
.MuiSvgIcon-colorDisabled {
color: rgba(0, 0, 0, 0.26);
}
.MuiSvgIcon-fontSizeInherit {
font-size: inherit;
}
.MuiSvgIcon-fontSizeSmall {
font-size: 1.25rem;
}
.MuiSvgIcon-fontSizeLarge {
font-size: 2.1875rem;
}
 
.MuiTouchRipple-root {
top: 0;
left: 0;
right: 0;
bottom: 0;
z-index: 0;
overflow: hidden;
position: absolute;
border-radius: inherit;
pointer-events: none;
}
.MuiTouchRipple-ripple {
opacity: 0;
position: absolute;
}
.MuiTouchRipple-rippleVisible {
opacity: 0.3;
animation: MuiTouchRipple-keyframes-enter 550ms cubic-bezier(0.4, 0, 0.2, 1);
transform: scale(1);
}
.MuiTouchRipple-ripplePulsate {
animation-duration: 200ms;
}
.MuiTouchRipple-child {
width: 100%;
height: 100%;
display: block;
opacity: 1;
border-radius: 50%;
background-color: currentColor;
}
.MuiTouchRipple-childLeaving {
opacity: 0;
animation: MuiTouchRipple-keyframes-exit 550ms cubic-bezier(0.4, 0, 0.2, 1);
}
.MuiTouchRipple-childPulsate {
top: 0;
left: 0;
position: absolute;
animation: MuiTouchRipple-keyframes-pulsate 2500ms cubic-bezier(0.4, 0, 0.2, 1) 200ms infinite;
}
@-webkit-keyframes MuiTouchRipple-keyframes-enter {
0% {
opacity: 0.1;
transform: scale(0);
}
100% {
opacity: 0.3;
transform: scale(1);
}
}
@-webkit-keyframes MuiTouchRipple-keyframes-exit {
0% {
opacity: 1;
}
100% {
opacity: 0;
}
}
@-webkit-keyframes MuiTouchRipple-keyframes-pulsate {
0% {
transform: scale(1);
}
50% {
transform: scale(0.92);
}
100% {
transform: scale(1);
}
}
 .MuiButtonBase-root {
color: inherit;
border: 0;
cursor: pointer;
margin: 0;
display: inline-flex;
outline: 0;
padding: 0;
position: relative;
align-items: center;
user-select: none;
border-radius: 0;
vertical-align: middle;
-moz-appearance: none;
justify-content: center;
text-decoration: none;
background-color: transparent;
-webkit-appearance: none;
-webkit-tap-highlight-color: transparent;
}
.MuiButtonBase-root::-moz-focus-inner {
border-style: none;
}
.MuiButtonBase-root.Mui-disabled {
cursor: default;
pointer-events: none;
}
@media print {
.MuiButtonBase-root {
-webkit-print-color-adjust: exact;
}
}
 @media (max-width:1279.95px) {
.jss109 {
font-size: 28px;
}
}
 .MuiPaper-root {
color: #121828;
transition: box-shadow 300ms cubic-bezier(0.4, 0, 0.2, 1) 0ms;
background-color: #FFFFFF;
}
.MuiPaper-rounded {
border-radius: 4px;
}
.MuiPaper-outlined {
border: 1px solid #eeeeee;
}
.MuiPaper-elevation0 {
box-shadow: none;
}
.MuiPaper-elevation1 {
box-shadow: none !important;;
}
.MuiPaper-elevation2 {
box-shadow: 0px 3px 1px -2px rgba(0,0,0,0.2),0px 2px 2px 0px rgba(0,0,0,0.14),0px 1px 5px 0px rgba(0,0,0,0.12);
}
.MuiPaper-elevation3 {
box-shadow: 0px 3px 3px -2px rgba(0,0,0,0.2),0px 3px 4px 0px rgba(0,0,0,0.14),0px 1px 8px 0px rgba(0,0,0,0.12);
}
.MuiPaper-elevation4 {
box-shadow: 0px 2px 4px -1px rgba(0,0,0,0.2),0px 4px 5px 0px rgba(0,0,0,0.14),0px 1px 10px 0px rgba(0,0,0,0.12);
}
.MuiPaper-elevation5 {
box-shadow: 0px 3px 5px -1px rgba(0,0,0,0.2),0px 5px 8px 0px rgba(0,0,0,0.14),0px 1px 14px 0px rgba(0,0,0,0.12);
}
.MuiPaper-elevation6 {
box-shadow: 0px 3px 5px -1px rgba(0,0,0,0.2),0px 6px 10px 0px rgba(0,0,0,0.14),0px 1px 18px 0px rgba(0,0,0,0.12);
}
.MuiPaper-elevation7 {
box-shadow: 0px 4px 5px -2px rgba(0,0,0,0.2),0px 7px 10px 1px rgba(0,0,0,0.14),0px 2px 16px 1px rgba(0,0,0,0.12);
}
.MuiPaper-elevation8 {
box-shadow: 0px 5px 5px -3px rgba(0,0,0,0.2),0px 8px 10px 1px rgba(0,0,0,0.14),0px 3px 14px 2px rgba(0,0,0,0.12);
}
.MuiPaper-elevation9 {
box-shadow: 0px 5px 6px -3px rgba(0,0,0,0.2),0px 9px 12px 1px rgba(0,0,0,0.14),0px 3px 16px 2px rgba(0,0,0,0.12);
}
.MuiPaper-elevation10 {
box-shadow: 0px 6px 6px -3px rgba(0,0,0,0.2),0px 10px 14px 1px rgba(0,0,0,0.14),0px 4px 18px 3px rgba(0,0,0,0.12);
}
.MuiPaper-elevation11 {
box-shadow: 0px 6px 7px -4px rgba(0,0,0,0.2),0px 11px 15px 1px rgba(0,0,0,0.14),0px 4px 20px 3px rgba(0,0,0,0.12);
}
.MuiPaper-elevation12 {
box-shadow: 0px 7px 8px -4px rgba(0,0,0,0.2),0px 12px 17px 2px rgba(0,0,0,0.14),0px 5px 22px 4px rgba(0,0,0,0.12);
}
.MuiPaper-elevation13 {
box-shadow: 0px 7px 8px -4px rgba(0,0,0,0.2),0px 13px 19px 2px rgba(0,0,0,0.14),0px 5px 24px 4px rgba(0,0,0,0.12);
}
.MuiPaper-elevation14 {
box-shadow: 0px 7px 9px -4px rgba(0,0,0,0.2),0px 14px 21px 2px rgba(0,0,0,0.14),0px 5px 26px 4px rgba(0,0,0,0.12);
}
.MuiPaper-elevation15 {
box-shadow: 0px 8px 9px -5px rgba(0,0,0,0.2),0px 15px 22px 2px rgba(0,0,0,0.14),0px 6px 28px 5px rgba(0,0,0,0.12);
}
.MuiPaper-elevation16 {
box-shadow: 0px 8px 10px -5px rgba(0,0,0,0.2),0px 16px 24px 2px rgba(0,0,0,0.14),0px 6px 30px 5px rgba(0,0,0,0.12);
}
.MuiPaper-elevation17 {
box-shadow: 0px 8px 11px -5px rgba(0,0,0,0.2),0px 17px 26px 2px rgba(0,0,0,0.14),0px 6px 32px 5px rgba(0,0,0,0.12);
}
.MuiPaper-elevation18 {
box-shadow: 0px 9px 11px -5px rgba(0,0,0,0.2),0px 18px 28px 2px rgba(0,0,0,0.14),0px 7px 34px 6px rgba(0,0,0,0.12);
}
.MuiPaper-elevation19 {
box-shadow: 0px 9px 12px -6px rgba(0,0,0,0.2),0px 19px 29px 2px rgba(0,0,0,0.14),0px 7px 36px 6px rgba(0,0,0,0.12);
}
.MuiPaper-elevation20 {
box-shadow: 0px 10px 13px -6px rgba(0,0,0,0.2),0px 20px 31px 3px rgba(0,0,0,0.14),0px 8px 38px 7px rgba(0,0,0,0.12);
}
.MuiPaper-elevation21 {
box-shadow: 0px 10px 13px -6px rgba(0,0,0,0.2),0px 21px 33px 3px rgba(0,0,0,0.14),0px 8px 40px 7px rgba(0,0,0,0.12);
}
.MuiPaper-elevation22 {
box-shadow: 0px 10px 14px -6px rgba(0,0,0,0.2),0px 22px 35px 3px rgba(0,0,0,0.14),0px 8px 42px 7px rgba(0,0,0,0.12);
}
.MuiPaper-elevation23 {
box-shadow: 0px 11px 14px -7px rgba(0,0,0,0.2),0px 23px 36px 3px rgba(0,0,0,0.14),0px 9px 44px 8px rgba(0,0,0,0.12);
}
.MuiPaper-elevation24 {
box-shadow: 0px 11px 15px -7px rgba(0,0,0,0.2),0px 24px 38px 3px rgba(0,0,0,0.14),0px 9px 46px 8px rgba(0,0,0,0.12);
}
</style><style data-jss="" data-meta="MuiBox">
</style>

<style>
 .MuiList-root {
margin: 0;
padding: 0;
position: relative;
list-style: none;
}
.MuiList-padding {
padding-top: 8px;
padding-bottom: 8px;
}
.MuiList-subheader {
padding-top: 0;
}

.MuiListItem-root {
width: 100%;
display: flex;
position: relative;
box-sizing: border-box;
text-align: left;
align-items: center;
padding-top: 8px;
padding-bottom: 8px;
justify-content: flex-start;
text-decoration: none;
}
.MuiListItem-root.Mui-focusVisible {
background-color: rgba(0, 0, 0, 0.08);
}
.MuiListItem-root.Mui-selected, .MuiListItem-root.Mui-selected:hover {
background-color: rgba(0, 0, 0, 0.08);
}
.MuiListItem-root.Mui-disabled {
opacity: 0.5;
}
.MuiListItem-container {
position: relative;
}
.MuiListItem-dense {
padding-top: 4px;
padding-bottom: 4px;
}
.MuiListItem-alignItemsFlexStart {
align-items: flex-start;
}
.MuiListItem-divider {
border-bottom: 1px solid #eeeeee;
background-clip: padding-box;
}
.MuiListItem-gutters {
padding-left: 16px;
padding-right: 16px;
}
.MuiListItem-button {
transition: background-color 150ms cubic-bezier(0.4, 0, 0.2, 1) 0ms;
}
.MuiListItem-button:hover {
text-decoration: none;
background-color: rgba(0, 0, 0, 0.04);
}
@media (hover: none) {
.MuiListItem-button:hover {
background-color: transparent;
}
}
.MuiListItem-secondaryAction {
padding-right: 48px;
}
.MuiButton-root {
color: #121828;
padding: 6px 16px;
font-size: 14px;
min-width: 64px;
box-sizing: border-box;
transition: background-color 250ms cubic-bezier(0.4, 0, 0.2, 1) 0ms,box-shadow 250ms cubic-bezier(0.4, 0, 0.2, 1) 0ms,border 250ms cubic-bezier(0.4, 0, 0.2, 1) 0ms;
font-family: "Roboto", "Helvetica", "Arial", sans-serif;
font-weight: 500;
line-height: 1.75;
border-radius: 8px !important;
letter-spacing: 0.02857em;
text-transform: uppercase;
}
.MuiButton-root:hover {
text-decoration: none;
background-color: rgba(18, 24, 40, 0.04);
}
.MuiButton-root.Mui-disabled {
color: rgba(0, 0, 0, 0.26);
}
@media (hover: none) {
.MuiButton-root:hover {
background-color: transparent;
}
}
.MuiButton-root:hover.Mui-disabled {
background-color: transparent;
}
.MuiButton-label {
width: 100%;
display: inherit;
align-items: inherit;
justify-content: inherit;
}
.MuiButton-text {
padding: 6px 8px;
}
.MuiButton-textPrimary {
color: #1ED760;
}
.MuiButton-textPrimary:hover {
background-color: rgba(30, 215, 96, 0.04);
}
@media (hover: none) {
.MuiButton-textPrimary:hover {
background-color: transparent;
}
}
.MuiButton-textSecondary {
color: #FFF;
}
.MuiButton-textSecondary:hover {
background-color: rgba(255, 255, 255, 0.04);
}
@media (hover: none) {
.MuiButton-textSecondary:hover {
background-color: transparent;
}
}
.MuiButton-outlined {
border: 1px solid rgba(0, 0, 0, 0.23);
padding: 5px 15px;
}
.MuiButton-outlined.Mui-disabled {
border: 1px solid rgba(0, 0, 0, 0.12);
}
.MuiButton-outlinedPrimary {
color: #1ED760;
border: 1px solid rgba(30, 215, 96, 0.5);
}
.MuiButton-outlinedPrimary:hover {
border: 1px solid #1ED760;
background-color: rgba(30, 215, 96, 0.04);
}
@media (hover: none) {
.MuiButton-outlinedPrimary:hover {
background-color: transparent;
}
}
.MuiButton-outlinedSecondary {
color: #FFF;
border: 1px solid rgba(255, 255, 255, 0.5);
}
.MuiButton-outlinedSecondary:hover {
border: 1px solid #FFF;
background-color: rgba(255, 255, 255, 0.04);
}
.MuiButton-outlinedSecondary.Mui-disabled {
border: 1px solid rgba(0, 0, 0, 0.26);
}
@media (hover: none) {
.MuiButton-outlinedSecondary:hover {
background-color: transparent;
}
}
.MuiButton-contained {
color: rgba(0, 0, 0, 0.87);
box-shadow: 0 1px 1px 0 rgba(0,0,0,0.14), 0 2px 1px -1px rgba(0,0,0,0.12), 0 1px 3px 0 rgba(0,0,0,0.20);
background-color: #e0e0e0;
}
.MuiButton-contained:hover {
box-shadow: 0px 2px 4px -1px rgba(0,0,0,0.2),0px 4px 5px 0px rgba(0,0,0,0.14),0px 1px 10px 0px rgba(0,0,0,0.12);
background-color: #d5d5d5;
}
.MuiButton-contained.Mui-focusVisible {
box-shadow: 0px 3px 5px -1px rgba(0,0,0,0.2),0px 6px 10px 0px rgba(0,0,0,0.14),0px 1px 18px 0px rgba(0,0,0,0.12);
}
.MuiButton-contained:active {
box-shadow: 0px 5px 5px -3px rgba(0,0,0,0.2),0px 8px 10px 1px rgba(0,0,0,0.14),0px 3px 14px 2px rgba(0,0,0,0.12);
}
.MuiButton-contained.Mui-disabled {
color: rgba(0, 0, 0, 0.26);
box-shadow: none;
background-color: rgba(0, 0, 0, 0.12);
}
@media (hover: none) {
.MuiButton-contained:hover {
box-shadow: 0px 3px 1px -2px rgba(0,0,0,0.2),0px 2px 2px 0px rgba(0,0,0,0.14),0px 1px 5px 0px rgba(0,0,0,0.12);
background-color: #e0e0e0;
}
}
.MuiButton-contained:hover.Mui-disabled {
background-color: rgba(0, 0, 0, 0.12);
}
.MuiButton-containedPrimary {
color: #FFFFFF;
background-color: #1ED760;
}
.MuiButton-containedPrimary:hover {
background-color: #111827;
}
@media (hover: none) {
.MuiButton-containedPrimary:hover {
background-color: #1ED760;
}
}
.MuiButton-containedSecondary {
color: #FFFFFF;
background-color: #FFF;
}
.MuiButton-containedSecondary:hover {
background-color: #0b0f19;
}
@media (hover: none) {
.MuiButton-containedSecondary:hover {
background-color: #FFF;
}
}
.MuiButton-disableElevation {
box-shadow: none;
}
.MuiButton-disableElevation:hover {
box-shadow: none;
}
.MuiButton-disableElevation.Mui-focusVisible {
box-shadow: none;
}
.MuiButton-disableElevation:active {
box-shadow: none;
}
.MuiButton-disableElevation.Mui-disabled {
box-shadow: none;
}
.MuiButton-colorInherit {
color: inherit;
border-color: currentColor;
}
.MuiButton-textSizeSmall {
padding: 4px 5px;
font-size: 0.8125rem;
}
.MuiButton-textSizeLarge {
padding: 8px 11px;
font-size: 0.9375rem;
}
.MuiButton-outlinedSizeSmall {
padding: 3px 9px;
font-size: 0.8125rem;
}
.MuiButton-outlinedSizeLarge {
padding: 7px 21px;
font-size: 0.9375rem;
}
.MuiButton-containedSizeSmall {
padding: 4px 10px;
font-size: 0.8125rem;
}
.MuiButton-containedSizeLarge {
padding: 8px 22px;
font-size: 0.9375rem;
}
.MuiButton-fullWidth {
width: 100%;
}
.MuiButton-startIcon {
display: inherit;
margin-left: -4px;
margin-right: 8px;
}
.MuiButton-startIcon.MuiButton-iconSizeSmall {
margin-left: -2px;
}
.MuiButton-endIcon {
display: inherit;
margin-left: 8px;
margin-right: -4px;
}
.MuiButton-endIcon.MuiButton-iconSizeSmall {
margin-right: -2px;
}
.MuiButton-iconSizeSmall > _:first-child {
font-size: 18px;
}
.MuiButton-iconSizeMedium > _:first-child {
font-size: 20px;
}
.MuiButton-iconSizeLarge > _:first-child {
font-size: 22px;
}

.MuiAvatar-root {
width: 40px;
height: 40px;
display: flex;
overflow: hidden;
position: relative;
font-size: 1.25rem;
align-items: center;
flex-shrink: 0;
font-family: "Roboto", "Helvetica", "Arial", sans-serif;
line-height: 1;
user-select: none;
border-radius: 50%;
justify-content: center;
}
.MuiAvatar-colorDefault {
color: #f5f5f7;
background-color: #bdbdbd;
}
.MuiAvatar-rounded {
border-radius: 4px;
}
.MuiAvatar-square {
border-radius: 0;
}
.MuiAvatar-img {
color: transparent;
width: 100%;
height: 100%;
object-fit: cover;
text-align: center;
text-indent: 10000px;
}
.MuiAvatar-fallback {
width: 75%;
height: 75%;
}
.MuiListItemAvatar-root {
min-width: 56px;
flex-shrink: 0;
}
.MuiListItemAvatar-alignItemsFlexStart {
margin-top: 8px;
}
.MuiListItemText-root {
flex: 1 1 auto;
min-width: 0;
margin-top: 4px;
margin-bottom: 4px;
}
.MuiListItemText-multiline {
margin-top: 6px;
margin-bottom: 6px;
}
.MuiListItemText-inset {
padding-left: 56px;
}
.jss128 {
color: rgb(255, 255, 255);
width: 40px;
height: 40px;
display: flex;
overflow: hidden;
position: relative;
font-size: 14px;
align-items: center;
flex-shrink: 0;
font-weight: 600;
line-height: 1;
user-select: none;
border-radius: 8px;
letter-spacing: 0px;
justify-content: center;
-webkit-box-pack: center;
background-color: transparent;
-webkit-box-align: center;
}
.jss129 {
padding: 4px;
animation: pulse-red 2s infinite;
box-shadow: 0 0 0 0 rgba(255, 82, 82, 1);
border-radius: 50%;
}
.jss130 {
width: 12px;
height: 12px;
margin: 0;
display: block;
border-radius: 50%;
background-color: rgb(209, 67, 67);
}
.MuiGrid-container {
width: 100%;
display: flex;
flex-wrap: wrap;
box-sizing: border-box;
}
.MuiGrid-item {
margin: 0;
box-sizing: border-box;
}
.MuiGrid-zeroMinWidth {
min-width: 0;
}
.MuiGrid-direction-xs-column {
flex-direction: column;
}
.MuiGrid-direction-xs-column-reverse {
flex-direction: column-reverse;
}
.MuiGrid-direction-xs-row-reverse {
flex-direction: row-reverse;
}
.MuiGrid-wrap-xs-nowrap {
flex-wrap: nowrap;
}
.MuiGrid-wrap-xs-wrap-reverse {
flex-wrap: wrap-reverse;
}
.MuiGrid-align-items-xs-center {
align-items: center;
}
.MuiGrid-align-items-xs-flex-start {
align-items: flex-start;
}
.MuiGrid-align-items-xs-flex-end {
align-items: flex-end;
}
.MuiGrid-align-items-xs-baseline {
align-items: baseline;
}
.MuiGrid-align-content-xs-center {
align-content: center;
}
.MuiGrid-align-content-xs-flex-start {
align-content: flex-start;
}
.MuiGrid-align-content-xs-flex-end {
align-content: flex-end;
}
.MuiGrid-align-content-xs-space-between {
align-content: space-between;
}
.MuiGrid-align-content-xs-space-around {
align-content: space-around;
}
.MuiGrid-justify-content-xs-center {
justify-content: center;
}
.MuiGrid-justify-content-xs-flex-end {
justify-content: flex-end;
}
.MuiGrid-justify-content-xs-space-between {
justify-content: space-between;
}
.MuiGrid-justify-content-xs-space-around {
justify-content: space-around;
}
.MuiGrid-justify-content-xs-space-evenly {
justify-content: space-evenly;
}
.MuiGrid-spacing-xs-1 {
width: calc(100% + 8px);
margin: -4px;
}
.MuiGrid-spacing-xs-1 > .MuiGrid-item {
padding: 4px;
}
.MuiGrid-spacing-xs-2 {
width: calc(100% + 16px);
margin: -8px;
}
.MuiGrid-spacing-xs-2 > .MuiGrid-item {
padding: 8px;
}
.MuiGrid-spacing-xs-3 {
width: calc(100% + 24px);
margin: -12px;
}
.MuiGrid-spacing-xs-3 > .MuiGrid-item {
padding: 12px;
}
.MuiGrid-spacing-xs-4 {
width: calc(100% + 32px);
margin: -16px;
}
.MuiGrid-spacing-xs-4 > .MuiGrid-item {
padding: 16px;
}
.MuiGrid-spacing-xs-5 {
width: calc(100% + 40px);
margin: -20px;
}
.MuiGrid-spacing-xs-5 > .MuiGrid-item {
padding: 20px;
}
.MuiGrid-spacing-xs-6 {
width: calc(100% + 48px);
margin: -24px;
}
.MuiGrid-spacing-xs-6 > .MuiGrid-item {
padding: 24px;
}
.MuiGrid-spacing-xs-7 {
width: calc(100% + 56px);
margin: -28px;
}
.MuiGrid-spacing-xs-7 > .MuiGrid-item {
padding: 28px;
}
.MuiGrid-spacing-xs-8 {
width: calc(100% + 64px);
margin: -32px;
}
.MuiGrid-spacing-xs-8 > .MuiGrid-item {
padding: 32px;
}
.MuiGrid-spacing-xs-9 {
width: calc(100% + 72px);
margin: -36px;
}
.MuiGrid-spacing-xs-9 > .MuiGrid-item {
padding: 36px;
}
.MuiGrid-spacing-xs-10 {
width: calc(100% + 80px);
margin: -40px;
}
.MuiGrid-spacing-xs-10 > .MuiGrid-item {
padding: 40px;
}
.MuiGrid-grid-xs-auto {
flex-grow: 0;
max-width: none;
flex-basis: auto;
}
.MuiGrid-grid-xs-true {
flex-grow: 1;
max-width: 100%;
flex-basis: 0;
}
.MuiGrid-grid-xs-1 {
flex-grow: 0;
max-width: 8.333333%;
flex-basis: 8.333333%;
}
.MuiGrid-grid-xs-2 {
flex-grow: 0;
max-width: 16.666667%;
flex-basis: 16.666667%;
}
.MuiGrid-grid-xs-3 {
flex-grow: 0;
max-width: 25%;
flex-basis: 25%;
}
.MuiGrid-grid-xs-4 {
flex-grow: 0;
max-width: 33.333333%;
flex-basis: 33.333333%;
}
.MuiGrid-grid-xs-5 {
flex-grow: 0;
max-width: 41.666667%;
flex-basis: 41.666667%;
}
.MuiGrid-grid-xs-6 {
flex-grow: 0;
max-width: 50%;
flex-basis: 50%;
}
.MuiGrid-grid-xs-7 {
flex-grow: 0;
max-width: 58.333333%;
flex-basis: 58.333333%;
}
.MuiGrid-grid-xs-8 {
flex-grow: 0;
max-width: 66.666667%;
flex-basis: 66.666667%;
}
.MuiGrid-grid-xs-9 {
flex-grow: 0;
max-width: 75%;
flex-basis: 75%;
}
.MuiGrid-grid-xs-10 {
flex-grow: 0;
max-width: 83.333333%;
flex-basis: 83.333333%;
}
.MuiGrid-grid-xs-11 {
flex-grow: 0;
max-width: 91.666667%;
flex-basis: 91.666667%;
}
.MuiGrid-grid-xs-12 {
flex-grow: 0;
max-width: 100%;
flex-basis: 100%;
}
@media (min-width:600px) {
.MuiGrid-grid-sm-auto {
flex-grow: 0;
max-width: none;
flex-basis: auto;
}
.MuiGrid-grid-sm-true {
flex-grow: 1;
max-width: 100%;
flex-basis: 0;
}
.MuiGrid-grid-sm-1 {
flex-grow: 0;
max-width: 8.333333%;
flex-basis: 8.333333%;
}
.MuiGrid-grid-sm-2 {
flex-grow: 0;
max-width: 16.666667%;
flex-basis: 16.666667%;
}
.MuiGrid-grid-sm-3 {
flex-grow: 0;
max-width: 25%;
flex-basis: 25%;
}
.MuiGrid-grid-sm-4 {
flex-grow: 0;
max-width: 33.333333%;
flex-basis: 33.333333%;
}
.MuiGrid-grid-sm-5 {
flex-grow: 0;
max-width: 41.666667%;
flex-basis: 41.666667%;
}
.MuiGrid-grid-sm-6 {
flex-grow: 0;
max-width: 50%;
flex-basis: 50%;
}
.MuiGrid-grid-sm-7 {
flex-grow: 0;
max-width: 58.333333%;
flex-basis: 58.333333%;
}
.MuiGrid-grid-sm-8 {
flex-grow: 0;
max-width: 66.666667%;
flex-basis: 66.666667%;
}
.MuiGrid-grid-sm-9 {
flex-grow: 0;
max-width: 75%;
flex-basis: 75%;
}
.MuiGrid-grid-sm-10 {
flex-grow: 0;
max-width: 83.333333%;
flex-basis: 83.333333%;
}
.MuiGrid-grid-sm-11 {
flex-grow: 0;
max-width: 91.666667%;
flex-basis: 91.666667%;
}
.MuiGrid-grid-sm-12 {
flex-grow: 0;
max-width: 100%;
flex-basis: 100%;
}
}
@media (min-width:960px) {
.MuiGrid-grid-md-auto {
flex-grow: 0;
max-width: none;
flex-basis: auto;
}
.MuiGrid-grid-md-true {
flex-grow: 1;
max-width: 100%;
flex-basis: 0;
}
.MuiGrid-grid-md-1 {
flex-grow: 0;
max-width: 8.333333%;
flex-basis: 8.333333%;
}
.MuiGrid-grid-md-2 {
flex-grow: 0;
max-width: 16.666667%;
flex-basis: 16.666667%;
}
.MuiGrid-grid-md-3 {
flex-grow: 0;
max-width: 25%;
flex-basis: 25%;
}
.MuiGrid-grid-md-4 {
flex-grow: 0;
max-width: 33.333333%;
flex-basis: 33.333333%;
}
.MuiGrid-grid-md-5 {
flex-grow: 0;
max-width: 41.666667%;
flex-basis: 41.666667%;
}
.MuiGrid-grid-md-6 {
flex-grow: 0;
max-width: 50%;
flex-basis: 50%;
}
.MuiGrid-grid-md-7 {
flex-grow: 0;
max-width: 58.333333%;
flex-basis: 58.333333%;
}
.MuiGrid-grid-md-8 {
flex-grow: 0;
max-width: 66.666667%;
flex-basis: 66.666667%;
}
.MuiGrid-grid-md-9 {
flex-grow: 0;
max-width: 75%;
flex-basis: 75%;
}
.MuiGrid-grid-md-10 {
flex-grow: 0;
max-width: 83.333333%;
flex-basis: 83.333333%;
}
.MuiGrid-grid-md-11 {
flex-grow: 0;
max-width: 91.666667%;
flex-basis: 91.666667%;
}
.MuiGrid-grid-md-12 {
flex-grow: 0;
max-width: 100%;
flex-basis: 100%;
}
}
@media (min-width:1280px) {
.MuiGrid-grid-lg-auto {
flex-grow: 0;
max-width: none;
flex-basis: auto;
}
.MuiGrid-grid-lg-true {
flex-grow: 1;
max-width: 100%;
flex-basis: 0;
}
.MuiGrid-grid-lg-1 {
flex-grow: 0;
max-width: 8.333333%;
flex-basis: 8.333333%;
}
.MuiGrid-grid-lg-2 {
flex-grow: 0;
max-width: 16.666667%;
flex-basis: 16.666667%;
}
.MuiGrid-grid-lg-3 {
flex-grow: 0;
max-width: 25%;
flex-basis: 25%;
}
.MuiGrid-grid-lg-4 {
flex-grow: 0;
max-width: 33.333333%;
flex-basis: 33.333333%;
}
.MuiGrid-grid-lg-5 {
flex-grow: 0;
max-width: 41.666667%;
flex-basis: 41.666667%;
}
.MuiGrid-grid-lg-6 {
flex-grow: 0;
max-width: 50%;
flex-basis: 50%;
}
.MuiGrid-grid-lg-7 {
flex-grow: 0;
max-width: 58.333333%;
flex-basis: 58.333333%;
}
.MuiGrid-grid-lg-8 {
flex-grow: 0;
max-width: 66.666667%;
flex-basis: 66.666667%;
}
.MuiGrid-grid-lg-9 {
flex-grow: 0;
max-width: 75%;
flex-basis: 75%;
}
.MuiGrid-grid-lg-10 {
flex-grow: 0;
max-width: 83.333333%;
flex-basis: 83.333333%;
}
.MuiGrid-grid-lg-11 {
flex-grow: 0;
max-width: 91.666667%;
flex-basis: 91.666667%;
}
.MuiGrid-grid-lg-12 {
flex-grow: 0;
max-width: 100%;
flex-basis: 100%;
}
}
@media (min-width:1920px) {
.MuiGrid-grid-xl-auto {
flex-grow: 0;
max-width: none;
flex-basis: auto;
}
.MuiGrid-grid-xl-true {
flex-grow: 1;
max-width: 100%;
flex-basis: 0;
}
.MuiGrid-grid-xl-1 {
flex-grow: 0;
max-width: 8.333333%;
flex-basis: 8.333333%;
}
.MuiGrid-grid-xl-2 {
flex-grow: 0;
max-width: 16.666667%;
flex-basis: 16.666667%;
}
.MuiGrid-grid-xl-3 {
flex-grow: 0;
max-width: 25%;
flex-basis: 25%;
}
.MuiGrid-grid-xl-4 {
flex-grow: 0;
max-width: 33.333333%;
flex-basis: 33.333333%;
}
.MuiGrid-grid-xl-5 {
flex-grow: 0;
max-width: 41.666667%;
flex-basis: 41.666667%;
}
.MuiGrid-grid-xl-6 {
flex-grow: 0;
max-width: 50%;
flex-basis: 50%;
}
.MuiGrid-grid-xl-7 {
flex-grow: 0;
max-width: 58.333333%;
flex-basis: 58.333333%;
}
.MuiGrid-grid-xl-8 {
flex-grow: 0;
max-width: 66.666667%;
flex-basis: 66.666667%;
}
.MuiGrid-grid-xl-9 {
flex-grow: 0;
max-width: 75%;
flex-basis: 75%;
}
.MuiGrid-grid-xl-10 {
flex-grow: 0;
max-width: 83.333333%;
flex-basis: 83.333333%;
}
.MuiGrid-grid-xl-11 {
flex-grow: 0;
max-width: 91.666667%;
flex-basis: 91.666667%;
}
.MuiGrid-grid-xl-12 {
flex-grow: 0;
max-width: 100%;
flex-basis: 100%;
}
}
.jss142 {
position: relative;
}
.MuiCardContent-root {
padding: 24px;
}
.MuiCardContent-root:last-child {
padding-bottom: 24px;
}
.jss143 {
height: 100%;
}
.jss144 {
padding: 0;
flex-grow: 1;
}
.MuiCard-root {
overflow: hidden;
}
.jss147 {
font-size: 16px;
text-transform: initial;
}
.jss145 {
color: rgb(18, 24, 40);
border: 0.1px solid #12182812;
display: flex;
padding: 24px;
box-shadow: rgb(100 116 139 / 6%) 0px 1px 1px, rgb(100 116 139 / 10%) 0px 1px 2px;
border-radius: 8px;
justify-content: center;
border-top-left-radius: 8px;
border-top-right-radius: 8px;
border-bottom-left-radius: 8px;
border-bottom-right-radius: 8px;
}
.jss146 {
padding-top: 32px;
}
.jss158 {
color: #1ED760;
height: 36px;
font-weight: 600;
}
.jss159 {
font-size: 14px;
padding-top: 3px;
}
.jss160 {
margin-left: 8px;
}
.MuiDrawer-docked {
flex: 0 0 auto;
}
.MuiDrawer-paper {
top: 0;
flex: 1 0 auto;
height: 100%;
display: flex;
outline: 0;
z-index: 1200;
position: fixed;
overflow-y: auto;
flex-direction: column;
-webkit-overflow-scrolling: touch;
}
.MuiDrawer-paperAnchorLeft {
left: 0;
right: auto;
}
.MuiDrawer-paperAnchorRight {
left: auto;
right: 0;
}
.MuiDrawer-paperAnchorTop {
top: 0;
left: 0;
right: 0;
bottom: auto;
height: auto;
max-height: 100%;
}
.MuiDrawer-paperAnchorBottom {
top: auto;
left: 0;
right: 0;
bottom: 0;
height: auto;
max-height: 100%;
}
.MuiDrawer-paperAnchorDockedLeft {
border-right: 1px solid #eeeeee;
}
.MuiDrawer-paperAnchorDockedTop {
border-bottom: 1px solid #eeeeee;
}
.MuiDrawer-paperAnchorDockedRight {
border-left: 1px solid #eeeeee;
}
.MuiDrawer-paperAnchorDockedBottom {
border-top: 1px solid #eeeeee;
}
.MuiFab-root {
color: rgba(0, 0, 0, 0.87);
width: 56px;
height: 56px;
padding: 0;
font-size: 14px;
min-width: 0;
box-shadow: 0px 3px 5px -1px rgba(0,0,0,0.2),0px 6px 10px 0px rgba(0,0,0,0.14),0px 1px 18px 0px rgba(0,0,0,0.12);
box-sizing: border-box;
min-height: 36px;
transition: background-color 250ms cubic-bezier(0.4, 0, 0.2, 1) 0ms,box-shadow 250ms cubic-bezier(0.4, 0, 0.2, 1) 0ms,border 250ms cubic-bezier(0.4, 0, 0.2, 1) 0ms;
font-family: "Roboto", "Helvetica", "Arial", sans-serif;
font-weight: 500;
line-height: 1.75;
border-radius: 50%;
letter-spacing: 0.02857em;
text-transform: uppercase;
background-color: #e0e0e0;
}
.MuiFab-root:active {
box-shadow: 0px 7px 8px -4px rgba(0,0,0,0.2),0px 12px 17px 2px rgba(0,0,0,0.14),0px 5px 22px 4px rgba(0,0,0,0.12);
}
.MuiFab-root:hover {
text-decoration: none;
background-color: #d5d5d5;
}
.MuiFab-root.Mui-focusVisible {
box-shadow: 0px 3px 5px -1px rgba(0,0,0,0.2),0px 6px 10px 0px rgba(0,0,0,0.14),0px 1px 18px 0px rgba(0,0,0,0.12);
}
.MuiFab-root.Mui-disabled {
color: rgba(0, 0, 0, 0.26);
box-shadow: none;
background-color: rgba(0, 0, 0, 0.12);
}
@media (hover: none) {
.MuiFab-root:hover {
background-color: #e0e0e0;
}
}
.MuiFab-root:hover.Mui-disabled {
background-color: rgba(0, 0, 0, 0.12);
}
.MuiFab-label {
width: 100%;
display: inherit;
align-items: inherit;
justify-content: inherit;
}
.MuiFab-primary {
color: #FFFFFF;
background-color: #1ED760;
}
.MuiFab-primary:hover {
background-color: #111827;
}
@media (hover: none) {
.MuiFab-primary:hover {
background-color: #1ED760;
}
}
.MuiFab-secondary {
color: #FFFFFF;
background-color: #FFF;
}
.MuiFab-secondary:hover {
background-color: #0b0f19;
}
@media (hover: none) {
.MuiFab-secondary:hover {
background-color: #FFF;
}
}
.MuiFab-extended {
width: auto;
height: 48px;
padding: 0 16px;
min-width: 48px;
min-height: auto;
border-radius: 24px;
}
.MuiFab-extended.MuiFab-sizeSmall {
width: auto;
height: 34px;
padding: 0 8px;
min-width: 34px;
border-radius: 17px;
}
.MuiFab-extended.MuiFab-sizeMedium {
width: auto;
height: 40px;
padding: 0 16px;
min-width: 40px;
border-radius: 20px;
}
.MuiFab-colorInherit {
color: inherit;
}
.MuiFab-sizeSmall {
width: 40px;
height: 40px;
}
.MuiFab-sizeMedium {
width: 48px;
height: 48px;
}
.jss29 {
right: 16px;
bottom: 16px;
position: fixed;
}
.jss29:hover {
background-color: #1ED760;
}
.jss3 {
height: 100%;
display: flex;
flex-direction: column;
}
.jss4 {
text-align: center;
font-weight: 600;
}
.jss5 {
width: 320px;
max-width: 100%;
}
.jss6 {
display: flex;
padding: 18.4px 24px;
background: #1ED760;
justify-content: space-between;
}
.jss7 {
color: #FFFFFF;
}
.jss8 {
color: #65748b;
margin: 0px 0px 8px;
font-size: 0.85rem;
font-weight: 600;
line-height: 2.5;
letter-spacing: 0.5px;
text-transform: uppercase;
}
.jss9 {
padding: 0;
min-width: 0;
}
.jss10 {
color: #FFFFFF;
margin-right: 8px;
}
.jss11 {
cursor: pointer;
margin: 8px;
padding: 8px;
overflow: hidden;
flex-grow: 1;
font-size: 0px;
border-color: #e6e8f0;
border-style: solid;
border-width: 2px;
border-radius: 8px;
-webkit-box-flex: 1;
}
.jss12 {
border-color: #1ED760;
}
.jss13 {
margin: -8px;
display: flex;
align-items: center;
-webkit-box-align: center;
}
.jss14 {
width: 100%;
height: auto;
}
.jss15 {
padding: 16px 28px;
flex-grow: 1;
}
.jss16 {
padding: 16px 0px;
}
.jss17 {
cursor: pointer;
display: flex;
justify-content: space-between;
}
.jss19 {
padding: 16px 0px;
}
.jss20 {
display: flex;
align-items: center;
}
.jss21 {
margin-top: 0;
margin-bottom: 0;
}
.jss22 {
flex-grow: 1;
}
.jss23 {
margin-left: 8px;
}
.jss24 {
margin-top: 8px;
}
.jss25 {
margin-right: 24px;
}
.jss26 {
margin-left: 24px;
}
.jss28 {
padding: 24px;
}
.jss28 > _ + _ {
margin-top: 16px;
}
html {
}
_, _::before, \_::after {
box-sizing: inherit;
}
body {
margin: 0;
font-size: 12px;
}
@media print {
body {
background-color: #fff;
}
}

.jss58 {
width: 100%;
display: flex;
padding: 8px;
}
.jss59 {
padding-right: 24px;
}
.jss60 {
display: flex;
padding: 0 8px;
min-height: 56px;
align-items: center;
justify-content: flex-end;
}
@media (min-width:0px) and (orientation: landscape) {
.jss60 {
min-height: 48px;
}
}
@media (min-width:600px) {
.jss60 {
min-height: 64px;
}
}
.jss61 {
color: white;
z-index: 1201;
position: fixed;
background: #1ED760;
box-shadow: none;
transition: width 195ms cubic-bezier(0.4, 0, 0.6, 1) 0ms,margin 195ms cubic-bezier(0.4, 0, 0.6, 1) 0ms;
padding-top: 8px;
padding-bottom: 8px;
}
.jss62 {
width: calc(100% - 270px + 50px);
transition: width 225ms cubic-bezier(0.4, 0, 0.6, 1) 0ms,margin 225ms cubic-bezier(0.4, 0, 0.6, 1) 0ms;
margin-left: calc(100% - 270px + 50px);
}
.jss63 {
display: none;
}
.jss64 {
width: calc(270px);
border: none;
z-index: 9;
position: relative;
margin-top: 130px !important;
transition: width 225ms cubic-bezier(0.4, 0, 0.6, 1) 0ms;
padding-top: 40px;
white-space: nowrap;
border-top-right-radius: 85px;
}
.jss65 {
width: 56px;
overflow-x: hidden;
transition: width 195ms cubic-bezier(0.4, 0, 0.6, 1) 0ms;
}
@media (min-width:600px) {
.jss65 {
width: 72px;
}
}
.jss66 {
width: 100%;
flex-grow: 1;
min-height: 100%;
padding-top: 52px;
padding-left: 255px;
}
@media (max-width:1279.95px) {
.jss66 {
padding-left: 15px;
padding-right: 15px;
}
}
.jss67 {
max-width: 100%;
padding-bottom: 32px;
justify-content: none;
}
@media (min-width:600px) {
.jss67 {
padding-left: 32px;
padding-right: 32px;
padding-bottom: 32px;
}
}
@media (min-width:1280px) {
.jss67 {
padding-left: 50px !important;;
padding-right: 30px !important;;
}
}
.jss68 {
display: flex;
padding: 16px;
flex-direction: column;
}
.jss69 {
height: 240px;
}
.jss70 {
color: #1ED760;
}
.jss70:hover {
color: #1ED760;
}
.jss71:hover {
color: #1ED760;
}
.jss72 {
width: 100%;
bottom: 0;
position: fixed;
text-align: center;
}
@media (max-width:959.95px) {
.jss72 {
display: block;
}
}
@media (min-width:960px) {
.jss72 {
display: none;
}
}
@media (min-width:1280px) {
.jss72 {
display: none;
}
}
@media (max-width:959.95px) {
.jss73 {
display: none;
}
}
@media (min-width:960px) {
.jss73 {
display: block;
}
}
@media (min-width:1280px) {
.jss73 {
display: block;
}
}
.jss74 {
background-color: #1ED760 !important;
}
.jss75 {
margin-right: 24px;
}
.jss76 {
font-size: 13px;
margin-left: 8px;
margin-right: 8px;
}
.jss77 {
width: 26px;
height: 26px;
margin-left: 10px;
margin-right: 4px;
}
.jss78 {
color: #1ED760;
display: flex;
}
.jss79 {
padding-left: 16px;
padding-right: 16px;
padding-bottom: 16px;
}
.jss80 {
width: 100%;
text-align: center;
}
.jss81 {
width: 100%;
font-size: 0.875rem;
text-align: center;
font-weight: 400;
line-height: 1.43;
letter-spacing: 0.01071em;
}
.jss82 {
color: white !important;
}
.jss83 {
padding: 16px;
}
.jss84 {
flex: 0 0 auto;
width: 256px;
z-index: 3;
min-width: 256px;
}
.jss85 {
width: 32px;
height: 32px;
}
.jss86 {
margin-left: 1px;
margin-right: 1px;
}
.jss87 {
color: inherit;
border: 0;
cursor: pointer;
margin: 0;
display: inline-flex;
outline: 0;
padding: 0;
position: relative;
align-iems: center;
user-select: none;
border-radius: 0;
vertical-align: middle;
justify-content: center;
text-decoration: none;
background-color: transparent;
}
.jss88 {
width: 100%;
padding: 8px;
}
.jss89 {
display: flex;
min-height: fit-content;
align-items: center;
flex-direction: column;
}
.jss90 {
width: 50px;
height: 50px;
border-radius: 10px !important;
}
.jss91 {
margin-top: 8px;
}
.jss92 {
margin-top: 16px;
}
.jss93 {
width: 100%;
margin-top: 16px;
}
.jss94 {
width: 275px !important;
border: none;
height: calc(100%);
position: fixed;
transition: width 225ms cubic-bezier(0.4, 0, 0.6, 1) 0ms;
padding-top: 56px;
white-space: nowrap;
justify-content: space-between;
}
.jss95 {
overflow-x: hidden;
transition: width 195ms cubic-bezier(0.4, 0, 0.6, 1) 0ms;
}
@media (min-width:600px) {
.jss95 {
width: 72px;
}
}
.jss96 {
line-height: 100px;
}
.jss97 {
background-color: transparent !important;
}
.jss98 {
margin-left: 0.5em;
}
.jss98 g {
opacity: xx;
}
.jss98 path {
fill: xxx;
}
.MuiContainer-root {
width: 100%;
display: block;
box-sizing: border-box;
margin-left: auto;
margin-right: auto;
padding-left: 16px;
padding-right: 16px;
}
@media (min-width:600px) {
.MuiContainer-root {
padding-left: 24px;
padding-right: 24px;
}
}
.MuiContainer-disableGutters {
padding-left: 0;
padding-right: 0;
}
@media (min-width:600px) {
.MuiContainer-fixed {
max-width: 600px;
}
}
@media (min-width:960px) {
.MuiContainer-fixed {
max-width: 960px;
}
}
@media (min-width:1280px) {
.MuiContainer-fixed {
max-width: 1280px;
}
}
@media (min-width:1920px) {
.MuiContainer-fixed {
max-width: 1920px;
}
}
@media (min-width:0px) {
.MuiContainer-maxWidthXs {
max-width: 444px;
}
}
@media (min-width:600px) {
.MuiContainer-maxWidthSm {
max-width: 600px;
}
}
@media (min-width:960px) {
.MuiContainer-maxWidthMd {
max-width: 960px;
}
}
@media (min-width:1280px) {
.MuiContainer-maxWidthLg {
max-width: 1280px;
}
}
@media (min-width:1920px) {
.MuiContainer-maxWidthXl {
max-width: 1920px;
}
}
.jss148 {
height: 100%;
}
.jss149 {
padding: 0;
flex-grow: 1;
}
.jss150 {
color: #FFFFFF;
font-size: 14px;
min-width: 0px !important;;
font-weight: 700;
}
.jss151 {
justify-content: flex-end;
}
.jss152 {
margin-left: 8px;
}
.jss153 {
color: #FFFFFF;
}
.jss154 {
display: -webkit-box;
overflow: hidden;
text-overflow: ellipsis;
-webkit-box-orient: vertical;
-webkit-line-clamp: 1;
}
.jss155 {
color: #9A9AA9;
}
.jss156 {
padding-top: 16px;
}
.jss157 {
padding-left: 16px;
padding-right: 16px;
}
.jss118 {
color: rgb(18, 24, 40);
border: 0.1px solid #12182812;
height: 100%;
padding: 22px;
box-shadow: rgb(100 116 139 / 6%) 0px 1px 1px, rgb(100 116 139 / 10%) 0px 1px 2px;
align-items: center;
border-radius: 8px;
border-top-left-radius: 8px;
border-top-right-radius: 8px;
border-bottom-left-radius: 8px;
border-bottom-right-radius: 8px;
}
.jss119 {
display: flex;
flex-wrap: wrap;
margin-top: 1em;
align-items: center;
}
.jss120 {
margin-left: 8px;
}
.jss121 {
width: 60px;
height: 60px;
background: #EFF4FF;
}
.jss122 {
font-size: 16px;
}
@media (max-width:1919.95px) {
.jss122 {
font-size: 14px;
}
}
.jss123 {
font-size: 26px;
font-weight: bold;
}
@media (max-width:1279.95px) {
.jss123 {
font-size: 20px;
}
}
.jss124 {
color: #1ED760;
width: 1.4em;
height: 2em;
border-radius: 20em !important;
}
.jss125 {
display: flex;
align-items: baseline;
margin-bottom: 8px;
-webkit-box-align: center;
}
.jss126 {
margin-left: 24px;
}
.MuiChip-root {
color: #263238;
border: none;
cursor: default;
height: 32px;
display: inline-flex;
outline: 0;
padding: 0;
font-size: 0.8125rem;
box-sizing: border-box;
transition: background-color 300ms cubic-bezier(0.4, 0, 0.2, 1) 0ms,box-shadow 300ms cubic-bezier(0.4, 0, 0.2, 1) 0ms;
align-items: center;
font-family: "Roboto", "Helvetica", "Arial", sans-serif;
white-space: nowrap;
border-radius: 16px;
vertical-align: middle;
justify-content: center;
text-decoration: none;
background-color: #eceff1;
}
.MuiChip-root.Mui-disabled {
opacity: 0.5;
pointer-events: none;
}
.MuiChip-root .MuiChip-avatar {
color: #616161;
width: 24px;
height: 24px;
font-size: 0.75rem;
margin-left: 5px;
margin-right: -6px;
}
.MuiChip-root .MuiChip-avatarColorPrimary {
color: #FFFFFF;
background-color: #111827;
}
.MuiChip-root .MuiChip-avatarColorSecondary {
color: #FFFFFF;
background-color: #0b0f19;
}
.MuiChip-root .MuiChip-avatarSmall {
width: 18px;
height: 18px;
font-size: 0.625rem;
margin-left: 4px;
margin-right: -4px;
}
.MuiChip-sizeSmall {
height: 24px;
}
.MuiChip-colorPrimary {
color: #FFFFFF;
background-color: #1ED760;
}
.MuiChip-colorSecondary {
color: #FFFFFF;
background-color: #FFF;
}
.MuiChip-clickable {
cursor: pointer;
user-select: none;
-webkit-tap-highlight-color: transparent;
}
.MuiChip-clickable:hover, .MuiChip-clickable:focus {
background-color: rgb(206, 206, 206);
}
.MuiChip-clickable:active {
box-shadow: 0px 2px 1px -1px rgba(0,0,0,0.2),0px 1px 1px 0px rgba(0,0,0,0.14),0px 1px 3px 0px rgba(0,0,0,0.12);
}
.MuiChip-clickableColorPrimary:hover, .MuiChip-clickableColorPrimary:focus {
background-color: rgb(48, 218, 108);
}
.MuiChip-clickableColorSecondary:hover, .MuiChip-clickableColorSecondary:focus {
background-color: rgb(234, 234, 234);
}
.MuiChip-deletable:focus {
background-color: #cfd8dc;
}
.MuiChip-deletableColorPrimary:focus {
background-color: rgb(75, 223, 127);
}
.MuiChip-deletableColorSecondary:focus {
background-color: rgb(204, 204, 204);
}
.MuiChip-outlined {
border: 1px solid rgba(0, 0, 0, 0.23);
background-color: transparent;
}
.MuiChip-clickable.MuiChip-outlined:hover, .MuiChip-clickable.MuiChip-outlined:focus, .MuiChip-deletable.MuiChip-outlined:focus {
background-color: rgba(18, 24, 40, 0.04);
}
.MuiChip-outlined .MuiChip-avatar {
margin-left: 4px;
}
.MuiChip-outlined .MuiChip-avatarSmall {
margin-left: 2px;
}
.MuiChip-outlined .MuiChip-icon {
margin-left: 4px;
}
.MuiChip-outlined .MuiChip-iconSmall {
margin-left: 2px;
}
.MuiChip-outlined .MuiChip-deleteIcon {
margin-right: 5px;
}
.MuiChip-outlined .MuiChip-deleteIconSmall {
margin-right: 3px;
}
.MuiChip-outlinedPrimary {
color: #1ED760;
border: 1px solid #1ED760;
}
.MuiChip-clickable.MuiChip-outlinedPrimary:hover, .MuiChip-clickable.MuiChip-outlinedPrimary:focus, .MuiChip-deletable.MuiChip-outlinedPrimary:focus {
background-color: rgba(30, 215, 96, 0.04);
}
.MuiChip-outlinedSecondary {
color: #FFF;
border: 1px solid #FFF;
}
.MuiChip-clickable.MuiChip-outlinedSecondary:hover, .MuiChip-clickable.MuiChip-outlinedSecondary:focus, .MuiChip-deletable.MuiChip-outlinedSecondary:focus {
background-color: rgba(255, 255, 255, 0.04);
}
.MuiChip-icon {
color: #616161;
margin-left: 5px;
margin-right: -6px;
}
.MuiChip-iconSmall {
width: 18px;
height: 18px;
margin-left: 4px;
margin-right: -4px;
}
.MuiChip-iconColorPrimary {
color: inherit;
}
.MuiChip-iconColorSecondary {
color: inherit;
}
.MuiChip-label {
overflow: hidden;
white-space: nowrap;
padding-left: 12px;
padding-right: 12px;
text-overflow: ellipsis;
}
.MuiChip-labelSmall {
padding-left: 8px;
padding-right: 8px;
}
.MuiChip-deleteIcon {
color: rgba(18, 24, 40, 0.26);
width: 22px;
cursor: pointer;
height: 22px;
margin: 0 5px 0 -6px;
-webkit-tap-highlight-color: transparent;
}
.MuiChip-deleteIcon:hover {
color: rgba(18, 24, 40, 0.4);
}
.MuiChip-deleteIconSmall {
width: 16px;
height: 16px;
margin-left: -4px;
margin-right: 4px;
}
.MuiChip-deleteIconColorPrimary {
color: rgba(255, 255, 255, 0.7);
}
.MuiChip-deleteIconColorPrimary:hover, .MuiChip-deleteIconColorPrimary:active {
color: #FFFFFF;
}
.MuiChip-deleteIconColorSecondary {
color: rgba(255, 255, 255, 0.7);
}
.MuiChip-deleteIconColorSecondary:hover, .MuiChip-deleteIconColorSecondary:active {
color: #FFFFFF;
}
.MuiChip-deleteIconOutlinedColorPrimary {
color: rgba(30, 215, 96, 0.7);
}
.MuiChip-deleteIconOutlinedColorPrimary:hover, .MuiChip-deleteIconOutlinedColorPrimary:active {
color: #1ED760;
}
.MuiChip-deleteIconOutlinedColorSecondary {
color: rgba(255, 255, 255, 0.7);
}
.MuiChip-deleteIconOutlinedColorSecondary:hover, .MuiChip-deleteIconOutlinedColorSecondary:active {
color: #FFF;
}
.jss110 {
display: flex;
padding: 30px;
align-items: center;
border-radius: 10px;
background-color: #5048E5;
}
@media (max-width:959.95px) {
.jss110 {
padding: 40px 60px;
}
}
@media (max-width:599.95px) {
.jss110 {
padding: 30px 40px;
}
}
.jss111 {
height: 200px;
padding-right: 20px;
}
@media (max-width:959.95px) {
.jss111 {
width: 100%;
}
}
.jss112 {
color: #fff;
font-size: 2rem;
font-weight: 500;
line-height: 30px;
margin-bottom: 10px;
}
.jss113 {
color: #1ED760;
}
.jss114 {
color: #fff;
font-size: 14px;
line-height: 19px;
}
@media (max-width:599.95px) {
.jss114 {
text-align: justify;
}
}
.jss115 {
width: auto;
height: 200px;
}
@media (max-width:959.95px) {
.jss115 {
margin: 0px auto;
display: block;
}
}
.jss116 {
color: white;
background: #10b981;
text-transform: initial;
}
.jss116:hover {
background: #0b815a;
}
.jss117 {
color: white;
font-size: 14px;
background: #10b981;
margin-bottom: 15px;
}
.jss136 {
display: flex;
padding: 24px;
align-items: center;
border-radius: 8px;
justify-content: center;
}
.jss138 {
display: flex;
justify-content: center;
}
.jss138 > _ {
margin-left: 8px;
}
.jss139 {
height: 375px;
min-width: 500px;
}
.jss140 {
height: 100%;
margin-top: 32px;
margin-bottom: 40px;
}
.jss141 {
font-size: 12px;
}
.jss101 {
width: 100%;
}
.jss102 {
margin-top: 24px;
}
.jss103 {
color: white;
float: right;
height: 36px;
padding: 1em 1em;
background: #1ED760;
margin-bottom: 1em;
text-transform: inherit;
}
.jss103:hover {
background: #1ED760;
}
.jss104 {
font-size: 2rem;
}
.jss105 {
border-radius: 8px;
}
.jss106 {
color: #d14343;
background-color: #d143431a;
}
.jss107 {
color: #ffb020;
background-color: #ffb0201a;
}
.jss108 {
color: #5048e5;
background-color: #5048e51a;
}
.jss99 {
width: 100%;
height: 53vh;
display: flex;
align-items: center;
justify-content: center;
}
.jss99 > _ + \* {
margin-top: 16px;
}
.jss100 {
width: 75%;
}
</style>

<div class="MuiGrid-root MuiGrid-item MuiGrid-grid-xs-12 MuiGrid-grid-sm-12 MuiGrid-grid-lg-12"><div class="MuiGrid-root jss110 MuiGrid-container">
<div class="MuiGrid-root" style="height: 200px">
  <div class="MuiChip-root jss117">
    <span class="MuiChip-label">
      <span style="top: -5px; position: relative;">Visitors</span> <img style="margin-top: 7px;" src="https://komarev.com/ghpvc/?username=isacarcanjo&style=&label=:" alt="isacarcanjo" />
    </span>
  </div>
  <h1 class="jss112">
    Somes  <strong class="jss113">Products</strong>
  </h1>
  <div style="display: flex; width: 100%; flex-direction: row;">
    <div style="width: 13%; margin: 15px;">
      <a href="https://dev-admin.meucarro.app/">
        <img src="https://dev-admin.meucarro.app/images/other/a5.svg" alt="Meucarro.app" width="100%"/>
      </a>
    </div>
    <div style="width: 13%; margin: 15px;">
      <a href="https://ia-kit-rvxyp.ondigitalocean.app/">
        <img src="https://dev-admin.meucarro.app/images/other/a1.svg" alt="Meucarro.app" width="100%"/>
      </a>
    </div>
    <div style="width: 13%; margin: 15px;">
      <a href="#">
        <img  src="https://dev-admin.meucarro.app/images/other/a2.svg" alt="Meucarro.app" width="100%"/>
      </a>
    </div>
    <div style="width: 13%; margin: 15px;">
      <a href="#">
        <img  src="https://dev-admin.meucarro.app/images/other/a3.svg" alt="Meucarro.app" width="100%"/>
      </a>
    </div>
    <div style="width: 13%; margin: 15px;">
      <a href="#">
        <img  src="https://dev-admin.meucarro.app/images/other/a4.svg" alt="Meucarro.app" width="100%"/>
      </a>
    </div>
    <div style="width: 13%; margin: 15px;">
      <a href="https://www.npmjs.com/package/@isacarcanjo/solid-create">
        <img  src="https://dev-admin.meucarro.app/images/other/a6.svg" alt="Meucarro.app" width="100%"/>
      </a>
    </div>
  </div>
  <!-- <p class="jss114"> </p>
    <br>
    </div> -->
  </div>
</div>
<br/>

<div style="display: flex; width: 100%; flex-direction: row;">

  <div style="width: 50%; padding-top: 8em">

  <h2>🔭I’m currently working on <a href="https://www.directvgo.com/br/home/">DirecTvGo</a></h2>
  <h2>🌱 I’m currently learning <b>the best technologies</b></h2>
  <h2>👯 I’m looking to collaborate on <b>News projects</b></h2>
  <h2>💬 Ask me about <b>react, python, microservice, mobile</b></h2>
  <div style="display: flex; width: 100%; flex-direction: row;">
  
  </div>
  </div>
  <div style="width: 50%">
    <img class="art" src="https://dev-admin.meucarro.app/images/other/art.svg" alt="Dev" width="100%"/>
  </div>
</div>
<br/>
<div style="">
  <a href="https://developer.android.com" target="_blank" rel="noreferrer"> <img class="bubbleG x1"  src="https://raw.githubusercontent.com/devicons/devicon/master/icons/android/android-original-wordmark.svg" alt="android" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img class="bubbleG x11" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> <a href="https://cordova.apache.org/" target="_blank" rel="noreferrer"> <img class="bubbleG x3" src="https://www.vectorlogo.zone/logos/apache_cordova/apache_cordova-icon.svg" alt="apachecordova" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img class="bubbleG x4" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a>

<a href="https://reactjs.org/" target="_blank" rel="noreferrer"> 
  <img class="bubbleG x10" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/>
</a> 
<a href="https://reactnative.dev/" target="_blank" rel="noreferrer"> 
  <img class="bubbleG x12" src="https://reactnative.dev/img/header_logo.svg" alt="reactnative" width="40" height="40"/>
</a> 
<a href="https://flutter.dev" target="_blank" rel="noreferrer"> 
  <img class="bubbleG x13" src="https://www.vectorlogo.zone/logos/flutterio/flutterio-icon.svg" alt="flutter" width="40" height="40"/>
</a> 
<a href="https://redis.io" target="_blank" rel="noreferrer"> 
  <img class="bubbleG x5" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redis/redis-original-wordmark.svg" alt="redis" width="40" height="40"/>
</a> 
<a href="https://golang.org" target="_blank" rel="noreferrer"> 
  <img class="bubbleG x6" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/go/go-original.svg" alt="go" width="40" height="40"/>
</a> 
<a href="https://kubernetes.io" target="_blank" rel="noreferrer"> 
  <img class="bubbleG x7" src="https://www.vectorlogo.zone/logos/kubernetes/kubernetes-icon.svg" alt="kubernetes" width="40" height="40"/>
</a>

<a href="https://nodejs.org" target="_blank" rel="noreferrer"> 
  <img class="bubbleG x8" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/>
</a> 
<a href="https://www.typescriptlang.org/" target="_blank" rel="noreferrer"> 
  <img class="bubbleG x9" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="typescript" width="40" height="40"/>
</a>
</div>
