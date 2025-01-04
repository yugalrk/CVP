Curriculum Learning to Train model:
We have trained the network in 4 ways: 1. Both Acuity and Contrast transformations, 2. Only Acuity,
3. Only Contrast and 4. Without any transformations. For all the networks we have implemented a
developmentally plausible Curriculum. We have used the Dataloader to generate data based on
the age groups(3, 6, 12 months) from the Dataset. Since the data in the smallest age group has
stronger effects of transformations defined as compared to higher age groups, details in the images
are lost initially which are recovered over transformations of increasing age groups.
This enables the model to strongly build its training foundation and later start picking up complex
information from the images.
We believe this setup simulates the development of infant vision over age.

![image](https://github.com/user-attachments/assets/b642248f-7dae-4c13-bd6a-752d5804223f)
