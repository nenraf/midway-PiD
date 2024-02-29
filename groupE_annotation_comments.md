# A clarifying note on the annotation process on Label Studio

We tried setting up a so called organization within a Label Studio instance (one of the group's members laptop Label Studio local server) by following relevant documentation from the Label Studio docs' website itself: [how to invite users to a local instance](https://labelstud.io/guide/signup#Invite-users-to-Label-Studio) & [how to expose the local instance to an outside network (to be able to invite users properly)](https://labelstud.io/guide/start#Expose-a-local-Label-Studio-instance-outside-using-ngrok). However, the latter seems to be outdated because it did not work in any of our laptops (not for macOS, nor for Windows, nor for WSL2), which is the reason why we decided to split our groups' images equally and annotate them separately in each of our laptops' Label Studio instances. This explains why the groupE_masks/ directory in this repository contains four .csv files with the annotations from each member of the group (32 images per member) and why the "annotator_id" field in three of those four files is the same (annotator_id = 1 for the three windows users in the group). 
Thus, we have decided to use our names as the annotator_ids for this file and for groupE_imageids.csv, so that we could correctly keep track of who did what. 

# Annotations' comments

Since we have just marked the different skin lessions without distinguishing between the different types (by, for instance, using a variety of colors for the labelling process) the only comments that make sense are the ones related to skipped images.
We have therefore decided to skip images that were blurry, had a lot hair covering the skin or were just normal skin, these are our comments:

The following images were skipped by Martin (annotator_ID), because they were very blurry:
aa2dfd80-PAT_2107_4595_381.png

The following images were skipped by Martin (annotator_ID), because they looked like normal skin:
73e69631-PAT_1799_3457_209.png, 8a1652ca-PAT_2102_4575_616.png, 7ebac997-PAT_1565_2432_808.png, dd21475d-PAT_1704_3142_702.png, b5f8768b-PAT_1715_3186_948.png, 54c19757-PAT_1738_3260_304.png, 087b04c2-PAT_1399_1367_121.png

The following images were skipped by Martin (annotator_ID), because they had a lot of hair:
00615c9f-PAT_1812_3492_670.png, 7a8c8117-PAT_1483_1678_850.png

The following images were skipped by Sergio (annotator_ID), because they had already been masked:
0e753b53-PAT_1065_275_136.png

The following images were skipped by Sergio (annotator_ID), because the lesions were difficult to distinguish from skin:
2438d898-PAT_1014_85_22.png, a21a7e02-PAT_1112_455_845.png

The following images were skipped by Sergio (annotator_ID), because there was too much hair:
20a40a9b-PAT_999_20_583.png

The following images were skipped by Jan (annotator_ID), because there was too much ink: 
3dd3a20d-PAT_704_1323_974.png, bc78168f-PAT_388_2452_548.png

The following images were skipped by Jan (annotator_ID), there is nothing wrong on the skin: 
51b88287-PAT_512_962_998.png

The following images were skipped by Simon (annotator_ID), because they were blurry:
b6e7527d-PAT_247_1293_449.png, 72b156f9-PAT_65_101_847.png, 9ae6fba0-PAT_153_1200_541.png

The following images were skipped by Simon (annotator_ID), because they looked like normal skin:
c7ae398d-PAT_326_690_797.png, f7983bb7-PAT_328_1738_890.png, 777c1564-PAT_57_90_910.png

The following images were skipped by Simon (annotator_ID), because they had a lot of hair covering the possible skin lession:
e1638171-PAT_279_429_142.png
