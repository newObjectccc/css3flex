# css3flex

.fater {
    width: 100%;
    height: 300px;
    .child-left {
        width:100px;
        height: 300px;
    }
    .child-right {
        flex: 1;
	      width: 0;
        /* 只有加上了width:0;或者overflow:hidden;才能在right元素内容超出时正常显示或隐藏，不然会溢出父元素的总宽度 */
    }
}
