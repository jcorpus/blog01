---
layout:     post
title:      "Historia de las Redes Neuronales "
subtitle:   "Las redes neuronales a travez del tiempo."
date:       2017-07-26 13:32:00
author:     "jcorpus"
header-img: "img/redes_neuronales/artifi-cogn.jpg"
---
<style>
.timeline {
  width: 100%;
  position: relative;
  padding: 1px 0;
  list-style: none;
  font-weight: 300;
}
.timeline .timeline-item {
  padding-left: 0;
  padding-right: 30px;
}
.timeline .timeline-item.timeline-item-right,
.timeline .timeline-item:nth-of-type(even):not(.timeline-item-left) {
  padding-left: 30px;
  padding-right: 0;
}
.timeline .timeline-item .timeline-event {
  width: 100%;
}
.timeline:before {
  border-right-style: solid;
}
.timeline:before,
.timeline:after {
  content: " ";
  display: block;
}
.timeline:after {
  clear: both;
}
.timeline:before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  width: 50%;
  height: 100% !important;
  margin-left: 1px;
  border-right-width: 2px;
  border-right-style: solid;
  border-right-color: #888888;
}
.timeline.timeline-single-column.timeline {
  width: 100%;
  max-width: 768px;
}
.timeline.timeline-single-column.timeline .timeline-item {
  padding-left: 72px;
  padding-right: 0;
}
.timeline.timeline-single-column.timeline .timeline-item.timeline-item-right,
.timeline.timeline-single-column.timeline .timeline-item:nth-of-type(even):not(.timeline-item-left) {
  padding-left: 72px;
  padding-right: 0;
}
.timeline.timeline-single-column.timeline .timeline-item .timeline-event {
  width: 100%;
}
.timeline.timeline-single-column.timeline:before {
  left: 42px;
  width: 0;
  margin-left: -1px;
}
.timeline.timeline-single-column.timeline .timeline-item {
  width: 100%;
  margin-bottom: 20px;
}
.timeline.timeline-single-column.timeline .timeline-item:nth-of-type(even) {
  margin-top: 0;
}
.timeline.timeline-single-column.timeline .timeline-item > .timeline-event {
  float: right !important;
}
.timeline.timeline-single-column.timeline .timeline-item > .timeline-event:before,
.timeline.timeline-single-column.timeline .timeline-item > .timeline-event:after {
  right: auto !important;
  border-left-width: 0 !important;
}
.timeline.timeline-single-column.timeline .timeline-item > .timeline-event:before {
  left: -15px !important;
  border-right-width: 15px !important;
}
.timeline.timeline-single-column.timeline .timeline-item > .timeline-event:after {
  left: -14px !important;
  border-right-width: 14px !important;
}
.timeline.timeline-single-column.timeline .timeline-item > .timeline-point {
  transform: translateX(-50%);
  left: 42px !important;
  margin-left: 0;
}
.timeline.timeline-single-column.timeline .timeline-label {
  transform: translateX(-50%);
  margin: 0 0 20px 42px;
}
.timeline.timeline-single-column.timeline .timeline-label + .timeline-item + .timeline-item {
  margin-top: 0;
}
.timeline.timeline-line-solid:before {
  border-right-style: solid;
}
.timeline.timeline-line-dotted:before {
  border-right-style: dotted;
}
.timeline.timeline-line-dashed:before {
  border-right-style: dashed;
}
.timeline .timeline-item {
  position: relative;
  float: left;
  clear: left;
  width: 50%;
  margin-bottom: 20px;
}
.timeline .timeline-item:before,
.timeline .timeline-item:after {
  content: "";
  display: table;
}
.timeline .timeline-item:after {
  clear: both;
}
.timeline .timeline-item:last-child {
  margin-bottom: 0 !important;
}
.timeline .timeline-item.timeline-item-right > .timeline-event,
.timeline .timeline-item:nth-of-type(even):not(.timeline-item-left) > .timeline-event {
  float: right !important;
}
.timeline .timeline-item.timeline-item-right > .timeline-event:before,
.timeline .timeline-item:nth-of-type(even):not(.timeline-item-left) > .timeline-event:before,
.timeline .timeline-item.timeline-item-right > .timeline-event:after,
.timeline .timeline-item:nth-of-type(even):not(.timeline-item-left) > .timeline-event:after {
  right: auto !important;
  border-left-width: 0 !important;
}
.timeline .timeline-item.timeline-item-right > .timeline-event:before,
.timeline .timeline-item:nth-of-type(even):not(.timeline-item-left) > .timeline-event:before {
  left: -15px !important;
  border-right-width: 15px !important;
}
.timeline .timeline-item.timeline-item-right > .timeline-event:after,
.timeline .timeline-item:nth-of-type(even):not(.timeline-item-left) > .timeline-event:after {
  left: -14px !important;
  border-right-width: 14px !important;
}
.timeline .timeline-item > .timeline-event:before {
  top: 10px;
  right: -15px;
  border-top: 15px solid transparent;
  border-left-width: 15px;
  border-left-style: solid;
  border-right-width: 0;
  border-right-style: solid;
  border-bottom: 15px solid transparent;
}
.timeline .timeline-item > .timeline-event:after {
  top: 11px;
  right: -14px;
  border-top: 14px solid transparent;
  border-left-width: 14px;
  border-left-style: solid;
  border-right-width: 0;
  border-right-style: solid;
  border-bottom: 14px solid transparent;
}
.timeline .timeline-item > .timeline-point {
  top: 25px;
}
.timeline-single-column.timeline .timeline-item > .timeline-event {
  float: right !important;
}
.timeline-single-column.timeline .timeline-item > .timeline-event:before,
.timeline-single-column.timeline .timeline-item > .timeline-event:after {
  right: auto !important;
  border-left-width: 0 !important;
}
.timeline-single-column.timeline .timeline-item > .timeline-event:before {
  left: -15px !important;
  border-right-width: 15px !important;
}
.timeline-single-column.timeline .timeline-item > .timeline-event:after {
  left: -14px !important;
  border-right-width: 14px !important;
}
.timeline .timeline-item:nth-of-type(2) {
  margin-top: 40px;
}
.timeline .timeline-item.timeline-item-left,
.timeline .timeline-item.timeline-item-right {
  clear: both !important;
}
.timeline .timeline-item.timeline-item-right,
.timeline .timeline-item:nth-of-type(even):not(.timeline-item-left) {
  float: right;
  clear: right;
}
.timeline .timeline-item.timeline-item-right > .timeline-point,
.timeline .timeline-item:nth-of-type(even):not(.timeline-item-left) > .timeline-point {
  left: -24px;
}
.timeline .timeline-item.timeline-item-right > .timeline-point.timeline-point-blank,
.timeline .timeline-item:nth-of-type(even):not(.timeline-item-left) > .timeline-point.timeline-point-blank {
  left: -12px;
}
.timeline .timeline-item.timeline-item-arrow-sm.timeline-item-right > .timeline-event,
.timeline .timeline-item.timeline-item-arrow-sm:nth-of-type(even):not(.timeline-item-left) > .timeline-event {
  float: right !important;
}
.timeline .timeline-item.timeline-item-arrow-sm.timeline-item-right > .timeline-event:before,
.timeline .timeline-item.timeline-item-arrow-sm:nth-of-type(even):not(.timeline-item-left) > .timeline-event:before,
.timeline .timeline-item.timeline-item-arrow-sm.timeline-item-right > .timeline-event:after,
.timeline .timeline-item.timeline-item-arrow-sm:nth-of-type(even):not(.timeline-item-left) > .timeline-event:after {
  right: auto !important;
  border-left-width: 0 !important;
}
.timeline .timeline-item.timeline-item-arrow-sm.timeline-item-right > .timeline-event:before,
.timeline .timeline-item.timeline-item-arrow-sm:nth-of-type(even):not(.timeline-item-left) > .timeline-event:before {
  left: -10px !important;
  border-right-width: 10px !important;
}
.timeline .timeline-item.timeline-item-arrow-sm.timeline-item-right > .timeline-event:after,
.timeline .timeline-item.timeline-item-arrow-sm:nth-of-type(even):not(.timeline-item-left) > .timeline-event:after {
  left: -9px !important;
  border-right-width: 9px !important;
}
.timeline .timeline-item.timeline-item-arrow-sm > .timeline-event:before {
  top: 4px;
  right: -10px;
  border-top: 10px solid transparent;
  border-left-width: 10px;
  border-left-style: solid;
  border-right-width: 0;
  border-right-style: solid;
  border-bottom: 10px solid transparent;
}
.timeline .timeline-item.timeline-item-arrow-sm > .timeline-event:after {
  top: 5px;
  right: -9px;
  border-top: 9px solid transparent;
  border-left-width: 9px;
  border-left-style: solid;
  border-right-width: 0;
  border-right-style: solid;
  border-bottom: 9px solid transparent;
}
.timeline .timeline-item.timeline-item-arrow-sm > .timeline-point {
  top: 14px;
}
.timeline-single-column.timeline .timeline-item.timeline-item-arrow-sm > .timeline-event {
  float: right !important;
}
.timeline-single-column.timeline .timeline-item.timeline-item-arrow-sm > .timeline-event:before,
.timeline-single-column.timeline .timeline-item.timeline-item-arrow-sm > .timeline-event:after {
  right: auto !important;
  border-left-width: 0 !important;
}
.timeline-single-column.timeline .timeline-item.timeline-item-arrow-sm > .timeline-event:before {
  left: -10px !important;
  border-right-width: 10px !important;
}
.timeline-single-column.timeline .timeline-item.timeline-item-arrow-sm > .timeline-event:after {
  left: -9px !important;
  border-right-width: 9px !important;
}
.timeline .timeline-item.timeline-item-arrow-md.timeline-item-right > .timeline-event,
.timeline .timeline-item.timeline-item-arrow-md:nth-of-type(even):not(.timeline-item-left) > .timeline-event {
  float: right !important;
}
.timeline .timeline-item.timeline-item-arrow-md.timeline-item-right > .timeline-event:before,
.timeline .timeline-item.timeline-item-arrow-md:nth-of-type(even):not(.timeline-item-left) > .timeline-event:before,
.timeline .timeline-item.timeline-item-arrow-md.timeline-item-right > .timeline-event:after,
.timeline .timeline-item.timeline-item-arrow-md:nth-of-type(even):not(.timeline-item-left) > .timeline-event:after {
  right: auto !important;
  border-left-width: 0 !important;
}
.timeline .timeline-item.timeline-item-arrow-md.timeline-item-right > .timeline-event:before,
.timeline .timeline-item.timeline-item-arrow-md:nth-of-type(even):not(.timeline-item-left) > .timeline-event:before {
  left: -15px !important;
  border-right-width: 15px !important;
}
.timeline .timeline-item.timeline-item-arrow-md.timeline-item-right > .timeline-event:after,
.timeline .timeline-item.timeline-item-arrow-md:nth-of-type(even):not(.timeline-item-left) > .timeline-event:after {
  left: -14px !important;
  border-right-width: 14px !important;
}
.timeline .timeline-item.timeline-item-arrow-md > .timeline-event:before {
  top: 10px;
  right: -15px;
  border-top: 15px solid transparent;
  border-left-width: 15px;
  border-left-style: solid;
  border-right-width: 0;
  border-right-style: solid;
  border-bottom: 15px solid transparent;
}
.timeline .timeline-item.timeline-item-arrow-md > .timeline-event:after {
  top: 11px;
  right: -14px;
  border-top: 14px solid transparent;
  border-left-width: 14px;
  border-left-style: solid;
  border-right-width: 0;
  border-right-style: solid;
  border-bottom: 14px solid transparent;
}
.timeline .timeline-item.timeline-item-arrow-md > .timeline-point {
  top: 25px;
}
.timeline-single-column.timeline .timeline-item.timeline-item-arrow-md > .timeline-event {
  float: right !important;
}
.timeline-single-column.timeline .timeline-item.timeline-item-arrow-md > .timeline-event:before,
.timeline-single-column.timeline .timeline-item.timeline-item-arrow-md > .timeline-event:after {
  right: auto !important;
  border-left-width: 0 !important;
}
.timeline-single-column.timeline .timeline-item.timeline-item-arrow-md > .timeline-event:before {
  left: -15px !important;
  border-right-width: 15px !important;
}
.timeline-single-column.timeline .timeline-item.timeline-item-arrow-md > .timeline-event:after {
  left: -14px !important;
  border-right-width: 14px !important;
}
.timeline .timeline-item.timeline-item-arrow-lg.timeline-item-right > .timeline-event,
.timeline .timeline-item.timeline-item-arrow-lg:nth-of-type(even):not(.timeline-item-left) > .timeline-event {
  float: right !important;
}
.timeline .timeline-item.timeline-item-arrow-lg.timeline-item-right > .timeline-event:before,
.timeline .timeline-item.timeline-item-arrow-lg:nth-of-type(even):not(.timeline-item-left) > .timeline-event:before,
.timeline .timeline-item.timeline-item-arrow-lg.timeline-item-right > .timeline-event:after,
.timeline .timeline-item.timeline-item-arrow-lg:nth-of-type(even):not(.timeline-item-left) > .timeline-event:after {
  right: auto !important;
  border-left-width: 0 !important;
}
.timeline .timeline-item.timeline-item-arrow-lg.timeline-item-right > .timeline-event:before,
.timeline .timeline-item.timeline-item-arrow-lg:nth-of-type(even):not(.timeline-item-left) > .timeline-event:before {
  left: -18px !important;
  border-right-width: 18px !important;
}
.timeline .timeline-item.timeline-item-arrow-lg.timeline-item-right > .timeline-event:after,
.timeline .timeline-item.timeline-item-arrow-lg:nth-of-type(even):not(.timeline-item-left) > .timeline-event:after {
  left: -17px !important;
  border-right-width: 17px !important;
}
.timeline .timeline-item.timeline-item-arrow-lg > .timeline-event:before {
  top: 10px;
  right: -18px;
  border-top: 18px solid transparent;
  border-left-width: 18px;
  border-left-style: solid;
  border-right-width: 0;
  border-right-style: solid;
  border-bottom: 18px solid transparent;
}
.timeline .timeline-item.timeline-item-arrow-lg > .timeline-event:after {
  top: 11px;
  right: -17px;
  border-top: 17px solid transparent;
  border-left-width: 17px;
  border-left-style: solid;
  border-right-width: 0;
  border-right-style: solid;
  border-bottom: 17px solid transparent;
}
.timeline .timeline-item.timeline-item-arrow-lg > .timeline-point {
  top: 28px;
}
.timeline-single-column.timeline .timeline-item.timeline-item-arrow-lg > .timeline-event {
  float: right !important;
}
.timeline-single-column.timeline .timeline-item.timeline-item-arrow-lg > .timeline-event:before,
.timeline-single-column.timeline .timeline-item.timeline-item-arrow-lg > .timeline-event:after {
  right: auto !important;
  border-left-width: 0 !important;
}
.timeline-single-column.timeline .timeline-item.timeline-item-arrow-lg > .timeline-event:before {
  left: -18px !important;
  border-right-width: 18px !important;
}
.timeline-single-column.timeline .timeline-item.timeline-item-arrow-lg > .timeline-event:after {
  left: -17px !important;
  border-right-width: 17px !important;
}
.timeline .timeline-item > .timeline-event {
  background: #fff;
  border: 1px solid #888888;
  color: #555;
  position: relative;
  float: left;
  border-radius: 3px;
}
.timeline .timeline-item > .timeline-event:before {
  border-left-color: #888888;
  border-right-color: #888888;
}
.timeline .timeline-item > .timeline-event:after {
  border-left-color: #fff;
  border-right-color: #fff;
}
.timeline .timeline-item > .timeline-event * {
  color: inherit;
}
.timeline .timeline-item > .timeline-event.timeline-event-default {
  background: #fff;
  border: 1px solid #888888;
  color: #555;
}
.timeline .timeline-item > .timeline-event.timeline-event-default:before {
  border-left-color: #888888;
  border-right-color: #888888;
}
.timeline .timeline-item > .timeline-event.timeline-event-default:after {
  border-left-color: #fff;
  border-right-color: #fff;
}
.timeline .timeline-item > .timeline-event.timeline-event-default * {
  color: inherit;
}
.timeline .timeline-item > .timeline-event.timeline-event-primary {
  background: #f5f5f5;
  border: 1px solid #888888;
  color: #555;
}
.timeline .timeline-item > .timeline-event.timeline-event-primary:before {
  border-left-color: #888888;
  border-right-color: #888888;
}
.timeline .timeline-item > .timeline-event.timeline-event-primary:after {
  border-left-color: #f5f5f5;
  border-right-color: #f5f5f5;
}
.timeline .timeline-item > .timeline-event.timeline-event-primary * {
  color: inherit;
}
.timeline .timeline-item > .timeline-event.timeline-event-success {
  background: #F3F8ED;
  border: 1px solid #72b92e;
  color: #3F8100;
}
.timeline .timeline-item > .timeline-event.timeline-event-success:before {
  border-left-color: #72b92e;
  border-right-color: #72b92e;
}
.timeline .timeline-item > .timeline-event.timeline-event-success:after {
  border-left-color: #F3F8ED;
  border-right-color: #F3F8ED;
}
.timeline .timeline-item > .timeline-event.timeline-event-success * {
  color: inherit;
}
.timeline .timeline-item > .timeline-event.timeline-event-info {
  background: #F0F8FD;
  border: 1px solid #3e93cf;
  color: #0062A7;
}
.timeline .timeline-item > .timeline-event.timeline-event-info:before {
  border-left-color: #3e93cf;
  border-right-color: #3e93cf;
}
.timeline .timeline-item > .timeline-event.timeline-event-info:after {
  border-left-color: #F0F8FD;
  border-right-color: #F0F8FD;
}
.timeline .timeline-item > .timeline-event.timeline-event-info * {
  color: inherit;
}
.timeline .timeline-item > .timeline-event.timeline-event-warning {
  background: #FFF9E9;
  border: 1px solid #d0aa42;
  color: #ac7e00;
}
.timeline .timeline-item > .timeline-event.timeline-event-warning:before {
  border-left-color: #d0aa42;
  border-right-color: #d0aa42;
}
.timeline .timeline-item > .timeline-event.timeline-event-warning:after {
  border-left-color: #FFF9E9;
  border-right-color: #FFF9E9;
}
.timeline .timeline-item > .timeline-event.timeline-event-warning * {
  color: inherit;
}
.timeline .timeline-item > .timeline-event.timeline-event-danger {
  background: #FFC4BC;
  border: 1px solid #d25a4b;
  color: #B71500;
}
.timeline .timeline-item > .timeline-event.timeline-event-danger:before {
  border-left-color: #d25a4b;
  border-right-color: #d25a4b;
}
.timeline .timeline-item > .timeline-event.timeline-event-danger:after {
  border-left-color: #FFC4BC;
  border-right-color: #FFC4BC;
}
.timeline .timeline-item > .timeline-event.timeline-event-danger * {
  color: inherit;
}
.timeline .timeline-item > .timeline-event:before,
.timeline .timeline-item > .timeline-event:after {
  content: "";
  display: inline-block;
  position: absolute;
}
.timeline .timeline-item > .timeline-event .timeline-heading,
.timeline .timeline-item > .timeline-event .timeline-body,
.timeline .timeline-item > .timeline-event .timeline-footer {
  padding: 4px 10px;
}
.timeline .timeline-item > .timeline-event .timeline-heading p,
.timeline .timeline-item > .timeline-event .timeline-body p,
.timeline .timeline-item > .timeline-event .timeline-footer p,
.timeline .timeline-item > .timeline-event .timeline-heading ul,
.timeline .timeline-item > .timeline-event .timeline-body ul,
.timeline .timeline-item > .timeline-event .timeline-footer ul {
  margin-bottom: 0;
}
.timeline .timeline-item > .timeline-event .timeline-heading h4 {
  font-weight: 400;
}
.timeline .timeline-item > .timeline-event .timeline-footer a {
  cursor: pointer;
  text-decoration: none;
}
.timeline .timeline-item > .timeline-event .panel,
.timeline .timeline-item > .timeline-event .table,
.timeline .timeline-item > .timeline-event .blankslate {
  margin: 0;
  border: none;
  border-radius: inherit;
  overflow: hidden;
}
.timeline .timeline-item > .timeline-event .table th {
  border-top: 0;
}
.timeline .timeline-item > .timeline-point {
  color: #888888;
  background: #fff;
  right: -24px;
  width: 24px;
  height: 24px;
  margin-top: -12px;
  margin-left: 12px;
  margin-right: 12px;
  position: absolute;
  z-index: 100;
  border-width: 2px;
  border-style: solid;
  border-radius: 100%;
  line-height: 20px;
  text-align: center;
}
.timeline .timeline-item > .timeline-point.timeline-point-blank {
  right: -12px;
  width: 12px;
  height: 12px;
  margin-top: -6px;
  margin-left: 6px;
  margin-right: 6px;
  color: #888888;
  background: #888888;
}
.timeline .timeline-item > .timeline-point.timeline-point-default {
  color: #888888;
  background: #fff;
}
.timeline .timeline-item > .timeline-point.timeline-point-primary {
  color: #888888;
  background: #fff;
}
.timeline .timeline-item > .timeline-point.timeline-point-success {
  color: #72b92e;
  background: #fff;
}
.timeline .timeline-item > .timeline-point.timeline-point-info {
  color: #3e93cf;
  background: #fff;
}
.timeline .timeline-item > .timeline-point.timeline-point-warning {
  color: #d0aa42;
  background: #fff;
}
.timeline .timeline-item > .timeline-point.timeline-point-danger {
  color: #d25a4b;
  background: #fff;
}
.timeline .timeline-label {
  position: relative;
  float: left;
  clear: left;
  width: 50%;
  margin-bottom: 20px;
  top: 1px;
  width: 100%;
  margin-left: auto;
  margin-right: auto;
  padding: 0;
  text-align: center;
}
.timeline .timeline-label:before,
.timeline .timeline-label:after {
  content: "";
  display: table;
}
.timeline .timeline-label:after {
  clear: both;
}
.timeline .timeline-label:last-child {
  margin-bottom: 0 !important;
}
.timeline .timeline-label + .timeline-item {
  margin-top: 0;
}
.timeline .timeline-label + .timeline-item + .timeline-item {
  margin-top: 40px;
}
.timeline .timeline-label .label-default {
  background-color: #888888;
}
.timeline .timeline-label .label-primary {
  background-color: #888888;
  font-size:14px;
  padding:10px;
}
.timeline .timeline-label .label-info {
  background-color: #3e93cf;
}
.timeline .timeline-label .label-warning {
  background-color: #d0aa42;
}
.timeline .timeline-label .label-danger {
  background-color: #d25a4b;
}
@media (max-width: 768px) {
  .timeline.timeline {
    width: 100%;
    max-width: 100%;
  }
  .timeline.timeline .timeline-item {
    padding-left: 72px;
    padding-right: 0;
  }
  .timeline.timeline .timeline-item.timeline-item-right,
  .timeline.timeline .timeline-item:nth-of-type(even):not(.timeline-item-left) {
    padding-left: 72px;
    padding-right: 0;
  }
  .timeline.timeline .timeline-item .timeline-event {
    width: 100%;
  }
  .timeline.timeline:before {
    left: 42px;
    width: 0;
    margin-left: -1px;
  }
  .timeline.timeline .timeline-item {
    width: 100%;
    margin-bottom: 20px;
  }
  .timeline.timeline .timeline-item:nth-of-type(even) {
    margin-top: 0;
  }
  .timeline.timeline .timeline-item > .timeline-event {
    float: right !important;
  }
  .timeline.timeline .timeline-item > .timeline-event:before,
  .timeline.timeline .timeline-item > .timeline-event:after {
    right: auto !important;
    border-left-width: 0 !important;
  }
  .timeline.timeline .timeline-item > .timeline-event:before {
    left: -15px !important;
    border-right-width: 15px !important;
  }
  .timeline.timeline .timeline-item > .timeline-event:after {
    left: -14px !important;
    border-right-width: 14px !important;
  }
  .timeline.timeline .timeline-item > .timeline-point {
    transform: translateX(-50%);
    left: 42px !important;
    margin-left: 0;
  }
  .timeline.timeline .timeline-label {
    transform: translateX(-50%);
    margin: 0 0 20px 42px;
  }
  .timeline.timeline .timeline-label + .timeline-item + .timeline-item {
    margin-top: 0;
  }
}
</style>

