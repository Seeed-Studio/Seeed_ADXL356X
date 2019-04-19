Grove Accelerometer ADXL 356B/C
==============

## parameters
range : ±10g/±20g for adxl356B,±10g/±40g for adxl356C.  
It can be adjusted by operating the pad of  the module's backside.  

sensitivity: 
80mv/g for ±10g range ,   
40mv/g for ±20g range ,   
20mv/g for ±40g range .

***
## Note：
1. The annalog output of sensor is 0~1.8V,and the accuracy of the sensor is 0.5% of the full scale range.  
But the ADC resolution of arduino UNO(or other board based on atmega 328) is 10 bit.and the power supply is 5V,So it will cause deviation when using adrino for adc conversion.   
If using other board which has the lower power voltage,or the higher adc resolution,the deviation value will be decresed.

2. **The sketch default running for ADXL356B ±20g range，if you use other options,The only thing to do is change the MODULE_RANGE to corresponding value.**


***
This software is written by downey  for seeed studio<br>
Email:dao.huang@seeed.cc
and is licensed under [The MIT License](http://opensource.org/licenses/mit-license.php). Check License.txt for more information.<br>

Contributing to this software is warmly welcomed. You can do this basically by<br>
[forking](https://help.github.com/articles/fork-a-repo), committing modifications and then [pulling requests](https://help.github.com/articles/using-pull-requests) (follow the links above<br>
for operating guide). Adding change log and your contact into file header is encouraged.<br>
Thanks for your contribution.

Seeed Studio is an open hardware facilitation company based in Shenzhen, China. <br>
Benefiting from local manufacture power and convenient global logistic system, <br>
we integrate resources to serve new era of innovation. Seeed also works with <br>
global distributors and partners to push open hardware movement.<br>
