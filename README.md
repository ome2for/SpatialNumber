##  Spatial number, multi-dimensional complex

##  by Hong-lin Yang
##  RIPED, CNPC
  
###  1. Definition and expression
  
>We know that a complex number **Z=a+bi** indicates a point **(a, b)** in the complex plane, hence the modulus of the vector from (0,0) to (a,b) i.e  **<img src="https://latex.codecogs.com/gif.latex?&#x5C;vert%20&#x5C;overrightarrow{Z}%20&#x5C;vert"/>** is **<img src="https://latex.codecogs.com/gif.latex?r=&#x5C;sqrt{a^2+b^2}"/>** and it's argument is **<img src="https://latex.codecogs.com/gif.latex?&#x5C;theta=&#x5C;arctan&#x5C;left(&#x5C;frac{b}{a}&#x5C;right)"/>**, which is the angle turning conterclockwisely away from the real axis **X**. Regardless of it's periodicity, **<img src="https://latex.codecogs.com/gif.latex?&#x5C;theta&#x5C;in{&#x5C;left(-&#x5C;pi,%20&#x5C;pi&#x5C;right]}"/>** . Expolently expressed it is as **<img src="https://latex.codecogs.com/gif.latex?Z=re^{{&#x5C;theta}i}"/>**。
  
>In the same way, we define **S=a+bi+cj** as a point **(a, b, c)** in three dimensional space, where the real part **a** is on axis **X**,  the first imaginary part **b** is on axis **Y**  and the second imaginary part **c** is on axis **Z**. The modulus of vector **<img src="https://latex.codecogs.com/gif.latex?&#x5C;overrightarrow{S}"/>** is **<img src="https://latex.codecogs.com/gif.latex?r=&#x5C;sqrt{a^2+b^2+c^2}"/>**. If let  **<img src="https://latex.codecogs.com/gif.latex?r_1=&#x5C;sqrt{a^2+b^2}"/>** , called first modulus, indicating the modulus of projective vector in <img src="https://latex.codecogs.com/gif.latex?XY"/> plane, then **<img src="https://latex.codecogs.com/gif.latex?&#x5C;theta_1=&#x5C;arctan&#x5C;left(&#x5C;frac{b}{a}&#x5C;right)"/>**, indicating the angle turning conterclockwisely away from the real axis **X**, is ranged in **<img src="https://latex.codecogs.com/gif.latex?&#x5C;left(-&#x5C;pi,%20&#x5C;pi&#x5C;right]"/>**, while  **<img src="https://latex.codecogs.com/gif.latex?&#x5C;theta_2=&#x5C;arctan&#x5C;left(&#x5C;frac{c}{r_1}&#x5C;right)"/>** indicates the angle leaving the **X-Y** plane for **Z**  in range **<img src="https://latex.codecogs.com/gif.latex?&#x5C;left(-&#x5C;frac{&#x5C;pi}{2},%20&#x5C;frac{&#x5C;pi}{2}&#x5C;right]"/>** . We call **<img src="https://latex.codecogs.com/gif.latex?&#x5C;theta_1"/>** the first argument and **<img src="https://latex.codecogs.com/gif.latex?&#x5C;theta_2"/>** the second argument. So in polary coordinate the expression is **<img src="https://latex.codecogs.com/gif.latex?S=re^{&#x5C;theta_1{i}+&#x5C;theta_2{j}}"/>**
  
