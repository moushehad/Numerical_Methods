This repository is a collection of python projects developed while attending my graduate program. 
They are directly inspired by the numerical methods discussed in numerical analysis,
as well as related coursework. I will use this README to post some of the outputs 
of the programs in this repository. 

Corresponding Outputs:

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
