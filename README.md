grid.less
=========

For creating grid layouts depending on your specifications. Using a very dynamic mixin for creating grid css'sss.

example
---------
'.grid('grid', 1000px, 400px, 4, 4, 10px);' With this you create a class wrapper named '.grid' that has a width of '1000px'
and a height of '400px' with 4 items in them


	.grid {
	  width: 1000px;
	  height: 400px;
	}
	.grid .s4 {
	  width: 1030px;
	  height: 430px;
	}
	.grid .s3 {
	  width: 770px;
	  height: 320px;
	}
	.grid .s2 {
	  width: 510px;
	  height: 210px;
	}
	.grid .s1 {
	  width: 250px;
	  height: 100px;
	}
	.grid .w4 {
	  width: 1030px;
	}
	.grid .w3 {
	  width: 770px;
	}
	.grid .w2 {
	  width: 510px;
	}
	.grid .w1 {
	  width: 250px;
	}
	.grid .h4 {
	  height: 430px;
	}
	.grid .h3 {
	  height: 320px;
	}
	.grid .h2 {
	  height: 210px;
	}
	.grid .h1 {
	  height: 100px;
	}
	.grid .x3 {
	  position: absolute;
	  left: 780px;
	}
	.grid .x2 {
	  position: absolute;
	  left: 520px;
	}
	.grid .x1 {
	  position: absolute;
	  left: 260px;
	}
	.grid .x0 {
	  position: absolute;
	  left: 0px;
	}
	.grid .y3 {
	  position: absolute;
	  top: 330px;
	}
	.grid .y2 {
	  position: absolute;
	  top: 220px;
	}
	.grid .y1 {
	  position: absolute;
	  top: 110px;
	}
	.grid .y0 {
	  position: absolute;
	  top: 0px;
	}