>Now we generalize the idea above as the following statement: **<img src="https://latex.codecogs.com/gif.latex?S=a_0+a_1&#x5C;bar{&#x5C;imath}+a_2&#x5C;acute{&#x5C;imath}+a_3&#x5C;check{&#x5C;imath}+a_4&#x5C;grave{&#x5C;imath}+&#x5C;cdots&#x5C;cdots+a_n&#x5C;hat{&#x5C;imath}"/>** (the **<img src="https://latex.codecogs.com/gif.latex?&#x5C;wedge"/>** on top of **<img src="https://latex.codecogs.com/gif.latex?&#x5C;imath"/>** should be **n**)
represents a point **<img src="https://latex.codecogs.com/gif.latex?(a_0,%20a_1,%20a_2,%20&#x5C;cdots&#x5C;cdots,%20a_n%20)"/>** in **n+1** dimensional space. Such defined number is called **n+1** dimensional ***spatial number***.
If let  **<img src="https://latex.codecogs.com/gif.latex?r_0=a_0"/>**,
**<img src="https://latex.codecogs.com/gif.latex?r_1=&#x5C;sqrt{a_0^2+a_1^2}"/>**,(first modulus)
**<img src="https://latex.codecogs.com/gif.latex?&#x5C;cdots&#x5C;cdots"/>**,
**<img src="https://latex.codecogs.com/gif.latex?r_{n-1}=&#x5C;sqrt{a_0^2+a_1^2+&#x5C;cdots&#x5C;cdots+a_{n-1}^2}"/>**,
and  **<img src="https://latex.codecogs.com/gif.latex?r=&#x5C;sqrt{a_0^2+a_1^2+&#x5C;cdots&#x5C;cdots+a_n^2}"/>**,
then **<img src="https://latex.codecogs.com/gif.latex?&#x5C;theta_1=&#x5C;arctan&#x5C;left(&#x5C;frac{a_1}{r_0}&#x5C;right)"/>**,(first argument)
 **<img src="https://latex.codecogs.com/gif.latex?&#x5C;theta_2=&#x5C;arctan&#x5C;left(&#x5C;frac{a_2}{r_1}&#x5C;right)"/>**,**<img src="https://latex.codecogs.com/gif.latex?&#x5C;cdots&#x5C;cdots"/>**,
 and **<img src="https://latex.codecogs.com/gif.latex?&#x5C;theta_n=&#x5C;arctan&#x5C;left(&#x5C;frac{a_n}{r_{n-1}}&#x5C;right)"/>**,
It also can be expressed in expolent form as **<img src="https://latex.codecogs.com/gif.latex?S=re^{&#x5C;theta_1&#x5C;bar{&#x5C;imath}+&#x5C;theta_2&#x5C;acute{&#x5C;imath}+&#x5C;theta_3&#x5C;check{&#x5C;imath}+&#x5C;cdots&#x5C;cdots+&#x5C;theta_n&#x5C;hat{&#x5C;imath}}"/>**.
  
>To simplify the expression, let **<img src="https://latex.codecogs.com/gif.latex?a"/>** represent the sequence **<img src="https://latex.codecogs.com/gif.latex?&#x5C;left[a_1,%20a_2,%20&#x5C;cdots&#x5C;cdots,%20a_n&#x5C;right]"/>** (called **spatial-position-row**) and **<img src="https://latex.codecogs.com/gif.latex?I"/>** represent the sequence **<img src="https://latex.codecogs.com/gif.latex?&#x5C;left[&#x5C;bar{&#x5C;imath},%20&#x5C;acute{&#x5C;imath},%20&#x5C;check{&#x5C;imath},%20&#x5C;grave{&#x5C;imath},%20&#x5C;cdots&#x5C;cdots,%20&#x5C;hat{&#x5C;imath}&#x5C;right]"/>**  (called **spatial-axis-collum**), so that **<img src="https://latex.codecogs.com/gif.latex?S=a_0+aI"/>**, where **<img src="https://latex.codecogs.com/gif.latex?aI"/>** implies the dot product of **<img src="https://latex.codecogs.com/gif.latex?a"/>** and **<img src="https://latex.codecogs.com/gif.latex?I"/>**. We call it the ***spatial-position expression***.  If insert the real part **a_0** into **<img src="https://latex.codecogs.com/gif.latex?a"/>** and **<img src="https://latex.codecogs.com/gif.latex?1"/>**  into **<img src="https://latex.codecogs.com/gif.latex?I"/>**, i.e. **<img src="https://latex.codecogs.com/gif.latex?a=&#x5C;left[a_0,%20a_1,%20&#x5C;cdots&#x5C;cdots,%20&#x5C;right]"/>** and **<img src="https://latex.codecogs.com/gif.latex?&#x5C;hat{I}=&#x5C;left[1,%20&#x5C;bar{&#x5C;imath},%20&#x5C;cdots&#x5C;right]"/>**, we can get the simpliest form **<img src="https://latex.codecogs.com/gif.latex?S=a&#x5C;hat{I}"/>**, which is called ***all-position expression***.
>Parellely in expolent expression, if **<img src="https://latex.codecogs.com/gif.latex?&#x5C;theta=&#x5C;left[&#x5C;theta_1,%20&#x5C;theta_2,%20&#x5C;cdots&#x5C;cdots,%20&#x5C;theta_n&#x5C;right]"/>**,  then **<img src="https://latex.codecogs.com/gif.latex?S=re^{&#x5C;theta{I}}"/>**, which is called ***spatial-phrase expression***. Since **<img src="https://latex.codecogs.com/gif.latex?r&#x5C;gt{0}"/>**, so if let **<img src="https://latex.codecogs.com/gif.latex?&#x5C;theta_0=&#x5C;ln{r}"/>** and **<img src="https://latex.codecogs.com/gif.latex?&#x5C;theta=&#x5C;left[&#x5C;theta_0,%20&#x5C;theta_1,%20&#x5C;theta_2,%20&#x5C;cdots&#x5C;cdots,%20&#x5C;theta_n&#x5C;right]"/>**,  then **<img src="https://latex.codecogs.com/gif.latex?S=e^{&#x5C;theta{&#x5C;hat{I}}}"/>**, that is called ***all-phrase expression***.
### 2. Operation rules
  
 - ##### Addition and subtraction
