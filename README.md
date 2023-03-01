# ML-Based-Multipal-Price-Prediction-System
:wave: Hi All :smile: it's my first ML project which is combination of different price prediction models using machine learning.

I deployed my moodel using streamlit.[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)]

In below video you can check the workflow and overview of this project.:point_down:

https://user-images.githubusercontent.com/126685886/222221465-6658c7ba-60d9-4a45-87e5-d11ffa556bb5.mp4

## List Of ML Models :

### 1.Dimaond Price Prediction.
### 2.Domastic Flight Price Prediction.
### 3.US House Price prediction.

>### 1.Dimaond Price Prediction.
>I have considered the classic Diamonds dataset which contains the prices and other attributes of almost 54,000 diamonds and this dataset is hosted on Kaggle. The dataset contains 53940 rows and 10 variables.let’s have a look into the variables & their definitions.

**Feature description:**

**price** price in US dollars ($326--$18,823)This is the target column containing tags for the features. 

**The 4 Cs of Diamonds:-**

**carat (0.2--5.01)** The carat is the diamond’s physical weight measured in metric carats.  One carat equals 1/5 gram and is subdivided into 100 points. Carat weight is the most objective grade of the 4Cs. 

**cut (Fair, Good, Very Good, Premium, Ideal)** In determining the quality of the cut, the diamond grader evaluates the cutter’s skill in the fashioning of the diamond. The more precise the diamond is cut, the more captivating the diamond is to the eye.  

**color**, from J (worst) to D (best) The colour of gem-quality diamonds occurs in many hues. In the range from colourless to light yellow or light brown. Colourless diamonds are the rarest. Other natural colours (blue, red, pink for example) are known as "fancy,” and their colour grading is different than from white colorless diamonds.  

**clarity (I1 (worst), SI2, SI1, VS2, VS1, VVS2, VVS1, IF (best))** Diamonds can have internal characteristics known as inclusions or external characteristics known as blemishes. Diamonds without inclusions or blemishes are rare; however, most characteristics can only be seen with magnification.  

**Dimensions**

**x** length in mm (0--10.74)

**y** width in mm (0--58.9)

**z** depth in mm (0--31.8)


![Screenshot 2023-03-02 003943](https://user-images.githubusercontent.com/126685886/222240510-d2c3158b-f58a-40d9-9c1a-b087745d8218.png)


**depth** total depth percentage = z / mean(x, y) = 2 * z / (x + y) (43--79) The depth of the diamond is its height (in millimetres) measured from the culet (bottom tip) to the table (flat, top surface).

**table** width of the top of the diamond relative to widest point (43--95)

A diamond's table refers to the flat facet of the diamond seen when the stone is face up. The main purpose of a diamond table is to refract entering light rays and allow reflected light rays from within the diamond to meet the observer’s eye. The ideal table cut diamond will give the diamond stunning fire and brilliance.

