##WHAT & WHY

This project shows how you can use [PyBossa technology](http://pybossa.com) to crowdsource image pattern recognition problems and get results in real time.

This project is built to help researchers, journalists, civic hackers that need to analyze images, and publish results as soon as the volunteers submit all the answers for a given image.

The project is using the Flickr integration task importer, so the project imported several images from that service. 


##HOW

In order to see how the project produces statistically analyzed results, a tasks needs to be completed. By default each image will have to be reviewed by 5 people, so until 5 persons submit a an answer for a given task, no results will be available. 

However, as soon as the first task gets the first 5 answers, a result will be generated, statistically analyzed and published. For performing these steps we're using the PyBossa webhooks technology and its open source micro-service: [webhooks](https://github.com/PyBossa/webhooks).

We're running that micro-service, and as soon as a task is completed, Crowdcrafting, notifies that service via a POST. The micro-service, downloads the task and its answers, analyze them and publish the results.

##WHO

The project has been created by [Scifabric](http://scifabric.com). The developers of the PyBossa technology as well as the company that hosts Crowdcrafting.org.

##KEEP TRACK

As this is a demo project, the easiest way is to contact us by [email](mailto:info@scifabric.com).