>>Spatial numbers follow the same rules of addition and subtraction as applied in complex numbers, that is to add or subtract each part respectively.
**<img src="https://latex.codecogs.com/gif.latex?S=a_0+a_1&#x5C;bar{&#x5C;imath}+a_2&#x5C;acute{&#x5C;imath}+&#x5C;cdots%20=a_0+aI"/>**
**<img src="https://latex.codecogs.com/gif.latex?P=b_0+b_1&#x5C;bar{&#x5C;imath}+b_2&#x5C;acute{&#x5C;imath}+&#x5C;cdots%20=b_0+bI"/>**
**<img src="https://latex.codecogs.com/gif.latex?S{&#x5C;pm}P=(a_0{&#x5C;pm}b_0)+(a_1{&#x5C;pm}b_1)&#x5C;bar{&#x5C;imath}+(a_2{&#x5C;pm}b_2)&#x5C;acute{&#x5C;imath}+&#x5C;cdots=(a_0{&#x5C;pm}b_0)+(a{&#x5C;pm}b)I"/>**
While in expolent expression, it has to be transformed in the follwing way:
If **<img src="https://latex.codecogs.com/gif.latex?S=re^{&#x5C;theta_1{&#x5C;bar{&#x5C;imath}}+&#x5C;theta_2{&#x5C;acute{&#x5C;imath}}+&#x5C;cdots+&#x5C;theta_n{&#x5C;hat{&#x5C;imath}}}=re^{&#x5C;theta{I}}"/>** and
**<img src="https://latex.codecogs.com/gif.latex?P={&#x5C;rho}e^{&#x5C;varphi_1&#x5C;bar{&#x5C;imath}+&#x5C;varphi_2&#x5C;acute{&#x5C;imath}+&#x5C;cdots+&#x5C;varphi_n&#x5C;hat{&#x5C;imath}}={&#x5C;rho}e^{&#x5C;varphi{I}}"/>**
  
>>then **<img src="https://latex.codecogs.com/gif.latex?a_0=r&#x5C;cos{&#x5C;theta_1}&#x5C;cos{&#x5C;theta_2}&#x5C;cdots&#x5C;cos{&#x5C;theta_n}"/>**
**<img src="https://latex.codecogs.com/gif.latex?b_0=&#x5C;rho&#x5C;cos{&#x5C;varphi_1}&#x5C;cos{&#x5C;varphi_2}&#x5C;cdots&#x5C;cos{&#x5C;varphi_n}"/>**
  
