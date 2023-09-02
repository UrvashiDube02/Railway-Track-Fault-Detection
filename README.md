# Railway-Track-Fault-Detection

**OBJECTIVE**
<p align = "justify">
The efficiency of the tracks plays an important role in the functioning of the railway system. I have proposed an effective solution to detect the railway track crack and decrease the number of accidents. A crack detection algorithm is proposed which will improvise the existing system of manually checking the track health. Our model is designed to capture images of the tracks and check for the minor cracks. It will also estimate the crack length and give report of railway track health.
</p>

**MOTIVATION**
<p align = "justify">
In countries like India, the most widely used and common mode of transport for the people is railway transport. As per the current scenario of train accidents we often observe in the news that railway accidents are quite common. It has been seen that approximately 60% of the rail accidents are caused due to derailment, and 90% of them are caused due to flaws on the railway track. Those minor cracks are unnoticed by the track-man of the railway department who walks 16km/day along the railway track for the inspection of the track. This method of inspection is quite unreliable. The manual checking railway tracks leads to many accidents and manual ignorance also responsible for this. Broken rails can occur because of a small defect in the rail or where the rail is subject to excessive loads. Small defects can grow under repetitive loading – more than three million axles (part of a wheel) pass over the rail every year on a busy mainline. Defects in rails; shatter cracks; detailed fracture; shelling; headchecks; dark-spots; wear. Resistance to structural failure as well as excessive wear is the major criterion involved in the assessment of the structural integrity of rails.
</p>

**BACKGROUND**
<p align = "justify">
The prerequisites to build the project mainly includes MATLAB software and image processing. This is because the major part of the project includes processing the image of the 
track to locate and estimate the length of the crack. Processing the image to get the maximum clarity is one of the tough tasks. The main aim of the project is to estimate the major crack length in the pipe. Some cracks are not visible to the naked eye, this method becomes an effective method to detect the crack and estimate its length.
</p>

**PROJECT DESCRIPTION**
<p align = "justify">
The project is developed to find the cracks and estimate the length of the major crack in the track. Multiple images of tracks are found and processed in MATLAB software. Different filters like median filter and bot hat filters are applied on the image to reduce the noise in the image. One of the goals of the project is to increase the clarity of the image, focus on the track at the first stage and then focus on the crack of the track, ultimately find the crack length and displaying it on the image. There is a flexibility in MATLAB, to set an image tool to estimate the crack length of the desired crack on the track.
</p>

**LITERATURE REVIEW**
<p align = "justify">
1. Tastimur, canan& akin,erhan&karaköse, m. & Aydin, ilhan. (2015). Detection of rail faults using morphological feature extraction-based image processing. 2015 23rd signal 
processing and communications applications conference, siu2015 -proceedings. 1244-1247.10.1109/siu.2015.7130063. Determining the rail's breakdown has a big importance in railway access. The breakdowns of rails bring about problems such as insecurity, delay of access, and expenditure. In this work, in order to determine the breakdowns of rails using morphological feature extraction-based image processing algorithm is offered. The rail is determined through applying the image processing methods and transform to the received images of rail. Head check breakage, apletilikand undulation of defects are determined by proposed method. Faulty regions is determined through extracting features of regions in images by applying morphological operations to detected rail images. In this work, all steps of the offered method is applied to the images of rail under different direction and lighting, and with maximum accuracy and minimum working time, the results are acquired
</p>
<p align = "justify">
2. Molodova, maria & li, zili&núñez, alfredo & dollevoet, rolf. (2013). Monitoring the railway infrastructure: detection of surface defects using wavelets. IEEE conference on
intelligent transportation systems, proceedings, itsc. 1316-1321. 10.1109/itsc.2013.6728413. For monitoring the conditions of railway infrastructures, axle box acceleration (aba) measurements onboard of trains is used. In this paper, the focus is on the early detection of short surface defects called squats. Different classes of squats are classified based on the response in the frequency domain of the abasignal, using the wavelet power spectrum. For the investigated dutchtracks, the power spectrum in the frequencies between 1060-1160hz and around300hz indicate existence of a squat and also provide information of whether a squat is light, moderate or severe. The detection procedure is then validated relying on real-life measurements of abasignals from measuring trains, and data of severity and location of squats obtained via a visual Inspection of the tracks. Based on the real-life tests in the Netherlands, the hit rate of the system for light squats is higher than 78%, with a false alarm rate of 15%. In the case of severe squats, the hit rate was 100% and zero false alarms
</p>
<p align = "justify">
3. Saurabh Srivastava, Ravi Prakash Chourasia, Prashant Sharma, Syed Imran Abbas, Nitin Kumar Singh, “Railway Track Crack detection vehicle”, IARJSET, Vol. 4, pp. 145-148, Issued in 2, Feb 2017. This paper is intended to propose a device which can automatically detect any cracks in railway tracks. The created device will be attached into the train engine and it consists of a sensor that will detect crack a few meters away and as soon as any crack is detected the train driver will get a signal so he can apply emergency brakes along with it the authorities will be notified with the correct location at which the fault is detected. The proposed approach is benign because the Indian Railway is the biggest railway network in Asia so there should be an efficacious methodology to detect and correct any kind of mishap due to railway tracks. The proposed system is different from others because the device is embedded in the train itself, which could reduce manual work and labor wages. This project aims at the eradication of any kind of casualty in Indian Railway and if this system creates, even if a small refinement it will make a difference in the nation.
</p>
<p align = "justify">
4. Rizvi Aliza Raza, Khan Pervez Rauf, Ahmad Shafeeq, “Crack detection in Railway track using Image processing”, IJARIIT, Vol. 3, pp. 489-496, Issue4. Computer vision can provide many potential advantages over manual methods of railway track inspection. Great levels of performance can be achieved through the automation of inspection using computer vision systems, as they allow scalable, quick, and cost-effective solutions to tasks otherwise unsuited to humans. At a minimum, railway track components can be objectively and quantitatively inspected, as the system does not suffer from fatigue or the subjectivity inherent with human inspectors. The digital nature of the data collection involved with a computer vision based method, archiving inspection results and trending of the data becomes feasible, leading to more advanced failure prediction models for maintenance scheduling and a more thorough understanding of railway track structure. In this research paper, a computer vision based method is presented. A system has been suggested which can periodically take images of the railway tracks and compared with the existing database of nonfaulty track images on a continuous basis. If a fault arises in the track section, the system will automatically detect the fault and necessary actions can be taken, to avoid any mishappening.
</p>

