README3


This imp new pulse code test 

this code is merged code with all 5 modes and pulse count in distance mode added.

We need to test this code to check if correct number of pulses are added.

if yess then do the necessary pulse logic code changes in my feedback codes.


=============================================================


pulse logic


we are using 1/32 step mode

which means  1.8 degree ==> 32 microsteps ==> 1 full steps


our stepper motor needs 5 revolution to cover 80cm distance == 32000 micro steps


also 1 stepper motor = 4 wheel revolution 


wheel has 36 slits ==> 1 rotation (complete 360 degree ) of wheel equals 36 pulses

10 degree == 1 pulse


Use this to count pulses


Also this is a optical limit switch : It works on low to high transition . eg: when there is no obstruction ( gap )  it doesn't count . It will only count when it detects change from gap to obstruction or vice versa


====================================================================

I have made the coee with this logic . test and verify