>>**<img src="https://latex.codecogs.com/gif.latex?a_1=r&#x5C;sin{&#x5C;theta_1}&#x5C;cos{&#x5C;theta_2}&#x5C;cos{&#x5C;theta_3}&#x5C;cdots&#x5C;cos{&#x5C;theta_n}"/>**
**<img src="https://latex.codecogs.com/gif.latex?b_1=&#x5C;rho&#x5C;sin{&#x5C;varphi_1}&#x5C;cos{&#x5C;varphi_2}&#x5C;cdots&#x5C;cos{&#x5C;varphi_n}"/>**
  
>>**<img src="https://latex.codecogs.com/gif.latex?a_2=r&#x5C;sin{&#x5C;theta_2}&#x5C;cos{&#x5C;theta_3}&#x5C;cdots&#x5C;cos{&#x5C;theta_n}"/>**
**<img src="https://latex.codecogs.com/gif.latex?b_2=&#x5C;rho&#x5C;sin{&#x5C;varphi_2}&#x5C;cos{&#x5C;varphi_3}&#x5C;cdots&#x5C;cos{&#x5C;varphi_n}"/>**
**<img src="https://latex.codecogs.com/gif.latex?&#x5C;cdots&#x5C;cdots"/>**
**<img src="https://latex.codecogs.com/gif.latex?a_{n-1}=r&#x5C;sin{&#x5C;theta_{n-1}}&#x5C;cos{&#x5C;theta_n}"/>**
**<img src="https://latex.codecogs.com/gif.latex?b_{n-1}=&#x5C;rho{&#x5C;sin{&#x5C;theta_{n-1}}&#x5C;cos{&#x5C;theta_n}}"/>**
**<img src="https://latex.codecogs.com/gif.latex?a_n=r&#x5C;sin{&#x5C;theta_n}"/>**
**<img src="https://latex.codecogs.com/gif.latex?b_n=&#x5C;rho&#x5C;sin{&#x5C;varphi_n}"/>**
For the sake of simplicity, we initiatively define two functions:
The first is **<img src="https://latex.codecogs.com/gif.latex?Recursive-cosine"/>**, difined  as:
**<img src="https://latex.codecogs.com/gif.latex?Recos&#x5C;theta=&#x5C;cos{&#x5C;theta_1}&#x5C;cos{&#x5C;theta_2}&#x5C;cdots&#x5C;cos{&#x5C;theta_n}"/>**, where
**<img src="https://latex.codecogs.com/gif.latex?&#x5C;theta=[&#x5C;theta_1,%20&#x5C;theta_2,%20&#x5C;cdots,%20&#x5C;theta_n]"/>**  
and the second is **<img src="https://latex.codecogs.com/gif.latex?Recursive-sine"/>** function , defined as:
**<img src="https://latex.codecogs.com/gif.latex?Resin&#x5C;theta=[&#x5C;sin{&#x5C;theta_1}&#x5C;cos{&#x5C;theta_2}&#x5C;cdots&#x5C;cos{&#x5C;theta_n},&#x5C;sin{&#x5C;theta_2}&#x5C;cos{&#x5C;theta_3}&#x5C;cdots&#x5C;cos{&#x5C;theta_n},
&#x5C;sin{&#x5C;theta_3}&#x5C;cos{&#x5C;theta_4}&#x5C;cdots&#x5C;cos{&#x5C;theta_n},
&#x5C;cdots&#x5C;cdots,
&#x5C;sin{&#x5C;theta_n}
]"/>**
therefore we can get the follwing expression:
**<img src="https://latex.codecogs.com/gif.latex?S=re^{&#x5C;theta{I}}=r(Recos&#x5C;theta+IResin&#x5C;theta)"/>**
**<img src="https://latex.codecogs.com/gif.latex?P=&#x5C;rho{e^{&#x5C;varphi{I}}}=&#x5C;rho(Recos&#x5C;varphi+IResin&#x5C;varphi)"/>**
**<img src="https://latex.codecogs.com/gif.latex?S{&#x5C;pm}P=(rRecos{&#x5C;theta}{&#x5C;pm}{&#x5C;rho}Recos{&#x5C;varphi})+(rResin{&#x5C;theta}{&#x5C;pm}{&#x5C;rho}Resin{&#x5C;varphi})I"/>**
  
 - #### multiplication and devision
 >>Before inquiring the method of multiplication on spatial numbers, we should review the rule applied in complex numbers:
 **<img src="https://latex.codecogs.com/gif.latex?Z_1=r_1e^{&#x5C;theta_1i}"/>**
 **<img src="https://latex.codecogs.com/gif.latex?Z_2=r_2e^{&#x5C;theta_2i}"/>**
 **<img src="https://latex.codecogs.com/gif.latex?Z_1Z_2=r_1r_2e^{(&#x5C;theta_1+&#x5C;theta_2)i}"/>**
 We assume that this rule still holds for spatial numbers, so the multiplication of two spatial numbers can be defined as following statement:
 if they are given in expolent expressions, here in **<img src="https://latex.codecogs.com/gif.latex?all-phrase-expression"/>**:
 **<img src="https://latex.codecogs.com/gif.latex?S=e^{&#x5C;theta{&#x5C;hat{I}}}"/>**
 **<img src="https://latex.codecogs.com/gif.latex?P=e^{&#x5C;varphi{&#x5C;hat{I}}}"/>**
 then  **<img src="https://latex.codecogs.com/gif.latex?SP=e^{(&#x5C;theta+&#x5C;varphi)&#x5C;hat{I}}"/>**
 Quite simple!
 However, it's truly not obvious to see how to multiply
 two spatial numbers given in coordinate expressions:
 **<img src="https://latex.codecogs.com/gif.latex?S=a_0+a_1&#x5C;bar{&#x5C;imath}+a_2&#x5C;acute{&#x5C;imath}+&#x5C;cdots=a&#x5C;hat{&#x5C;imath}"/>**
 **<img src="https://latex.codecogs.com/gif.latex?P=b_0+b_1&#x5C;bar{&#x5C;imath}+b_2&#x5C;acute{&#x5C;imath}+&#x5C;cdots=b&#x5C;hat{&#x5C;imath}"/>**
 where **<img src="https://latex.codecogs.com/gif.latex?a=[a_0,%20a_1,%20a_2,%20&#x5C;cdots,%20a_n]"/>**
 **<img src="https://latex.codecogs.com/gif.latex?b=[b_0,%20b_1,%20b_2,%20&#x5C;cdots,%20b_n]"/>**
 In fact, it is a recursive procession as follows:
 **<img src="https://latex.codecogs.com/gif.latex?S_1=a_0+a_1&#x5C;bar{&#x5C;imath}"/>**
 **<img src="https://latex.codecogs.com/gif.latex?S_2=a_0+a_1&#x5C;bar{&#x5C;imath}+a_2&#x5C;acute{&#x5C;imath}"/>**
 **<img src="https://latex.codecogs.com/gif.latex?&#x5C;cdots&#x5C;cdots"/>**
 **<img src="https://latex.codecogs.com/gif.latex?P_1=b_0+b_1&#x5C;bar{&#x5C;imath}"/>**
 **<img src="https://latex.codecogs.com/gif.latex?P_2=b_0+b_1&#x5C;bar{&#x5C;imath}+b_2&#x5C;acute{&#x5C;imath}"/>**
 **<img src="https://latex.codecogs.com/gif.latex?&#x5C;cdots&#x5C;cdots"/>**
 **<img src="https://latex.codecogs.com/gif.latex?S_1P_1=a_0b_0(1-&#x5C;frac{a_1b_1}{a_0b_0})+(a_1b_0+b_1a_0)&#x5C;bar{&#x5C;imath}"/>**(multiplication of two ordinary complex numbers )
 **<img src="https://latex.codecogs.com/gif.latex?S_2P_2=S_1P_1(1-&#x5C;frac{a_2b_2}{|S_1||P_1|})+(a_2|P_1|+b_2|S_1|)&#x5C;acute{&#x5C;imath}"/>**
  
 >>**<img src="https://latex.codecogs.com/gif.latex?S_3P_3=S_2P_2(1-&#x5C;frac{a_3b_3}{|S_2||P_2|})+(a_3|P_2|+b_3|S_2|)&#x5C;check{&#x5C;imath}"/>**
