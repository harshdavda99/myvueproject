<template>
<div>
    <div class="toggle-group">
                            <input type="checkbox" name="on-off-switch" id="on-off-switch"  tabindex="1">
                            <label for="on-off-switch" (click)="changeActiveInActiveStatus(row.shopId, row)"></label>
                            <div class="onoffswitch pull-right" aria-hidden="true">
                              <div class="onoffswitch-label">

                                <div class="onoffswitch-inner"></div>
                                <div class="onoffswitch-switch"></div>
                              </div>
                            </div>
                          </div>
</div>


</template>


<style>
.onoffswitch {
    position: absolute;
    width: 50%;
    display: inline-block;
    font-size: 80%;
    left: 0;
}

.onoffswitch .onoffswitch-label {
    display: block;
    overflow: hidden;
    cursor: pointer;
    border: 1px solid #4c84ff;
    -moz-border-radius: 20px;
    -webkit-border-radius: 20px;
    border-radius: 20px;
    margin: 0;
}

.onoffswitch .onoffswitch-inner {
    width: 200%;
    margin-left: -100%;
    -webkit-transition: margin 0.15s ease-in-out;
    -o-transition: margin 0.15s ease-in-out;
    -moz-transition: margin 0.15s ease-in-out;
    transition: margin 0.15s ease-in-out;
    font-size: 14px;
    line-height: 17px;
    font-weight: 500;
}

.onoffswitch .onoffswitch-inner:before,
.onoffswitch .onoffswitch-inner:after {
    float: left;
    width: 50%;
    height: 24px;
    padding: 0;
    line-height: 24px;
    font-size: 80%;
    color: hsl(0, 0%, 100%);
    font-weight: normal;
    -moz-box-sizing: border-box;
    -webkit-box-sizing: border-box;
    box-sizing: border-box;
}

.onoffswitch .onoffswitch-inner:before {
    content: "Active";
    padding-left: 10px;
    background-color: #4C84FF;
    color: white;
}

.onoffswitch .onoffswitch-inner:after {
    content: "Deactive";
    padding-left: 10px;
    background-color: #f5f5f5;
    color: #4c84ff;
    text-align: left;
}

.onoffswitch .onoffswitch-switch {
    width: 22px;
    height: 22px;
    margin: 0;
    background: #4c84ff;
    border-radius: 50%;
    position: absolute;
    top: 2px;
    bottom: 0;
    right: 3px;
    transition: right 0.15s ease-in-out;
}

.toggle-group {
    position: relative;
    top: 50%;
    left: 0;
}


.toggle-group input[type=checkbox] {
    position: absolute;
    left: 10px;
    opacity: 0;
    display: none;
}

.toggle-group input[type=checkbox]:checked~.onoffswitch .onoffswitch-label .onoffswitch-inner {
    margin-left: 0;
}

.toggle-group input[type=checkbox]:checked~.onoffswitch .onoffswitch-label .onoffswitch-switch {
    right: 3px;
    box-shadow: 0 0 3px rgb(0 0 0 / 50%);
    background: #fff;
}

.toggle-group input[type=checkbox]:focus~.onoffswitch {
    outline: thin dotted #333;
    outline: 0;
}

.toggle-group label {
    position: absolute;
    cursor: pointer;
    padding-left: 0;
    display: inline-block;
    text-align: left;
    line-height: 24px;
    width: 100%;
    z-index: 1;
    height: 24px;
    font-weight: 200;
}

.aural {
    clip: rect(1px, 1px, 1px, 1px);
    height: 1px;
    overflow: hidden;
    position: absolute;
    width: 1px;
}

.aural:focus {
    clip: rect(0, 0, 0, 0);
    font-size: 1em;
    height: auto;
    outline: thin dotted;
    position: static !important;
    width: auto;
    overflow: visible;
}
</style>