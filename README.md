grid.less
=========

For creating grid layouts depending on your specifications. Using a very dynamic mixin for creating grid css'sss.

example
---------
`.grid('grid', 1000px, 400px, 4, 4, 10px);` With this you create a class wrapper named `.grid` that has a width of `1000px`
and a height of `400px` with 16 items in them `4x4`.


	.grid {
	  position: relative;
	  width: 100px;
	  height: 100px;
	}
	.grid .s4 {
	  width: 100px;
	  height: 100px;
	}
	.grid .s3 {
	  width: 72.5px;
	  height: 72.5px;
	}
	.grid .s2 {
	  width: 45px;
	  height: 45px;
	}
	.grid .s1 {
	  width: 17.5px;
	  height: 17.5px;
	}
	.grid .w4 {
	  width: 100px;
	}
	.grid .w3 {
	  width: 72.5px;
	}
	.grid .w2 {
	  width: 45px;
	}
	.grid .w1 {
	  width: 17.5px;
	}
	.grid .h4 {
	  height: 100px;
	}
	.grid .h3 {
	  height: 72.5px;
	}
	.grid .h2 {
	  height: 45px;
	}
	.grid .h1 {
	  height: 17.5px;
	}
	.grid .x3 {
	  position: absolute;
	  left: 82.5px;
	}
	.grid .x2 {
	  position: absolute;
	  left: 55px;
	}
	.grid .x1 {
	  position: absolute;
	  left: 27.5px;
	}
	.grid .x0 {
	  position: absolute;
	  left: 0px;
	}
	.grid .y3 {
	  position: absolute;
	  top: 82.5px;
	}
	.grid .y2 {
	  position: absolute;
	  top: 55px;
	}
	.grid .y1 {
	  position: absolute;
	  top: 27.5px;
	}
	.grid .y0 {
	  position: absolute;
	  top: 0px;
	}