**<img src="https://latex.codecogs.com/gif.latex?&#x5C;cdots&#x5C;cdots"/>**
 if **<img src="https://latex.codecogs.com/gif.latex?SP=c_0+c_1&#x5C;bar{&#x5C;imath}+c_2&#x5C;acute{&#x5C;imath}+&#x5C;cdots=c&#x5C;hat{&#x5C;imath}"/>**
 then **<img src="https://latex.codecogs.com/gif.latex?c_0=a_0b_0(1-&#x5C;frac{a_1b_1}{a_0b_0})(1-&#x5C;frac{a_2b_2}{|S_1||P_1|})(1-&#x5C;frac{a_3b_3}{|S_2||P_2|})&#x5C;cdots(1-&#x5C;frac{a_nb_n}{|S_{n-1}||P_{n-1}|})=|S||P|&#x5C;frac{a_0b_0-a_1b_1}{|S_1||P_1|}&#x5C;frac{|S_1||P_1|-a_2b_2}{|S_2||P_2|}&#x5C;cdots&#x5C;frac{|S_{n-1}||P_{n-1}|-a_nb_n}{|S||P|}=|S||P|&#x5C;cos(&#x5C;theta_1+&#x5C;varphi_1)&#x5C;cos(&#x5C;theta_2+&#x5C;varphi_2)&#x5C;cdots&#x5C;cos(&#x5C;theta_n+&#x5C;varphi_n)"/>**
 **<img src="https://latex.codecogs.com/gif.latex?c_1=(a_1b_0+b_1a_0)(1-&#x5C;frac{a_2b_2}{|S_1||P_1|})(1-&#x5C;frac{a_3b_3}{|S_2||P_2|})&#x5C;cdots(1-&#x5C;frac{a_nb_n}{|S_{n-1}||P_{n-1}|})=|S||P|&#x5C;frac{a_1b_0+b_1a_0}{|S_1||P_1|}&#x5C;frac{|S_1||P_1|-a_2b_2}{|S_2||P_2|}&#x5C;cdots&#x5C;frac{|S_{n-1}||P_{n-1}|-a_nb_n}{|S||P|}=|S||P|&#x5C;sin(&#x5C;theta_1+&#x5C;varphi_1)&#x5C;cos(&#x5C;theta_2+&#x5C;varphi_2)&#x5C;cdots&#x5C;cos(&#x5C;theta_n+&#x5C;varphi_n)"/>**
