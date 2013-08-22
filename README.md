grid.less
=========

For creating grid layouts depending on your specifications. Using a very dynamic mixin for creating grid css'sss.
You can use any unit size (px,%,vw) and it will adjust it self to that size.

Compatible with less 1.4 >

example
---------
`.grid('grid', 100px, 100px, 4, 4, 10px);` With this you create a class wrapper named `.grid` that has a width of `100px`
and a height of `100px` with 16 items in them `4x4`.

![Example](https://github.com/mientjan/grid.less/raw/master/example/grid.less-example.png)


### css
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

### html
	<div class="grid">
	    <div class="s1 x0 y0"></div>
	    <div class="s1 x1 y0"></div>
	    <div class="s1 x2 y0"></div>
	    <div class="s1 x3 y0"></div>

	    <div class="s1 x0 y1"></div>
	    <div class="s1 x1 y1"></div>
	    <div class="s1 x2 y1"></div>
	    <div class="s1 x3 y1"></div>

	    <div class="s1 x0 y2"></div>
	    <div class="s1 x1 y2"></div>
	    <div class="s1 x2 y2"></div>
	    <div class="s1 x3 y2"></div>

	    <div class="s1 x0 y3"></div>
	    <div class="s1 x1 y3"></div>
	    <div class="s1 x2 y3"></div>
	    <div class="s1 x3 y3"></div>
	</div>

	<div class="grid">
	    <div class="s2 x0 y0"></div>
	    <div class="s1 x2 y0"></div>
	    <div class="s1 x3 y0"></div>

	    <div class="s1 x2 y1"></div>
	    <div class="s1 x3 y1"></div>

	    <div class="s1 x0 y2"></div>
	    <div class="s1 x1 y2"></div>
	    <div class="s1 x2 y2"></div>
	    <div class="s1 x3 y2"></div>

	    <div class="s1 x0 y3"></div>
	    <div class="s1 x1 y3"></div>
	    <div class="s1 x2 y3"></div>
	    <div class="s1 x3 y3"></div>
	</div>

	<div class="grid">
	    <div class="w3 h2 x0 y0"></div>
	    <div class="s1 x3 y0"></div>
	    <div class="s1 x3 y1"></div>

	    <div class="s1 x0 y2"></div>
	    <div class="s1 x1 y2"></div>
	    <div class="s1 x2 y2"></div>
	    <div class="s1 x3 y2"></div>

	    <div class="s1 x0 y3"></div>
	    <div class="s1 x1 y3"></div>
	    <div class="s1 x2 y3"></div>
	    <div class="s1 x3 y3"></div>
	</div>


	<div class="grid">
	    <div class="w3 h2 x0 y0"></div>
	    <div class="s1 x3 y0"></div>
	    <div class="s1 x3 y1"></div>

	    <div class="w4 h1 x0 y2"></div>

	    <div class="s1 x0 y3"></div>
	    <div class="s1 x1 y3"></div>
	    <div class="s1 x2 y3"></div>
	    <div class="s1 x3 y3"></div>
	</div>

	<div class="grid">
	    <div class="s2 x0 y0"></div>
	    <div class="s2 x2 y0"></div>

	    <div class="s2 x0 y2"></div>
	    <div class="s2 x2 y2"></div>
	</div>


	<div class="grid">
	    <div class="w4 h2 x0 y0"></div>
	    <div class="w4 h2 x0 y2"></div>
	</div>

	<div class="grid">
	    <div class="w2 h4 x0 y0"></div>
	    <div class="w2 h4 x2 y0"></div>
	</div>

