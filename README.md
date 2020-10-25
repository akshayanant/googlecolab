# googlecolab



Dataset creation using Visual Madlibs:

The data set contains the images and the fill in the blanks answers regarding the objects present in the image.
We have selected the type of data which is relevant for our task.
We have created the data related to persons with person attributes, person activities and person locations.

Process:

We have converted the fill in the blanks to referring expressions.
We have only selected the data with the referring expressions comprising of more than 6 words making the referring expression more interesting as possible.

Steps to run the code :
The script requires some dependencies, from Visual Madlibs and Coco dataset.
Fiels to be included from Visual Madlibs, 
	1. <madlibs_train_v1>/tr_person_activities.json 
	2. <madlibs_train_v1>/tr_person_attributes.json
	3. <madlibs_train_v1>/tr_person_locations.json
Files to be included from Coco
	1. annotations_trainval14/instances_val2014.json

THe result will be in the File Results.json