**<img src="https://latex.codecogs.com/gif.latex?c_2=(a_2|P_1|+b_2|S_1|)(1-&#x5C;frac{a_3b_3}{|S_2||P_2|})&#x5C;cdots(1-&#x5C;frac{a_nb_n}{|S_{n-1}||P_{n-1}|})=|S||P|&#x5C;frac{a_2|P_1|+b_2|S_1|}{|S_2||P_2|}&#x5C;frac{|S_2||P_2|-a_3b_3}{|S_3||P_3|}&#x5C;cdots&#x5C;frac{|s_{n-1}||P_{n-1}|-a_nb_n}{|S||P|}=|S||P|&#x5C;sin(&#x5C;theta_2+&#x5C;varphi_2)&#x5C;cos(&#x5C;theta_3+&#x5C;varphi_3)&#x5C;cdots&#x5C;cos(&#x5C;theta_n+&#x5C;varphi_n)"/>**
**<img src="https://latex.codecogs.com/gif.latex?&#x5C;cdots&#x5C;cdots"/>**
**<img src="https://latex.codecogs.com/gif.latex?c_n=a_n|P_{n-1}|+b_n|S_{n-1}|=|S||P|&#x5C;frac{a_n|P_{n-1}|+b_n|S_{n-1}|}{|S||P|}=|S||P|&#x5C;sin(&#x5C;theta_n+&#x5C;varphi_n)"/>**
therefore **<img src="https://latex.codecogs.com/gif.latex?SP=|S||P|(Recos(&#x5C;theta+&#x5C;varphi)+IResin(&#x5C;theta+&#x5C;varphi))"/>**
  
In the recursive procession mentioned above,
  