**TECHNICAL SPECIFICATION**
<p align = "justify">
Our project replaces manual inspection of the track section, by automatic inspection to detect any cracks in the track section. This will help to detect cracks immediately and reduce the possibilities of any mishaps. •The system would be automatic and will require less manual intervention, utmost efficiency of the system can be ensured. •Low-lighting and contrast-based image enhancement techniques make sure that the system is extremely accurate
</p>
<p align = "justify">
• The project is therefore feasible and is not susceptible to the judgement of the technicians

• In practical scenario’s the images of the tracks could be captured either manually or by drone cameras. The drone cameras also have a high-resolution capacity which could hover over the tracks to capture the images of the tracks.

• Images of various tracks have been collected from the internet. The image has been processed, hence converted into a RGB image. The image is also compressed according to the 
required size for image processing. Parameter are being monitored and different algorithms are being tested on the image to detect the crack and its length
</p>

**DESIGN APPROACH AND DETAILS**
<p align = "justify">
Those minor cracks are unnoticed by the track-man of the railway department who walks 16km/day along the railway track for the inspection of the track. This method of inspection is quite unreliable. Railway track image is taken and processed in MATLAB software. Initially taken image is converted into a contrast stretched image. Then the RGB colour image is converted into grayscale image. A fine-tuned image is obtained by applying median filter. BOT hat output image is obtained by applying another filter. The resultant image is converted into a binary image. The background noise is reduced by applying filters. The obtained thinned image is called as skeleton image. The skeleton image is processed for cracks detection. Crack length is also estimated by crack detection algorithm.
</p>
<p align = "justify">
• Image is processed in MATLAB software.

• Chosen image is converted into a contrast stretched image.10 | P a g e

• The RGB color image s converted into grayscale image

• Median filter is applied on the image to get a fine-tuned image

• Another filter is applied to get a bot hat output image

• Obtained image is converted into a binary image 

• The background noise is reduced by applying filters 

• The thinned clear image is ready for processing of cracks.

• Abbreviations and Acronyms
</p>

**FLOWCHART**

