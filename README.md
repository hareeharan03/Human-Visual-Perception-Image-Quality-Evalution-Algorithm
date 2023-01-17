
# OVERVIEW 

### What is all about the Human Visual Perception Image Quality Evalution Algorithm

                Humans have always seen the world in colour. In the last few decades, there has been 
        a rapid and enormous transition from black-and-white images to colour ones. Image 
        colourisation aims to produce a natural-looking colour image from a given grey-scale image, 
        which remains a challenging problem. As the colourisation of the black & white images 
        evolves, the metrics to evaluate the quality of the colourised images have to be evolved one 
        step ahead. 

                Well-known objective evaluation metrics including MSE, PSNR, SSIM, UIQM, and QSSIM, 
        which fall under FR. for measuring image quality metrics will measure the error between original 
        and processed images. One of these objective measures standard and significant limitations is 
        that they require reference images to evaluate the quality of grayscale images by fidelity to 
        the original image. This algorithm is a novel approach based on the clear combination of 
        mathematical formulae and deep learning to evaluate and provide an overall score for the 
        colourised image by getting the object's colour distribution. That will be learned and 
        transformed into a database to act as the reference data, which has plausible colours for 
        each label.

### How it differs and solve existing image colorization techniques drawbacks

                One of the standards and significant limitations of these objective measures is that 
        they only evaluate the quality of grayscale images and predict the perceived difference between 
        a distorted image and a Ground truth image. So it is difficult to measure the quality of 
        colourized grey scale images taken back in the 18th century since the Ground truth image, which 
        will act as a reference image, will not be available

### What is the Outcome
                The algorithm is an evaluation metric to evaluate the quality of an image with 
        no reference image using deep learning, computer vision, and a mathematical formula by analysing 
        and extracting the plausible colour of various objects from real-world photos using segmentation. 
        As a result, each label will have its colour distribution. Finally, utilise those colour 
        distributions to assess the colour plausibility of objects in the colourized test picture to 
        produce an overall score.
