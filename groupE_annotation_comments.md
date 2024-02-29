# A clarifying note on the annotation process on Label Studio

We tried setting up a so called organization within a Label Studio instance (one of the group's members laptop Label Studio local server) by following relevant documentation from the Label Studio docs' website itself: [how to invite users to a local instance](https://labelstud.io/guide/signup#Invite-users-to-Label-Studio) & [how to expose the local instance to an outside network (to be able to invite users properly)](https://labelstud.io/guide/start#Expose-a-local-Label-Studio-instance-outside-using-ngrok). However, the latter seems to be outdated because it did not work in any of our laptops (not for macOS, nor for Windows, nor for WSL2), which is the reason why we decided to split our groups' images equally and annotate them separately in each of our laptops' Label Studio instances. This explains why the groupE_masks/ directory in this repository contains four .csv files with the annotations from each member of the group (32 images per member) and why the "annotator_id" field in three of those four files is the same (annotator_id = 1 for the three windows users in the group). 
Thus, we have decided to use our names as the annotator_ids for this file and for groupE_imageids.csv, so that we could correctly keep track of who did what. 

# Annotations' comments

Since we have just marked the different skin lessions without distinguishing between the different types (by, for instance, using a variety of colors for the labelling process) the only comments that make sense are the ones related to skipped images, so:   