- Discussion on imaginary unit
 >>**<img src="https://latex.codecogs.com/gif.latex?&#x5C;bar{&#x5C;imath}&#x5C;acute{&#x5C;imath}=?"/>**
 **<img src="https://latex.codecogs.com/gif.latex?&#x5C;bar{&#x5C;imath}&#x5C;rightarrow(0,%201,%200)%20,%20%20&#x5C;acute{&#x5C;imath}&#x5C;rightarrow(0,%200,%201)"/>**
 so **<img src="https://latex.codecogs.com/gif.latex?&#x5C;bar{&#x5C;imath}&#x5C;acute{&#x5C;imath}=&#x5C;acute{&#x5C;imath}"/>**
 or **<img src="https://latex.codecogs.com/gif.latex?&#x5C;bar&#x5C;imath=e^{&#x5C;frac{&#x5C;pi}{2}{&#x5C;bar{&#x5C;imath}}}"/>**
 **<img src="https://latex.codecogs.com/gif.latex?&#x5C;acute&#x5C;imath=e^{&#x5C;frac{&#x5C;pi}{2}{&#x5C;acute&#x5C;imath}}"/>**
 **<img src="https://latex.codecogs.com/gif.latex?&#x5C;bar&#x5C;imath&#x5C;acute&#x5C;imath=e^{&#x5C;frac{&#x5C;pi}{2}&#x5C;bar&#x5C;imath+&#x5C;frac{&#x5C;pi}{2}&#x5C;acute&#x5C;imath}=(&#x5C;cos&#x5C;frac{&#x5C;pi}{2}&#x5C;cos&#x5C;frac{&#x5C;pi}{2},%20&#x5C;sin&#x5C;frac{&#x5C;pi}{2}&#x5C;cos&#x5C;frac{&#x5C;pi}{2},%20&#x5C;sin&#x5C;frac{&#x5C;pi}{2})=&#x5C;acute&#x5C;imath"/>**
 Similarily, **<img src="https://latex.codecogs.com/gif.latex?&#x5C;bar&#x5C;imath&#x5C;check&#x5C;imath=&#x5C;acute&#x5C;imath&#x5C;check&#x5C;imath=&#x5C;bar&#x5C;imath&#x5C;acute&#x5C;imath&#x5C;check&#x5C;imath=&#x5C;check&#x5C;imath"/>**
  
 >>**<img src="https://latex.codecogs.com/gif.latex?&#x5C;acute&#x5C;imath^2=?"/>**
 Jast like **<img src="https://latex.codecogs.com/gif.latex?i^2=-1"/>** in complex number, **<img src="https://latex.codecogs.com/gif.latex?&#x5C;acute{&#x5C;imath}^2=-1"/>** still holds. In fact, **<img src="https://latex.codecogs.com/gif.latex?&#x5C;acute{&#x5C;imath}^2=-(&#x5C;cos{&#x5C;theta}+&#x5C;bar{&#x5C;imath}&#x5C;sin{&#x5C;theta})"/>**, where **<img src="https://latex.codecogs.com/gif.latex?&#x5C;theta&#x5C;in(-&#x5C;pi,%20&#x5C;pi]"/>**, i.e it is an inverse  unit circle in the complex plane.
 Similarily, **<img src="https://latex.codecogs.com/gif.latex?&#x5C;check{&#x5C;imath}^2=-e^{&#x5C;theta{&#x5C;bar{&#x5C;imath}}+&#x5C;varphi&#x5C;acute{&#x5C;imath}}"/>**, representing the inverse unit sphere in 3-D space.
  
  
 >>**<img src="https://latex.codecogs.com/gif.latex?&#x5C;frac{1}{&#x5C;acute{&#x5C;imath}}=?"/>**
**<img src="https://latex.codecogs.com/gif.latex?&#x5C;frac{1}{&#x5C;acute{&#x5C;imath}}=e^{(0-&#x5C;frac{&#x5C;pi}{2})}=-&#x5C;acute{&#x5C;imath}"/>**.
  **<img src="https://latex.codecogs.com/gif.latex?&#x5C;frac{1}{&#x5C;check{&#x5C;imath}}=-&#x5C;check{&#x5C;imath}"/>**
