# woke-grid

> 24格的栅格化

栅格化的设计目的是统一布局，在前端目的是快速开发。使用 `m-grid` 包含 `m-grid-数字` 组成布局。 `m-grid-数字` 的数字只和需要等于 `24`。

<link rel="stylesheet" href="./index.less">

## 1-24
````html
<div class="m-grid">
    <div class="m-grid-1">m-grid-1</div><div class="m-grid-23">m-grid-23</div>
    <div class="m-grid-2">m-grid-2</div><div class="m-grid-22">m-grid-22</div>
    <div class="m-grid-3">m-grid-3</div><div class="m-grid-21">m-grid-21</div>
    <div class="m-grid-4">m-grid-4</div><div class="m-grid-20">m-grid-20</div>
    <div class="m-grid-5">m-grid-5</div><div class="m-grid-19">m-grid-19</div>
    <div class="m-grid-6">m-grid-6</div><div class="m-grid-18">m-grid-18</div>
    <div class="m-grid-7">m-grid-7</div><div class="m-grid-17">m-grid-17</div>
    <div class="m-grid-8">m-grid-8</div><div class="m-grid-16">m-grid-16</div>
    <div class="m-grid-9">m-grid-9</div><div class="m-grid-15">m-grid-15</div>
    <div class="m-grid-10">m-grid-10</div><div class="m-grid-14">m-grid-14</div>
    <div class="m-grid-11">m-grid-11</div><div class="m-grid-13">m-grid-13</div>
    <div class="m-grid-12">m-grid-12</div><div class="m-grid-12">m-grid-12</div>
    <div class="m-grid-13">m-grid-13</div><div class="m-grid-11">m-grid-11</div>
    <div class="m-grid-14">m-grid-14</div><div class="m-grid-10">m-grid-10</div>
    <div class="m-grid-15">m-grid-15</div><div class="m-grid-9">m-grid-9</div>
    <div class="m-grid-16">m-grid-16</div><div class="m-grid-8">m-grid-8</div>
    <div class="m-grid-17">m-grid-17</div><div class="m-grid-7">m-grid-7</div>
    <div class="m-grid-18">m-grid-18</div><div class="m-grid-6">m-grid-6</div>
    <div class="m-grid-19">m-grid-19</div><div class="m-grid-5">m-grid-5</div>
    <div class="m-grid-20">m-grid-20</div><div class="m-grid-4">m-grid-4</div>
    <div class="m-grid-21">m-grid-21</div><div class="m-grid-3">m-grid-3</div>
    <div class="m-grid-22">m-grid-22</div><div class="m-grid-2">m-grid-2</div>
    <div class="m-grid-23">m-grid-23</div><div class="m-grid-1">m-grid-1</div>
    <div class="m-grid-24">m-grid-24</div>
</div>
````
## 4 20
````html
<div class="m-grid">
    <div class="m-grid-4">m-grid-4</div>
    <div class="m-grid-20">m-grid-20</div>
</div>
````

## 3 3 3 3 3 3 3 3
````html
<div class="m-grid">
    <div class="m-grid-3">m-grid-3</div>
    <div class="m-grid-3">m-grid-3</div>
    <div class="m-grid-3">m-grid-3</div>
    <div class="m-grid-3">m-grid-3</div>
    <div class="m-grid-3">m-grid-3</div>
    <div class="m-grid-3">m-grid-3</div>
    <div class="m-grid-3">m-grid-3</div>
    <div class="m-grid-3">m-grid-3</div>
</div>
````

<style>
/* 用于演示的样式 */
.m-grid-1,
.m-grid-2,
.m-grid-3,
.m-grid-4,
.m-grid-5,
.m-grid-6,
.m-grid-7,
.m-grid-8,
.m-grid-9,
.m-grid-10,
.m-grid-11,
.m-grid-12,
.m-grid-13,
.m-grid-14,
.m-grid-15,
.m-grid-16,
.m-grid-17,
.m-grid-18,
.m-grid-19,
.m-grid-20,
.m-grid-21,
.m-grid-22,
.m-grid-23,
.m-grid-24 {
    margin-bottom: 5px;
    height: 20px;
    line-height:20px;
    color:white;
    font-size:12px;
}
.m-grid-1,
.m-grid-2,
.m-grid-3,
.m-grid-4,
.m-grid-5,
.m-grid-6,
.m-grid-7,
.m-grid-8,
.m-grid-9,
.m-grid-10,
.m-grid-11,
.m-grid-12 {
    background-color:#99CCFF;
    box-shadow:inset 0px 0px 5px #44a0fb;
}
.m-grid-13,
.m-grid-14,
.m-grid-15,
.m-grid-16,
.m-grid-17,
.m-grid-18,
.m-grid-19,
.m-grid-20,
.m-grid-21,
.m-grid-22,
.m-grid-23,
.m-grid-24  {
    background-color:#0099CC;
    box-shadow:inset 0px 0px 5px #0A6586;
}
</style>
