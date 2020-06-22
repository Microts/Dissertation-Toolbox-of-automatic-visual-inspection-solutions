# Dissertation - Toolbox of automatic visual inspection solutions

**PROJECT:** 

The objective of this work is to develop a toolbox of configurable solutions, through a graphical interface appropriate to the problem, so that they can be applied to similar problems. This dissertation focuses on the detection of four specific problems, namely, the detection of fiducial markers, the detection of pins, the detection of the geometric center and verification of the positioning of pointers and the detection of the absence or defective positioning of screws.

The methods proposed for each of the problems were based on the operators provided by the Halcon software and validated on different objects. The developed methods proved to be efficient, being able to correctly detect the objects.

The developed application focuses on the definition of micro-operations and the execution engine. It is the combination of the interactive mode of the application, with the parameterizable toolbox, that enables the user
configure the solutions.

**OBJECTIVES:**
* Detection and recognition of different fiducial markers to, for example, help locate other electronic components inserted in plates;
* Detection of pins correctly positioned on plugs;
* Detection of the geometric center of objects for the placement of pointers and respective verification of their correct positioning;
* Detection of the absence or defective positioning of screws;
* The solutions developed will also be configurable, so that they can be applied to other problems with different properties.


**RESULTS:** 

[Video of an example](https://youtu.be/w_oUst0VUbQ) - video with the execution of the two interfaces implemented and an example of a solution configuration for a given problem, in this case, for the detection of circular fiducials. Summary: first an image is selected that will serve as a reference for future new test images, and then an appropriate solution to the problem is loaded. By selecting the Settings option, the user will have control over the solution configuration, in the so-called micro-operations. At each step it is possible to adjust its parameters and, before proceeding to the next micro-operation, check its effect unlimited times. When the configuration of the solution is finished, it is transferred to the execution engine (main interface). The "new" solution will be applied to different test images where it will be possible to view the detections made, as well as additional information about the detections made, for example, number of detections and computation times.

* Detection of different circular fiducial markers:

![1](https://user-images.githubusercontent.com/66881028/85334054-8a9e8d80-b4d2-11ea-8a23-e0784874905c.png)

* Detection of different cross fiducial markers:

![2](https://user-images.githubusercontent.com/66881028/85334058-8bcfba80-b4d2-11ea-97eb-62ed1d6f2dba.png)

* Detection of correctly positioned pins:

![3](https://user-images.githubusercontent.com/66881028/85334059-8bcfba80-b4d2-11ea-9507-32d0f48df8c7.png)

![4](https://user-images.githubusercontent.com/66881028/85334060-8c685100-b4d2-11ea-9a10-915042900dcb.png)

* Detection of the geometric center and checking the positioning of pointers:

![5](https://user-images.githubusercontent.com/66881028/85335358-cb97a180-b4d4-11ea-9ebb-2ec985b473df.png)

* Detection of the absence or defective positioning of screws:

![6](https://user-images.githubusercontent.com/66881028/85334062-8d00e780-b4d2-11ea-9eec-75248f76a8b1.png)
