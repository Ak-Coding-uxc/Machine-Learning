#### Date:- 17 june 2026

# Link :- [video 2](https://youtu.be/jerPVDaHbEA?si=TAXziV6KKwl9sJYQ)

# Simple Linear Regression Algorithm

**Data scientist ke liye first topic hota h**

**Hypothesis ka hindi matlab "Parikalpana" (परिकल्पना) ya "Anuman" (अनुमान) hota hai**

**Submission :- Kisi cheez ko jama karna**

**Agenda**
1. What problem we are solving
2. Geometric intution:- figure or Diagram dikaye  jayege ki ham kya solve kar rahe h.
3. Mathematical inutitation

_<u>Note</u>:- Iss agenda se hi baki ki ml algorithm sikni chahiye._


## First Problem

- ML is 2 types 
    - Supervised
        - Regression :- Continous values
        - Classification - for category
    - Unsupervised

## Linear Regreesion
- can be solve with excel sheets , stastistic ke point of view se bhi solve kar sakte h

- mathamatical equation se samaj aayega

**1. What problem are we solving**  
for ex:- we have 2 feature  height and weight  
height*kg() on y axis // dependent feature  
weight*cm() on x axis // independent feature  
- in this we are predicted y axis values
- our main aim is to model ko train data se train karna fir ye model ek hypothesis banaega jaha per iss hypothesis ka main work hoga weight lena
or height predict karna(see image 1)

- our main aim is to create a best fit line in which all the difference between actual pooint and predicted point, submission of all the distance  called residual error should be very low
the submission and error

- ham sab residual error ka submission (adding) karte h jiska bhi kam aaya vo line best fit line hoti h.

- **Residual Error** => The difference b/w the actual point and predicted point.

- actual point = jaha actual value h
- predicted point = jaha per best fit line per value lie karti h.
- redi
_steps_
- train data provide kiya jata h
- model ko train karte h  
- fir hypothesis banaya jata h joh jata h jisme weight (i/p) diya jata h orr wo height(o/p) deta h. 

## Linear Regression start

<b><u>_image1_</u>:- Linear Regreesion Terminology</b>  
![alt text](<1.linear regression.png>)  

-- in short ham train data provide karte h model ko orr fir hypothesis hota h anuman lagaya jata h.

**working**
- linear regreesion data point mein ek best fit line bana dete h
- ye line model banata h jisko ham hypothesis bhi bol sakte h.
- staright line pe lie karti value ko predicted value bolte h
- actual value or predicted value mein difference ko residual error bolte h. 
- best fit line jab uska submission bahut kam hona chahiye.
- **Aim** :- is to find best fit line with minimal error  
    - 0 nhi hona chahiye.

### Best fit line
    - ye alag alag equation se dekh sakte h
- equation:- y(y ke upar cap h = ^) = mx + c  j
y = predicted point  
m = slope or coefficient  
{ ye hame bahut hi important information dete h , slope hame ye batata h ki 1 unit increase in x usse hamara slope kitna increase ho raha h in y.( 1 unit incer in x how many incre in y). this is slope and coefficient }# this is more imp   
c = interceipt ,  
 when x value is 0 wo y mein kitna mill raha h.
(when x value is 0 where besst fit line in intercepting y)  

y
  x

**Andrew NG** se ham sikh sakte h hypothesis  
=> h.theta(x) = theta0 + theta1 x  
x = data point(input feature) x value

<b><u>_image2_</u>:- Best Fit Line & Hypothesis Formula</b>  
![alt text](<2.Best Fit Line.png>)  


**Hypothesis Formula**  
_image 3_  
![alt text](3.hypothesis.png)
- x is data point , input feature





#### How to find best fit line?
- ek straight line se start karte h , fir uss line ko adjust karte h
- solve cost function:
- predict point - actural point) there difference minimize is our target.

- y is a linear fn. of x


# Kuch bhi samaj nhi aaya , dubara dekhonga. video ko

# Bookmark = 17 min 


