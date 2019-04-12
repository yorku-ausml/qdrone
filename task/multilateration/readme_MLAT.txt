* 2019/4/12
* Jungwon Kang


================================================================================================================
#### files
================================================================================================================
* current multilateration algorithm = algebraic solution + non-linear optimization

@@ mlat_jungwon
: written in matlab
  include current multilateration algorithm (= algebraic solution + non-linear optimization). 

@@ MFCApplication_trilateration_20170929_1
: written in c++
  include only algebraic solution -> it does not include non-linear optimization.


================================================================================================================
#### what to do
================================================================================================================

@ Implemeting non-linear optimization (Levenberg-Marquardt) in MFCApplication_trilateration_20170929_1
  - It is highly recommended to use OpenCV. (Hopefully, 3.x)
  - The implementation should be validated by simulation.
  - The implementation should be validated by Oshawa dataset.





The end-of-the-file