<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.5.0/css/font-awesome.min.css">

<div class="container-fluid">
        <div class="col-md-12">
            <div class="row">
                <h2>Usage example</h2>
                <div class="timeline timeline-line-dotted">
                    <span class="timeline-label">
                        <span class="label label-primary">1936</span>
                    </span>
                    <div class="timeline-item">
                        <div class="timeline-point timeline-point-success">
                            <i class="fa fa-clock-o" aria-hidden="true"></i>
                        </div>
                        <div class="timeline-event">
                            <div class="timeline-heading">
                                <h4>Alan Turing</h4>
                            </div>
                            <div class="timeline-body">
                                <p>Fue el primero en estudiar el cerebro como una forma de ver el mundo de la computación.</p>
                            </div>
                            
                        </div>
                    </div>
                    <span class="timeline-label">
                        <span class="label label-primary">1943</span>
                    </span>
                    <div class="timeline-item">
                        <div class="timeline-point timeline-point-success">
                            <i class="fa fa-clock-o" aria-hidden="true"></i>
                        </div>
                        <div class="timeline-event">
                            <div class="timeline-heading">
                                <h4>Warren McCulloch, un neurofisiólogo, y Walter Pitts, un matemático</h4>
                            </div>
                            <div class="timeline-body">
                                <p>Los primeros teóricos que concibieron los fundamentos de la computación neuronal. Lanzaron una 
                                  teoría acerca de la forma
                                  de trabajar de las neuronas (Un Cálculo Lógico de la Inminente Idea de la Actividad 
                                  Nerviosa, modelaron una red neuronal simple mediante circuitos eléctricos.</p>
                            </div>
                            
                        </div>
                    </div>
                    <span class="timeline-label">
                        <span class="label label-primary">1949</span>
                    </span>
                    <div class="timeline-item">
                        <div class="timeline-point timeline-point-success">
                            <i class="fa fa-clock-o" aria-hidden="true"></i>
                        </div>
                        <div class="timeline-event">
                            <div class="timeline-heading">
                                <h4>Donald Hebb</h4>
                            </div>
                            <div class="timeline-body">
                                <p>Fue el primero en explicar los procesos del aprendizaje (que es el elemento básico de la inteligencia humana)
                                  desde un punto de vista psicológico, desarrollando una regla de como el aprendizaje ocurría. 
                                  Su idea fue que el aprendizaje ocurría cuando ciertos cambios en una neurona eran
                                  activados. Los trabajos de Hebb formaron las bases de la Teoría de las Redes Neuronales</p>
                            </div>
                            
                        </div>
                    </div>
                    <span class="timeline-label">
                        <span class="label label-primary">1950</span>
                    </span>
                    <div class="timeline-item">
                        <div class="timeline-point timeline-point-success">
                            <i class="fa fa-clock-o" aria-hidden="true"></i>
                        </div>
                        <div class="timeline-event">
                            <div class="timeline-heading">
                                <h4>Karl Lashley</h4>
                            </div>
                            <div class="timeline-body">
                               <p>En sus series de ensayos, encontró que la información no era almacenada 
                                 en forma centralizada en el cerebro sino que era
                                 distribuida encima de él. </p>
                            </div>
                            
                        </div>
                    </div>
                   
                   
                    <span class="timeline-label">
                        <span class="label label-primary">1956</span>
                    </span>
                    <div class="timeline-item">
                        <div class="timeline-point timeline-point-success">
                           <i class="fa fa-clock-o" aria-hidden="true"></i>
                        </div>
                        <div class="timeline-event">
                            <div class="timeline-heading">
                                <h4>John McCarthy</h4>
                            </div>
                            <div class="timeline-body">
                                <p>Organiza un congreso en la universidad de Dartmouth en Estados Unidos, donde se acuña el término
                                   inteligencia artificial. Se tratan temas de teoría de autómatas, redes neuronales y estudios sobre inteligencia</p>
                            </div>
                            
                        </div>
                    </div>
                    
                    
                    <span class="timeline-label">
                        <span class="label label-primary">1957</span>
                    </span>
                    <div class="timeline-item">
                        <div class="timeline-point timeline-point-success">
                            <i class="fa fa-clock-o" aria-hidden="true"></i>
                        </div>
                        <div class="timeline-event">
                            <div class="timeline-heading">
                                <h4>Frank Rosenblatt</h4>
                            </div>
                            <div class="timeline-body">
                                <p>Comenzó el desarrollo del Perceptron. Esta es la red neuronal más antigua; utilizándose 
                                  hoy en día para aplicación como identificador de patrones. Este modelo era capaz de 
                                  generalizar, es decir, despuésde haber aprendido una serie de patrones
                                  podía reconocer otros similares, aunque no se le hubiesen presentado en el entrenamiento.</p>
                            </div>
                            
                        </div>
                    </div>
                    
                    
                    <span class="timeline-label">
                        <span class="label label-primary">1959</span>
                    </span>
                    <div class="timeline-item">
                        <div class="timeline-point timeline-point-success">
                            <i class="fa fa-clock-o" aria-hidden="true"></i>
                        </div>
                        <div class="timeline-event">
                            <div class="timeline-heading">
                                <h4>Frank Rosenblatt</h4>
                            </div>
                            <div class="timeline-body">
                                <p>En su libro Principios de Neurodinámica confirmó que, bajo ciertas condiciones, 
                                  el aprendizaje del Perceptron convergía hacia un estado finito (Teorema de Convergencia del Perceptron).</p>
                            </div>
                            
                        </div>
                    </div>
                    
                    
                    
                    <span class="timeline-label">
                        <span class="label label-primary">1960</span>
                    </span>
                    <div class="timeline-item">
                        <div class="timeline-point timeline-point-success">
                            <i class="fa fa-clock-o" aria-hidden="true"></i>
                        </div>
                        <div class="timeline-event">
                            <div class="timeline-heading">
                                <h4>Bernard Widroff/Marcian Hoff</h4>
                            </div>
                            <div class="timeline-body">
                                <p>Desarrollaron el modelo Adaline (ADAptative LINear Elements). Fue la primera red neuronal aplicada a un 
                                  problema real (filtros adaptativos para eliminar ecos en las líneas telefónicas).</p>
                            </div>
                            
                        </div>
                    </div>
                    
                    
                    <span class="timeline-label">
                        <span class="label label-primary">1961</span>
                    </span>
                    <div class="timeline-item">
                        <div class="timeline-point timeline-point-success">
                            <i class="fa fa-clock-o" aria-hidden="true"></i>
                        </div>
                        <div class="timeline-event">
                            <div class="timeline-heading">
                                <h4>Karl Steinbeck</h4>
                            </div>
                            <div class="timeline-body">
                                <p>Die Lernmatrix. Red neuronal para simples realizaciones técnicas (memoria asociativa). </p>
                            </div>
                            
                        </div>
                    </div>
                    
                    
                    
                    <span class="timeline-label">
                        <span class="label label-primary">1969</span>
                    </span>
                    <div class="timeline-item">
                        <div class="timeline-point timeline-point-success">
                            <i class="fa fa-clock-o" aria-hidden="true"></i>
                        </div>
                        <div class="timeline-event">
                            <div class="timeline-heading">
                                <h4>Marvin Minsky/Seymour Papert</h4>
                            </div>
                            <div class="timeline-body">
                                <p>En este año casi se produjo la “muerte abrupta” de las Redes Neuronales; ya 
                                  que Minsky y Papert probaron (matemáticamente) que el Perceptrons no era capaz de
                                  resolver problemas relativamente fáciles, tales como el aprendizaje de una función 
                                  no-lineal. Esto demostró que el Perceptron era muy débil, dado que las funciones 
                                  no-lineales son extensamente empleadas en computación y en los problemas del mundo real.</p>
                            </div>
                            
                        </div>
                    </div>
                    
                    
                    
                    <span class="timeline-label">
                        <span class="label label-primary">1974</span>
                    </span>
                    <div class="timeline-item">
                        <div class="timeline-point timeline-point-success">
                            <i class="fa fa-clock-o" aria-hidden="true"></i>
                        </div>
                        <div class="timeline-event">
                            <div class="timeline-heading">
                                <h4>Paul Werbos</h4>
                            </div>
                            <div class="timeline-body">
                                <p>Desarrolló la idea básica del algoritmo de aprendizaje de propagación hacia 
                                  atrás (backpropagation); cuyo significado quedó definitivamente aclarado en 1985. </p>
                            </div>
                            
                        </div>
                    </div>
                    
                    
                    <span class="timeline-label">
                        <span class="label label-primary">1977</span>
                    </span>
                    <div class="timeline-item">
                        <div class="timeline-point timeline-point-success">
                            <i class="fa fa-clock-o" aria-hidden="true"></i>
                        </div>
                        <div class="timeline-event">
                            <div class="timeline-heading">
                                <h4>Stephen Grossberg</h4>
                            </div>
                            <div class="timeline-body">
                                <p>Teoría de Resonancia Adaptada (TRA). La Teoría de Resonancia Adaptada es una arquitectura de red 
                                  que se diferencia de todas las demás previamente inventadas. 
                                  La misma simula otras habilidades del cerebro: memoria a largo y corto plazo.</p>
                            </div>
                            
                        </div>
                    </div>
                    
                  
                  
                  <span class="timeline-label">
                        <span class="label label-primary">1985</span>
                    </span>
                    <div class="timeline-item">
                        <div class="timeline-point timeline-point-success">
                            <i class="fa fa-clock-o" aria-hidden="true"></i>
                        </div>
                        <div class="timeline-event">
                            <div class="timeline-heading">
                                <h4>John Hopfield</h4>
                            </div>
                            <div class="timeline-body">
                                <p>Provocó el renacimiento de las redes neuronales con su libro:
                                  “Computación neuronal de decisiones en problemas de optimización.”</p>
                            </div>
                            
                        </div>
                    </div>
                  
                  
                  
                  <span class="timeline-label">
                        <span class="label label-primary">1986</span>
                    </span>
                    <div class="timeline-item">
                        <div class="timeline-point timeline-point-success">
                            <i class="fa fa-clock-o" aria-hidden="true"></i>
                        </div>
                        <div class="timeline-event">
                            <div class="timeline-heading">
                                <h4>David Rumelhart/G. Hinton</h4>
                            </div>
                            <div class="timeline-body">
                                <p>Redescubrieron el algoritmo de aprendizaje de propagación hacia atrás (backpropagation). </p>
                            </div>
                            
                        </div>
                    </div>
                  
                  
                  <span class="timeline-label">
                        <span class="label label-primary">1986</span>
                    </span>
                    <div class="timeline-item">
                        <div class="timeline-point timeline-point-success">
                            <i class="fa fa-clock-o" aria-hidden="true"></i>
                        </div>
                        <div class="timeline-event">
                            <div class="timeline-heading">
                                <h4>Redes Neuronales</h4>
                            </div>
                            <div class="timeline-body">
                                <p>el panorama fue alentador con respecto a las investigaciones y el desarrollo de las redes 
                                  neuronales. En la actualidad, son numerosos los trabajos que se realizan y publican cada 
                                  año, las aplicaciones nuevas que surgen (sobretodo en el área de control) y las empresas 
                                  que lanzan al mercado productos nuevos, tanto hardware como software (sobre todo para simulación).</p>
                            </div>
                            
                        </div>
                    </div> 
                </div>
            </div>
        </div>
    </div>
