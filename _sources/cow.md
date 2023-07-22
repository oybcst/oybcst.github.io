# Large datasets 
The full model outputs are several terabytes. Post-processing tasks must be done while the data is on the supercomputer. That storage is not backed up, so the tasks must be completed before the data is lost or purged.

Before running a large model, take inventory of expected end products.  Write, test, and automate post-processing scripts *before* generating data, so they may be scheduled when each model run is complete.  If the end products take only a small fraction of the raw data, and if rerunning the model is less expensive than archival storage, it may be acceptable to delete that raw data. 

<video controls preload="metadata">
	<source src="https://renc.osn.xsede.org/ees210015-bucket01/img/video/ourdatacow.mp4" type="video/mp4">
	<track label="English" kind="captions" srclang="en" src="https://renc.osn.xsede.org/ees210015-bucket01/img/video/changecows.vtt">
</video>
