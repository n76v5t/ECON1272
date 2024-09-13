java c
ECON1272
Basic Econometrics
Individual Assignment
This is an individual assignment where you must work alone. You must submit an electronic copy of your assignment in Canvas in pdf, doc or docx format. Hard copies and submission via email will not be accepted. Show your calculations (if any) as well as answering the questions in clear full sentences. Log referrers to natural logarithm.
QUESTION 1)
We model the salary of the average inhabitant of Pinkland. Salaries are a function of education (expressed in years), working hours (expressed in hours), firm sales (expressed in millions of pinkies) and sector. There are 3 sectors in Pinkland, namely agriculture, industry and service.
Salaries are expressed in pinkies (currency of Pinkland). The model is estimated as follows:
Log(salary) = 1.2 + 0.166*educ + 0.76*log(hours) + 0.16*log(sales) + 0.35*service -
0.13*agriculture
N=800
R2 = 0.63
1) Interpret the coefficient on education. What type of relationship is this?
This is a log-linear relationship，where each additional year of education increases the log of salary by 0.166.  2 marks
2) Interpret the coefficient on “hours” and “sales”. What type of relationship are these?  4 marks
3) We have 3 categorical variables in the regression. Which is the base category?   1 mark
4) Interpret the coefficient on “service” and “agriculture”.   4 marks
5) Calculate the degrees of freedom for the regression and explain if standard normal critical values can be used or not.   1 marks
Don’t forget: Log referrers to natural logarithm!Subtotal: 13 marksQUESTION 2
Use the dataset: Energy.RData,
Use R to run a cross sectional regression on energy use per capita for the listed countries as follows:
lntpes_pc = ���� + ������ + �������� + ������ + �������� + ���� + ���� + ��
The variables are defined as follows: lntpes_pc = log of total primary
energy consumption per capita (ktoe)
lnypcpenn =log of GDP per capita (USD) lnypcpenn2 =
square of log of GDP per capita (USD) ln_gasprice = log
of pump price for gasoline (USD/liter) ln_annualprecip=
log of annual precipitation (mm) ffrents = Fossil Fuel
Rents (% of GDP) lnpop = log of population (in millions)
lnland = log of land area (in km代 写ECON1272 Basic Econometrics Sem 2 2024Java
代做程序编程语言2)
I_Incomegroup = refers to income groups “1” , “2” and “3”, low, mid and high income
countries.
*”Log” always refers to natural logs or “ln” here.
Log referrers to natural logarithm!
1) Present your regression results in a table below (R output):   5 marks
2) Interpret the constant and its p-value.   3 marks
3) Interpret the coefficient on gas price and its p-value.   3 marks
4) Interpret the coefficient on ln land and carry out (meaning: calculate with the official formula) a t-test to determine the significance of the coefficient.   3 marks
5) Interpret the coefficient on ff-rents and its p-value.     3 marks
6) The above model belongs to the class of nonlinear equations. Calculate the turning point of the nonlinear relationship.  3 marks 
7) Is this a U-shaped or inverted U-shaped relationship?   1 mark
8) Interpret the adjusted R2 of the regression.    `2 marks
9) a) Please define MLR 3 and describe if MLR 3 is likely to hold or not?
b) Please define MLR 4 and describe if MLR 4 is likely to hold or not? What other variables might be in the error term?2 x2=4 marksSubtotal: 27 marks
Assignment Total: 40 marks
FORMULA SHEET
Critical values for the standard normal distribution (z)Confidence level(1-α)Level ofSignificance (α)Two–Sided
Critical Valuecα/2One-Sided,Upper-TailCritical Value cαOne-Sided,Lower-TailCritical Value -cα90%10%1.6451.28-1.2895%5%1.961.645-1.64599%1%2.582.33-2.33
Formula for a t-statistic
������ − ℎ��ℎ���� ��
�� = 
������ ������
Formula for a (1-α)% confidence interval
������ = ��̂ − ����/2 ∗ ����̂, ��̂ + ����/2 ∗ ����̂
Logarithmic/Quadratic/Interaction specifications
For the model ��() = ��̂0 + ��̂ + ��̂22, the exact effect of a change in explanatory variable x2 is:
%∆ = 100exp��̂2∆2 − 1
For a quadratic specification of the form.  = ��0 + �� + ��22 + 
The turning point (maximum/minimum) is given by:
∗ = ��̂/(2��̂2)
The approximation of the marginal effect of x on y is given by:
∆
≈ ��̂ + 2��̂2
∆
For a interaction specification of the form.  = ��0 + �� + ��2 ∗ 2 +  The approximation of the marginal effect of x1 on y is given by: ∆ 1 ��̂ + ��̂22��

         
加QQ：99515681  WX：codinghelp
