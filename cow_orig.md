# Large datasets 
The full model outputs are several terabytes. Post-processing tasks must be done while the data is on the supercomputer. That storage is not backed up, so the tasks must be completed before the data is lost or purged.

Before running a large model, take inventory of expected end products.  Write, test, and automate post-processing scripts *before* generating data, so they may be scheduled when each model run is complete.  If the end products take only a small fraction of the raw data, and if rerunning the model is less expensive than archival storage, it may be acceptable to delete that raw data. 

<video allow="fullscreen" frameBorder="0" style="width:50vw" controls controlsList="nodownload">
  <source src="https://renc.osn.xsede.org/ees210015-bucket01/img/video/ourdatacow.mp4" type="video/mp4">
  <track label="English" kind="subtitles" srclang="en" src="https://renc.osn.xsede.org/ees210015-bucket01/img/video/changecows.vtt" default>
</video>

## Video Transcript

NC State is an AG school, and North Carolinians like to support their local farms. NC State is also home to your favorite Advanced Computing Specialist, and she supports the high-performance computing center. In this project, she supports the hydrodynamics modeling for Mobile Bay.

Raising a cow takes a lot of time and effort. It is expensive. And it takes a lot of space.  Our hydrodynamics model can take several weeks to run - even on a supercomputer!  Processing the resulting output can take several months.

The model generates 6TB of data. In other words, our data is a cow.

A small farm can't afford to make any mistakes.  Before they start raising the first cow, they need to know who their consumers will be.  Which products will they want?  And how do they need the products to be packaged?

Likewise, before generating the next six terabytes of data, we need to know who the consumers will be.  Which products do they want?  And how do they need the products to be packaged?

To get the cow ready for market, the processing must be done in a plant.  This job is only done once.  The cow goes in...  and the products go out.

The data for our model needs to be processed on the supercomputer.  Hopefully, this job is only done once.  Ideally, the processing is done immediately.  When the job finishes!

The data needs to be processed on the supercomputer.  But we can't store it there. It will need to be archived.  And we can't process data in that type of storage.  If we don't have a list of the products needed when a model is finished, we end up moving the data back and forth. 

We take great care to create models that get the science right.  And to get things right, sometimes you need a cow.  We do need to pause, to think, and to make some data management decisions.  Preferably...  as soon as possible!

## Video Description
The theme song from "Rawhide" plays, and video fades in to an image of a cow looking toward the viewer.  The Monty Python 'and now for something completely different' falls down.  

Text appears in "black and white silent-film" style, saying: NC State is an Ag school...with supercomputing expertise.  

A family with NC State apparel pose next to two cows, then a pasture is shown along with several brand logos from local beef suppliers(Baldwin Beef, First Hand Foods, and others).  

Next is a picture of NC State campus, a head shot of a smiling 'advanced computing specialist', and an image of a supercomputing cluster, followed by a short animation of bottom and surface salinity for Mobile Bay.

Text appears in "black and white silent-film" style, saying: Raising a cow is hard work...and so is running our model.

Fade in to a picture of a farmer nuzzling a cow, a clip art of cash and coins fall, and burn out to an open range with several cows.

Image of Mobile Bay modeling grid showing close-ups of areas with high resolution, a supercomputer, and two head shots of smiling people who process the data.  

Fade in to a clip-art of a storage drive saying 6 TB, then the same cow as the beginning appears abruptly.

Text appears in "black and white silent-film" style, saying: How do small, family farms manage to deal with those cows??? ...and what can we learn from them?

Closeup view of farmer in contemplative state, then pictures representing consumers(box from suppliers or food delivery services), products(diagram of cow with areas labeled for the different cuts), and packaging(individual steaks or patties).

Image of model output and a supercomputer, then pictures representing consumers(climate, watershed, hydro, and ecology modelers), products(words: temperature, salinity, precipitation, nutrients, oxygen, river discharge), and packaging(icon for CSV and netCDF files).

Text appears in "black and white silent-film" style, saying: Limited Time Offer - Order Now!  ...we don't want to do this kind of job more than once! 

Animated cartoon cow walks in to picture of interior of meat processing plant.  Image of different cuts of beef moves out of the same plant into the right side of the screen.  On the left, a sketch of a customer with a menu and a waiter.  The customer asks "Can I just order a meatball?"

Animated cartoon cow walks in to picture of a supercomputer. The cow fades into the earlier images for computational products(temperature, etc.) and packaging(file icons).

Animated cartoon cow starts behind a fence and walks into picture of a supercomputer, then the file icon image floats up from the supercomputer. Text appears labeling the fence as 'Cold Storage' and the supercomputer as 'Network Attached Storage'.  The cow moves back and forth between the fence and computer, and files float up from the computer when the cow moves behind it, a total of four times.  Text appears saying, "This is even more annoying in real life...And it's slower too!"

Text appears in "black and white silent-film" style, saying: Don't moooove it twice...please let's discuss a plan for post-processing model results!

Photo of a cow lying in a grassy field.  Three young women are sitting in the grass, next to the cow, one is cuddled close and gently holding the cow's face.  Next, a photo of cows in a feed lot, and a farmer with hands on hips, looking down at the cows as if wondering what to do.  Finally, a photo of a large herd of cows being herded down a country road, which then zooms in to indicate a stampede.

Text appears in "black and white silent-film" style, saying: The End.  No cows were harmed in the making of this video. 
 

 
  
 
