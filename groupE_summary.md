# Summary of the dataset 

The given dataset, is called “PAD-UFES-20”. It’s a skin lesion dataset composed by images shot on smartphones.

This dataset takes in account the patient clinical information and different features of the skin lesions, such as their (a)symmetry or color, enabling researchers to try and find a pattern for diagnosing. However, several questions may arise when trying to determine whether any sort of algorithm could in fact be accurate in pinpointing these diagnoses. 

The dataset consists of 1,373 patients, 1,641 skin lesions, and 2,298 images for six different
diagnostics: three skin diseases and three skin cancers. In total, 58.4% of the skin lesions
are biopsy-proven, including 100% of the skin cancers.

We’ve written a brief description of the 6 diagnosis we may find in the images of the dataset:
  
  ● Actinic Keratosis (ACK): Actinic keratosis is a precancerous skin lesion caused by
  prolonged sun exposure. It appears as rough, scaly patches on areas frequently
  exposed to sunlight, such as the face, scalp, hands, and arms. If left untreated, it
  can progress to squamous cell carcinoma.
  
  ● Basal Cell Carcinoma (BCC): Basal cell carcinoma is the most common type of
  skin cancer. It typically appears as a flesh-colored, pearly bump or a pinkish patch
  of skin. BCC usually develops on areas of the skin exposed to the sun, such as the
  face, neck, and ears. It grows slowly and rarely spreads to other parts of the body
  but can cause disfigurement if not treated early.
  
  ● Melanoma (MEL): Melanoma is the most dangerous type of skin cancer. It
  develops in the cells that produce melanin, the pigment that gives skin its color.
  Melanoma often appears as a new spot or a change in an existing mole. It can
  spread rapidly to other parts of the body if not detected and treated early.
  
  ● Nevus (NEV): A nevus, commonly known as a mole, is a benign skin growth
  composed of melanocytes, the pigment-producing cells of the skin. Moles can vary
  in size, shape, and color. While most moles are harmless, some may develop into
  melanoma or other skin cancers.
  
  ● Squamous Cell Carcinoma (SCC): Squamous cell carcinoma is a type of skin
  cancer that arises from the squamous cells in the epidermis, the skin's outermost
  layer. It typically appears as a firm, red nodule or a flat, scaly lesion. SCC often
  develops on areas exposed to the sun, such as the face, ears, and hands. It has
  the potential to metastasize if not treated promptly.
  
  ● Seborrheic Keratosis (SEK): Seborrheic keratosis is a common non-cancerous
  skin growth that appears as waxy, raised lesions with a "stuck-on" appearance.
  They often vary in color, ranging from tan to dark brown or black. Seborrheic
  keratoses are typically found on areas of the body prone to sun exposure, but they
  are harmless and do not require treatment unless they become irritated or
  cosmetically bothersome.

As a final aspect of the summary, it is important to point out that throughout the dataset's images we may encounter some that can't be considered useful to include as valid inputs for the algorithm we will have to develop later on the semester, because they would worsen the algorithm's quality and precision when using it to fulfill its purpose: diagnosing skin cancer after learning how skin cancer looks like. This explains why they are being skipped during the labelling process. 
