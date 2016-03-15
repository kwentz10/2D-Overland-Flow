# 2D-Overland-Flow

To my reviewer: navigate to OverlandFlow_constant_rainrate&infilitration.py.  I just realized that I did not change the name of this file--
it should read: OverlandFlow_variable_rainrate&infilitration because I am varying rainrate and infilitration.

Make sure to run this model in Spyder--Idle for some reason is not recognizing landlab.

The file produces 2 figures. One is the water thickness over time and the other is water elevation over time. You'll have to pull
them apart from eachother when they first load (they load on top of eachother :/ ).

I am having trouble with several things: 1) I do not know how to make the colorbar axis set so that the min and max values are constant 
over the runtime. 2) I don't understand why my overland flow is so small (it is 0.004 mm at its greatest). 3) I don't know if my y axis
should be flipped..it goes from high to low numbers. I am not sure if that is just how landlab reads in the grids.

Thanks for reviewing! 
