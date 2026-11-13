This repository is a collection of python projects developed while attending my graduate program. 
They are directly inspired by the numerical methods discussed in numerical analysis,
as well as related coursework. I will use this README to post some of the outputs 
of the programs in this repository. 

Corresponding Outputs:

-------------------------------------------------
Taylor vs Runge-Kutta Order 4 Comparisons
-------------------------------------------------

t       Taylor O4       Runge-Kutta O4  Exact           Taylor Error    Runge-Kutta Error
-------------------------------------------------------------------------------------
0.0     0.5000000000    0.5000000000    0.5000000000    0.0000000000    0.0000000000
0.1     0.6577562500    0.6574143750    0.6574145410    0.0003417090    0.0000001660
0.2     0.8299829813    0.8292982760    0.8292986209    0.0006843604    0.0000003449
0.3     1.0160986497    1.0150700584    1.0150705962    0.0010280535    0.0000005378
0.4     1.2154605498    1.2140869057    1.2140876512    0.0013728986    0.0000007455
0.5     1.4273583821    1.4256383956    1.4256393646    0.0017190174    0.0000009690
0.6     1.6510071442    1.6489393904    1.6489405998    0.0020665444    0.0000012094
0.7     1.8855392748    1.8831221786    1.8831236463    0.0024156285    0.0000014677
0.8     2.1299959699    2.1272277907    2.1272295358    0.0027664341    0.0000017451
0.9     2.3833175877    2.3801964018    2.3801984444    0.0031191433    0.0000020426
1.0     2.6443330428    2.6408567242    2.6408590858    0.0034739571    0.0000023616

<img width="982" height="789" alt="taylor4_rk4_fig" src="https://github.com/user-attachments/assets/814dab75-9aa2-40cc-9838-2949d70f2a38" />



Composite_trap_vs_Simps
Example uses n = 6 subdivision.

Enter the number of subintervals n (must b even): 6

-------------------------------------------------
Numerical Integration Result
-------------------------------------------------
Interval: [1, 3]
Number of subintervals: n = 6

Exact Area             = 0.6666666667

Composite Trapezoidal Rule
Approximation            = 0.6841180083
Absolute Error           = 1.7451341648e-02

Composite Simpson's Rule
Approximation            = 0.6678842278
 Absolute Error          = 1.2175610985e-03



<img width="854" height="576" alt="comp_trap_v_simp_fig2" src="https://github.com/user-attachments/assets/3cb8146d-b20b-4e82-9aa5-e5ecf05ebc1b" />
<img width="861" height="586" alt="comp_trap_v_simp_fig1" src="https://github.com/user-attachments/assets/3ad66a29-23ae-4477-9ceb-d8315cb2b50c" />



Derivative_Three_Point_Endpoint

THREE POINT ENDPOINT FORMULA
===============================================================================================
h = 0.1

       x      Approximation        Exact Value    Truncation Error       Absolute Error
-----------------------------------------------------------------------------------------------
    1.20      -1.1333675482      -1.1574074074     3.2150205761e-02     2.4039859205e-02
    1.50      -0.5842704729      -0.5925925926     1.0534979424e-02     8.3221196976e-03
    2.00      -0.2479104589      -0.2500000000     2.5000000000e-03     2.0895410506e-03
    3.00      -0.0737824640      -0.0740740741     3.2921810700e-04     2.9161006089e-04


<img width="869" height="579" alt="three_point_endpoint_fig" src="https://github.com/user-attachments/assets/b77383db-e365-4206-aba7-efb7f8f60f5b" />


Natural Cubic Spline vs Newton's Polynomial Interpolation

=============================================
Natural Cubic Spline
=============================================
Second derivatives:
M0 = 0.000000
M1 = 1.875000
M2 = 0.000000

Cubic Spline:

S(x) =
    5.000000  -2.125000(x-5) +0.000000(x-5)^2 +0.156250(x-5)^3,   5 <= x <= 7
    2.000000  -0.250000(x-7) +0.937500(x-7)^2 -0.156250(x-7)^3,   7 <= x <= 9


=============================================
NEWTON DIVIDED DIFFERENCES
=============================================

Divided Difference Table: 

  5.000000 -1.500000  0.625000
  2.000000  1.000000
  4.000000

Newton Coefficients:
a0 = 5.000000
a1 = -1.500000
a2 = 0.625000

Newton Interpolation Polynomial:

P(x) = 5.000000 -1.500000(x-5) +0.625000(x - 5)(x-7)

<img width="961" height="569" alt="nat_cub_splin_v_polyn_interp_fig" src="https://github.com/user-attachments/assets/4fd31a2b-094c-4138-8e5f-ee2adeffe825" />