<img src="https://latex.codecogs.com/gif.latex?**
###%203.%20Extension%20on%20complex%20number
-%20On%20C-R%20function
&gt;&gt;Cauchy-Riemann%20theorem%20says%20that%20for%20complex%20number%20**"/>Z=x+yi<img src="https://latex.codecogs.com/gif.latex?**,
if%20**"/>f(Z)=u(x, y)+v(x, y)i<img src="https://latex.codecogs.com/gif.latex?**%20is%20differential%20at%20**"/>(x_0, y_0)<img src="https://latex.codecogs.com/gif.latex?**,
then%20exists:%20**"/>\left\{\begin{array}{r}u_x=v_y\\u_y=-v_x\end{array}\right.<img src="https://latex.codecogs.com/gif.latex?**
If%20spatial%20number%20**"/>S=x+y\bar{\imath}+z\acute{\imath}<img src="https://latex.codecogs.com/gif.latex?**%20and%20function%20**"/>f(Z)=u(x, y, z)+v(x, y, z)\bar{\imath}+w(x, y, z)\check{\imath}<img src="https://latex.codecogs.com/gif.latex?**%20is%20differential%20at%20**"/>(x_0,y_0,z_0)<img src="https://latex.codecogs.com/gif.latex?**
then%20exists:%20**"/>\left\{\begin{array}{r}u_x=v_y=w_z\\v_x=-u_y=0\\w_x=-w_y=-v_z-u_z\end{array}\right. <img src="https://latex.codecogs.com/gif.latex?**

If%20spatial%20number%20**"/>S=x+y\bar{\imath}+z\acute{\imath+t\check\imath}+t\grave{\imath}<img src="https://latex.codecogs.com/gif.latex?**%20and%20function%20**"/>f(Z)=u(x, y, z, t)+v(x, y, z, t)\bar{\imath}+w(x, y, z, t)\check{\imath}+r(x, y, z, t)\grave{\imath}<img src="https://latex.codecogs.com/gif.latex?**%20is%20differential%20at%20**"/>(x_0,y_0,z_0, t_0)<img src="https://latex.codecogs.com/gif.latex?**
then%20exists:%20**"/>\left\{\begin{array}{r}u_x=v_y=w_z=r_t\\v_x=-u_y=0\\w_x=-w_y=-v_z-u_z=0\\r_x=-r_y=-r_z=-u_t-v_t-w_t\end{array}\right. <img src="https://latex.codecogs.com/gif.latex?**

-%20The%20angle%20between%20two%20spatial%20numbers
If%20two%20complex%20numbers%20**"/>Z_1=re^{\theta{i}}=r(\cos{\theta}+i\sin{\theta})<img src="https://latex.codecogs.com/gif.latex?**%20and%20**"/>Z_2=\rho e^{\varphi{i}}=\rho(\cos{\varphi}+i\sin{\varphi})<img src="https://latex.codecogs.com/gif.latex?**,
the%20angle%20between%20**"/>Z_1<img src="https://latex.codecogs.com/gif.latex?**%20and%20**"/>Z_2<img src="https://latex.codecogs.com/gif.latex?**%20%20is%20**"/>\theta-\varphi<img src="https://latex.codecogs.com/gif.latex?**
**"/>\cos(\theta-\varphi)=\cos{\theta}\cos{\varphi}+\sin{\theta}\sin{\varphi}<img src="https://latex.codecogs.com/gif.latex?**

If%20two%20spatial%20numbers%20are%20given%20in%20**spatial-phase**%20expressions,%20as%20follows:%20**"/>S_1=re^{\theta{I}}=r(Recos{\theta}+IResin\theta)=aI<img src="https://latex.codecogs.com/gif.latex?**%20and%20**"/>S_2=\rho e^{\varphi{I}}=\rho(Recos{\varphi}+IResin\varphi)=bI<img src="https://latex.codecogs.com/gif.latex?**,%20then%20the%20angle%20between%20**"/>S_1<img src="https://latex.codecogs.com/gif.latex?**%20and%20**"/>S_2<img src="https://latex.codecogs.com/gif.latex?**%20is%20symblized%20as%20**"/>\theta\wedge\varphi<img src="https://latex.codecogs.com/gif.latex?**
**"/>\cos(\theta\wedge\varphi)=Recos\theta Recos\varphi+Resin\theta Resin\varphi=\frac{ab}{|a||b|}$**
  