![image](https://user-images.githubusercontent.com/87383888/125571612-1888fcf5-7dbb-46f7-9ea3-4a2aa39a00be.png)

Fig.2. Flowchart of Track fault Detection Algorithm


**CODE**

I = imread('Railway_track_photo.jpg'); %Read the image

figure(1)

imshow(I) %Printing the image

title('Original Image') 

Istrech =imadjust(I,stretchlim(I)); %Adjust image intensity values or colourmap.

figure(2)

imshow(Istrech) %Display image 

title('Contrast stretched image')

Igray_s = rgb2gray(Istrech); %Convert RGB image or colormap to grayscale

figure(3)

imshow(Igray_s,[]) %Display image 

title('RGb to Gray (contrast stretched)');

K = medfilt2(Igray_s); %Performs median filtering

figure(4)

imshow(K)

title('Applying Median filter')

se = strel('disk',4); %Creates a structuring element

bothatimg = imbothat(K,se); %Performs morphological bottom hat filtering

figure(5);

imshow(bothatimg);

title('Bot Hat Output Image')

BW = imbinarize(bothatimg,0.07); %Binarize grayscale 2D image or 3D volume by 

thresholding

figure(6)

imshow(BW);

title('Binary Image')

BW2 = bwareaopen(BW,1000); %Removes from a binary image all connected 

components

%(objects) that have fewer than P pixels

figure(7)

imshow(BW2);

title('Noise Reduction')

BW4 = bwmorph(BW2,'skel',Inf);

figure()

imshow(BW4)

title('Thinned image(Skeleton)')

measurements = regionprops(BW4,'Area');%Area operation tothe binary image BW4

allCrackLengths = [measurements.Area];

Total_Length = sum(allCrackLengths);

h = imdistline; %Creates a draggable distance tool on the currentaxes12 | P a g e

impixelinfo; %Creates a pixel information tool in the current figure

imtool(BW4) %Displays the binary image BW

The standards taken into account is the 6850 mm = 685.0 cm

**CONSTRAINTS, ALTERNATIVES AND TRADEOFFS**
<p align = "justify">
The major constraint in the project is the angle at which the image of the track is captured. The alternatives for this project are drone images can be captured which can capture precise images at specific angles. Another major constraint is that the images should be captured in such a way that the image majorly focuses on the track with the track, background details of the ground stones or other fillers may hamper the efficiency of image processing of the model. The cleanliness of the track is also one of the requirements. The trade-off in this project is finding the optimum image from a huge dataset, to get the maximum results.
</p>

**PROJECT DEMONSTRATION**

I have attached the step-by-step photos of all the designs:

![image](https://user-images.githubusercontent.com/87383888/125571913-a5c9cc52-d123-4701-8f70-62d004a4d367.png)

![image](https://user-images.githubusercontent.com/87383888/125571925-8a575fd0-2cd6-4cc9-b6fb-796c8fe2c4ae.png)

**COST ANALYSIS / RESULT & DISCUSSION**
Cost Analysis -
<p align = "justify">
My project would only involve costs for the installation of the camera and for the computer vision system. The camera would cost about 1k-2.5k and the cost of procuring a computer vision system would be approximately 15k. Therefore, the project is cost-effective as it reduces expenditure on labour costs. The program will run on MATLAB software and will provide results on the screen. Laptop (40k) Total Cost: Practical purposes: Rs. 56-57.5KIn case of simulation we take a dataset of images of railway tracks available on the internet. According to various surveys, a computer vision investment can be recovered in less than a year. Also, compared to the economic damage and the loss of lives that faults in railway tracks can cause, the costs incurred are reasonable.To assess if the model is successful:
</p>
•Once the crack is identified, the crack length is noted. 

•Then a team is sent to analyze the crack.

•On inspecting the crack, the team decides to weld the crack if the crack is not severe.

•In severe cases where there could be a derailment, the whole part has to be changed.

•Minute cracks will be identified through image processing which cannot be seen through the naked eye. If the model fails to identify the crack at the first go, the model is run several times on the image to get better accuracy.


**Result and Discussion**
<p align = "justify">
Various photographs of tracks are taken and the original image with crack is processed in MATLAB. If the crack is found the image is contrast stretched and RGB to gray image is obtained. A median-filtered image is obtained by applying the median filter. A BOT HAT output image of the crack of the track is obtained and on binary image noise reduction techniques are applied via noise filter. A thinned image or skeleton image of a crack is visualized, and the crack length is also calculated and displayed. This proposed crack detection algorithm can detect the cracks on the tracks and calculate the crack length. The value of crack length can be used to measure the severity of the crack and the life of the crack.    
</p>
<p align = "justify">
The obtained images of MATLAB are shown in Fig.4 to Fig.12. My project would only involve costs for the installation of the camera and for the computer vision system. The camera would cost about 1k-2.5k and the cost of procuring a computer vision system would be approximately 15k. Therefore, the project is cost-effective as it reduces expenditure on labour costs. The program will run on MATLAB software and will provide results on the screen. In the case of simulation, we take a dataset of images of railway tracks available on the internet. According to various surveys, a computer vision investment can be recovered in less than a year. Also, compared to the economic damage and the loss of lives that faults in railway tracks can cause, the costs incurred are reasonable. For the image used, we have found the crack length is 209.06 cm.
</p>

**SUMMARY**
<p align = "justify">
I have performed a detailed literature survey. Collected the images of the faulty tracks and modified the images for identification of the crack. Removed all the background details and focused only on the image of the track. We identified all the cracks and applied different filters to get a clear image. We located the crack in the image and fine-tuned the image for better crack length estimation.
I have converted the image into pixels and estimated the crack length and the gap length. At the final stage we displayed all the images at different stages and the crack length in the modified image. The identified crack length can be used by inspection officers to estimate the risk of whether the tracks could either be replaced or welded to prevent derailments and accidents. Further, we found the system very cost-effective.
</p>
